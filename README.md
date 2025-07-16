# Estudo de Data Mining para disciplina de Bussiness Inteligence do Centro Universitário Facens.

Este repositório apresenta uma coleção de projetos práticos de Data Mining, implementados em Python, demonstrando a aplicação de diversas técnicas para extrair insights valiosos e tomar decisões embasadas a partir de grandes volumes de dados. Cada cenário aborda um problema de negócio ou análise diferente, utilizando bibliotecas essenciais como Pandas, Scikit-learn, Matplotlib e Seaborn.

---

## Projetos Destaque

Explore como o Data Mining pode ser aplicado em diferentes domínios:

### 1. Previsão de Consumo de Energia Elétrica Residencial (Regressão)

**Objetivo:** Prever o consumo de energia elétrica residencial utilizando técnicas de regressão.
* **Técnica:** Regressão Linear, Regressão Polinomial, Redes Neurais (O notebook específico usa Regressão Linear).
* **Base de Dados:** "Household Power Consumption" disponível no Kaggle.
* **Insights:** O modelo prevê a intensidade global de energia em função da potência ativa, hora e mês. A visualização dos valores reais vs. previstos permite avaliar a qualidade das previsões.
* **Habilidades Demonstradas:** Manipulação e limpeza de séries temporais com Pandas, construção e avaliação de modelos de regressão com Scikit-learn, e visualização de resultados com Matplotlib/Seaborn.

- <img width="663" height="429" alt="image" src="https://github.com/user-attachments/assets/f396a546-e5a6-4987-b73d-f1c5b3cb07e7" />
O gráfico acima mostra a comparação entre os valores reais e os valores previstos pelo modelo de Regressão Linear para a Intensidade Global.

---

###2. Identificação de Padrões de Compra em Clientes de Shopping (Regras de Associação)
-**Objetivo:** Identificar padrões de comportamento dos clientes de um shopping utilizando regras de associação.
* **Técnica:** Associação (Algoritmo Apriori).
* **Base de Dados:** "Mall Customers".
* **Insights:** Através da análise, é possível identificar quais características de clientes (faixa etária, gênero, renda) frequentemente aparecem juntas, revelando oportunidades para ofertas direcionadas. O Heatmap de Lift visualiza a força dessas associações.
* **Habilidades Demonstradas:** Pré-processamento de dados para regras de associação (categorização e one-hot encoding), aplicação do algoritmo Apriori com `mlxtend` e interpretação de métricas como Suporte, Confiança e Lift.


<img width="661" height="498" alt="image" src="https://github.com/user-attachments/assets/8a0648d6-be3d-41a9-9d9b-fbf5ade37b0f" />
O mapa de calor acima representa as regras de associação entre diferentes atributos com base no coeficiente Lift. Valores mais altos indicam associações mais fortes.

--- 

### 3. Segmentação de Clientes de E-commerce (Agrupamento)

* **Objetivo:** Segmentar clientes de um e-commerce com base em características de compra.
* **Técnica:** Agrupamento (K-Means, DBSCAN, Hierarchical Clustering - o notebook específico usa K-Means).
* **Base de Dados:** "E-Commerce Data" disponível no Kaggle.
* **Insights:** A segmentação revela perfis de clientes distintos (ex: clientes que gastam muito em poucas compras, ou que fazem muitas compras de baixo valor), permitindo abordagens personalizadas.
* **Habilidades Demonstradas:** Feature engineering (criação de `TotalPrice` e `TransactionCount`), normalização de dados, uso do Método do Cotovelo para determinar o número ótimo de clusters e visualização de clusters com Seaborn.

- <img width="515" height="402" alt="image" src="https://github.com/user-attachments/assets/5829a773-f8e2-4a03-9e65-110b9dbb6b64" />
O gráfico do Método do Cotovelo ajuda a determinar o número ideal de clusters para o algoritmo K-Means. O ponto de inflexão no gráfico indica o número recomendado de clusters.


---

### 4. Previsão de Diabetes em Pacientes (Classificação)

* **Objetivo:** Prever se um paciente tem ou não diabetes.
* **Técnica:** Classificação (Árvores de Decisão, Random Forest, SVM, Redes Neurais - o notebook específico usa Random Forest).
* **Base de Dados:** "Diabetes Dataset" disponível no Kaggle. [Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database).
* **Insights:** O modelo Random Forest é utilizado para classificar pacientes, e a avaliação é feita através da acurácia e da matriz de confusão, que ajuda a entender os tipos de erros (falsos positivos/negativos).
* **Habilidades Demonstradas:** Divisão de dados em conjuntos de treino e teste, treinamento de modelo de classificação robusto com Scikit-learn e interpretação de métricas de avaliação como Acurácia e Matriz de Confusão.

<img width="515" height="446" alt="image" src="https://github.com/user-attachments/assets/acb11e0e-6bf1-4188-828d-e443cf96560d" />
A matriz de confusão acima mostra o desempenho do modelo Random Forest na classificação de diabetes, indicando verdadeiros positivos, falsos positivos, verdadeiros negativos e falsos negativos.

---

## Tecnologias Utilizadas

* **Python**
* **Pandas:** Manipulação e análise de dados.
* **NumPy:** Computação numérica.
* **Scikit-learn (sklearn):** Implementação de algoritmos de Machine Learning (Regressão Linear, Random Forest, K-Means) e pré-processamento de dados.
* **Matplotlib:** Geração de gráficos estáticos.
* **Seaborn:** Visualizações estatísticas atraentes e simplificadas.
* **mlxtend:** Para regras de associação (Apriori).

## Como Executar
1. Clone este repositório:
   
  ```bash
     ``` bash git clone https://github.com/larislima11/data-mining.git
       ```

   **Instale as dependências:**
    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn mlxtend
    ```
  ```

**Baixe as bases de dados:**
    * **Consumo de Energia:** Baixe `household_power_consumption.txt` do Kaggle: [https://www.kaggle.com/uciml/electric-power-consumption-data-set](https://www.kaggle.com/uciml/electric-power-consumption-data-set)
    * **Clientes de Shopping:** Certifique-se de ter `Mall_Customers.csv` na pasta do projeto.
    * **E-commerce:** Baixe `data.csv` do Kaggle: [https://www.kaggle.com/carrie1/ecommerce-data](https://www.kaggle.com/carrie1/ecommerce-data)
    * **Diabetes:** Baixe `diabetes.csv` do Kaggle: [https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
