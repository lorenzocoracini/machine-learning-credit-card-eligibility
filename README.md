# Comparação de Modelos de Classificação com Base em Dados Reais

##  Estrutura do Repositório

Este repositório contém a implementação de dois algoritmos de aprendizado de máquina para um problema de classificação binária. O objetivo é prever corretamente a variável-alvo `Target` com base em diversas variáveis sociodemográficas e econômicas.

### Dataset

Foi utilizado a seguinte base de dados: https://www.kaggle.com/datasets/rohit265/credit-card-eligibility-data-determining-factors?resource=download

### Arquivos

- `dataset.csv`: Base de dados original contendo as informações utilizadas nos modelos.
- `Gaussuian.ipynb.py`: Script/notebook com a implementação do modelo **Naive Bayes**.
- `MLP.ipynb`: Script/notebook com a implementação do modelo **MLP (Multilayer Perceptron)**.

---


##  Modelos Treinados

### 🔹 Naive Bayes
- Utilizado: `GaussianNB`
- Dados não escalados.

### 🔹 MLP 
- Arquitetura: 2 camadas ocultas (64 e 32 neurônios).
- Ativação: ReLU
- Otimizador: Adam
- Número máximo de iterações: 1000

---

##  Avaliação dos Modelos

###  Métrica Utilizada: Medida F1

A **medida F1** é uma média harmônica entre *precisão* e *revocação*, muito útil em bases desbalanceadas.

---

##  Resultados Finais

| Modelo       | Medida F1 |
|--------------|------------|
| Naive Bayes  | 0.92 |
| MLP          | 0.89 |

