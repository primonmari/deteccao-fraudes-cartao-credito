# Detecção de Fraudes em Transações de Cartão de Crédito

Projeto de **Machine Learning** desenvolvido para identificar transações potencialmente fraudulentas por meio da análise de dados históricos e comparação de diferentes modelos de classificação.

**Projeto desenvolvido por:** Marislene Primon

**Formação:**
Projeto desenvolvido no módulo **Análise de Dados com Python: Da Preparação à Aplicação com Segurança**, do **Bootcamp Bradesco – GenAI, Dados & Cyber**, realizado pela **DIO (Digital Innovation One)**.

---

## Sobre o Projeto

A detecção de fraudes em transações financeiras é um problema de classificação que apresenta um grande desafio devido ao forte desbalanceamento entre transações legítimas e fraudulentas.

Neste projeto, foram aplicadas técnicas de Machine Learning para analisar os dados, comparar diferentes modelos de classificação e realizar o ajuste do modelo selecionado.

O desenvolvimento completo, incluindo análise exploratória, preparação dos dados, treinamento, avaliação, gráficos e interpretação dos resultados, está disponível no notebook do projeto.

---

## Objetivos

Desenvolver um modelo de Machine Learning capaz de auxiliar na identificação de transações fraudulentas, considerando o forte desbalanceamento das classes e utilizando técnicas de avaliação e explicabilidade.

---

## Dataset

Foi utilizado o dataset **Credit Card Fraud Detection**, contendo:

* **284.807** transações;
* **284.315** transações legítimas;
* **492** transações fraudulentas;
* Aproximadamente **0,17%** das transações são fraudulentas.

As variáveis `V1` a `V28` correspondem a componentes obtidos por **PCA (Principal Component Analysis)**.

A variável `Class` representa o resultado da transação:

```text
0 → Transação legítima
1 → Transação fraudulenta
```

---

## Tecnologias Utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* SHAP
* Google Colab
* GitHub

---

## Modelos Avaliados

Foram avaliados três modelos de classificação:

* **Logistic Regression**
* **Random Forest**
* **XGBoost**

Após a comparação inicial, o XGBoost foi selecionado para o ajuste de hiperparâmetros utilizando GridSearchCV.

Os resultados completos da comparação e da avaliação final estão disponíveis no notebook.

---

## Avaliação e Explicabilidade

O projeto utiliza métricas e técnicas adequadas ao problema de desbalanceamento das classes, incluindo:

* **Precision**
* **Recall**
* **F1-score**
* **Curva ROC**
* **Curva Precision-Recall**
* **Importância das variáveis**
* **SHAP**

A análise detalhada dessas etapas e os respectivos resultados estão disponíveis no notebook do projeto.

---


## Como Executar

O projeto foi desenvolvido utilizando **Google Colab**.

1. Abra o arquivo `Deteccao_Fraudes_transacao_bancaria.ipynb` no Google Colab.
2. Execute as células em sequência.

O dataset é carregado diretamente durante a execução do projeto.

---

## Referência

**TensorFlow — Classification on imbalanced data**

[Tutorial oficial do TensorFlow](https://www.tensorflow.org/tutorials/structured_data/imbalanced_data?hl=pt-br&utm_source=chatgpt.com)

---

## Conclusão

O projeto demonstrou a aplicação de Machine Learning na detecção de fraudes em transações de cartão de crédito, envolvendo análise dos dados, comparação de modelos, ajuste de hiperparâmetros e técnicas de explicabilidade.

O XGBoost foi selecionado após a comparação dos modelos e posteriormente submetido ao ajuste de hiperparâmetros.

Como etapa complementar, foi utilizada a biblioteca SHAP para analisar a influência das variáveis nas previsões do XGBoost.

O desenvolvimento completo e os resultados obtidos podem ser consultados no notebook disponível neste repositório.

---

**Projeto desenvolvido como parte do Bootcamp Bradesco – GenAI, Dados & Cyber | DIO**
