## Análise Exploratória de Dados (EDA) com o Dataset Iris Flower 🌸

Este projeto foi desenvolvido como parte das atividades da pós-graduação em **Engenharia e Arquitetura de Dados**. Nele, realizamos uma **Análise Exploratória de Dados (EDA)** utilizando o famoso **Iris Dataset (O 'Hello World' da Ciência de Dados)**, com o objetivo de apresentar visualmente as características do conjunto de dados e reforçar a importância da EDA no processo de tomada de decisão baseada em dados.

### 📌 Objetivo

Demonstrar, por meio de um estudo de caso prático, como **engenheiros de dados** podem apoiar **stakeholders** e **equipes de negócio** na geração de insights a partir de dados, além de explorar a aplicação de técnicas básicas de **Machine Learning (ML)** com foco em **classificação supervisionada**.

---

### 📂 Estrutura do Projeto

O projeto segue os seguintes passos:

1. **Carregamento dos dados**  
   Utilização da biblioteca `pandas` para ler o arquivo CSV e transformar em um dataframe.

2. **Inspeção Inicial**
   - Visualização do shape do dataset
   - Estrutura das colunas e tipos de dados (`df.info()`)
   - Resumo estatístico (`df.describe()`)

3. **Verificação de dados ausentes**
   - Detecção de valores nulos usando `isnull().sum()`

4. **Análise de espécies**
   - Checagem de duplicatas
   - Contagem por classe (`species`)

5. **Visualizações com `matplotlib` e `seaborn`**
   - Relação entre comprimento e largura da sépala
   - Relação entre comprimento e largura da pétala
   - `pairplot` com todas as combinações
   - Histogramas
   - Mapa de calor de correlação (`heatmap`)
   - Boxplots para identificação de **outliers**

---

### 🧠 Tecnologias Utilizadas

- **Python 3.12**
- **Pandas**
- **Seaborn**
- **Matplotlib**

---

### 🗃️ Dataset

- Dataset: [Iris Dataset - Kaggle](https://www.kaggle.com/datasets/uciml/iris)
- Atributos:
  - `sepal_length`
  - `sepal_width`
  - `petal_length`
  - `petal_width`
  - `species`

---
