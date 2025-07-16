# 📊 Explorando o Poder do Data Mining com Python

Este repositório apresenta uma coleção de projetos práticos de Data Mining, implementados em Python, demonstrando a aplicação de diversas técnicas para extrair insights valiosos e tomar decisões embasadas a partir de grandes volumes de dados. Cada cenário aborda um problema de negócio ou análise diferente, utilizando bibliotecas essenciais como Pandas, Scikit-learn, Matplotlib e Seaborn.

---

## 🚀 Projetos Destaque

Explore como o Data Mining pode ser aplicado em diferentes domínios:

### [cite_start]1. Previsão de Consumo de Energia Elétrica Residencial (Regressão) [cite: 54, 55]

### 1. Previsão de Consumo de Energia
- **Objetivo**: Prever o consumo de energia elétrica residencial utilizando regressão linear.
- **Base de Dados**: [Household Power Consumption](https://www.kaggle.com/uciml/electric-power-consumption-data-set).
- **Resultado**: Gráficos de dispersão comparando valores reais e previstos, com métricas de erro (RMSE).

- <img width="663" height="429" alt="image" src="https://github.com/user-attachments/assets/f396a546-e5a6-4987-b73d-f1c5b3cb07e7" />
O gráfico acima mostra a comparação entre os valores reais e os valores previstos pelo modelo de Regressão Linear para a Intensidade Global.

---

### 2. Associação em Clientes de Shopping
- **Objetivo**: Identificar padrões de comportamento entre clientes de shopping usando regras de associação.
- **Base de Dados**: `Mall Customers` (demográfica).
- **Resultado**: Heatmap das relações de lift entre características como faixa etária, gênero e renda.

- <img width="659" height="498" alt="image" src="https://github.com/user-attachments/assets/bc99ccc6-5778-45fa-a65c-287abd8a5567" />
O mapa de calor acima representa as regras de associação entre diferentes atributos com base no coeficiente Lift. Valores mais altos indicam associações mais fortes.
--- 

### 3. Segmentação de Clientes de E-commerce
- **Objetivo**: Agrupar clientes com base em comportamento de compra utilizando K-Means.
- **Base de Dados**: [E-Commerce Data](https://www.kaggle.com/carrie1/ecommerce-data).
- **Resultado**: Gráfico de dispersão mostrando clusters de comportamento.

- <img width="515" height="402" alt="image" src="https://github.com/user-attachments/assets/5829a773-f8e2-4a03-9e65-110b9dbb6b64" />
O gráfico do Método do Cotovelo ajuda a determinar o número ideal de clusters para o algoritmo K-Means. O ponto de inflexão no gráfico indica o número recomendado de clusters.


---

### 4. Previsão de Diabetes
- **Objetivo**: Prever se pacientes têm diabetes usando o algoritmo Random Forest.
- **Base de Dados**: [Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database).
- **Resultado**: Heatmap da matriz de confusão, além de métricas como acurácia.

<img width="515" height="446" alt="image" src="https://github.com/user-attachments/assets/acb11e0e-6bf1-4188-828d-e443cf96560d" />

A matriz de confusão acima mostra o desempenho do modelo Random Forest na classificação de diabetes, indicando verdadeiros positivos, falsos positivos, verdadeiros negativos e falsos negativos.

---

## 🛠️ Tecnologias Utilizadas
- **Python**: Linguagem principal.
- **Bibliotecas**:
  - `pandas`, `numpy` - Manipulação de dados.
  - `matplotlib`, `seaborn` - Visualizações gráficas.
  - `scikit-learn` - Algoritmos de aprendizado de máquina.
- **Google Colab**: Ambiente de desenvolvimento e execução.

## 📋 Estrutura do Projeto
- **Notebook Principal**: Contém a implementação dos quatro cenários com explicações detalhadas e gráficos.
- **Imagens**: Inclui capturas de gráficos gerados no projeto para referência.

## 🖥️ Como Executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/larislima11/data-mining.git
