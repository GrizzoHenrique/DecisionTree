# Projeto de Credit Score – Árvore de Decisão (Módulo 21)

**Este notebook apresenta a aplicação do algoritmo de Árvore de Decisão para previsão de Credit Score, dando continuidade às etapas anteriores de tratamento e preparação dos dados.**

### Objetivo

**Treinar e avaliar um modelo de classificação capaz de prever o score de crédito dos clientes com base em variáveis previamente tratadas.**

### Tecnologias utilizadas
| Tecnologia | Versão | Propósito |
|-----------|--------|----------|
| ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) | 3.7 | Linguagem Principal|
| ![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white) | Latest | Manipulação de dados |
| ![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white) | Latest | Computação numérica |
| ![Plotly Express](https://img.shields.io/badge/Plotly-Express-3F4F75?logo=plotly&logoColor=white) | Latest | Visualização Interativa|
| ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?logo=matplotlib&logoColor=white) | Latest | Visualizações |
| ![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?logo=seaborn&logoColor=white) | Latest | Gráficos estatísticos |
| ![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?logo=scikit-learn&logoColor=white) | Latest | Implementação Decision Tree |

### Etapas do Projeto

* Carregamento das bases

* Importação dos conjuntos de treino (X_train, y_train) e teste (X_test, y_test)

* Verificação de consistência das dimensões

* Conferência do balanceamento da variável alvo

* Revisão do Pré-processamento

* Dados já tratados em módulos anteriores:

* Limpeza e tratamento de valores ausentes

* Transformação de variáveis categóricas

* Balanceamento de classes

* Modelagem com Árvore de Decisão

* Treinamento do modelo

* Ajuste de hiperparâmetros

* Aplicação do modelo na base de teste

* Avaliação do Modelo

* Análise de métricas de desempenho

* Avaliação da capacidade de generalização

* Discussão sobre possíveis melhorias (ex: poda, ajuste de profundidade, tuning de parâmetros)


### Conceitos Aplicados

* Aprendizado Supervisionado

* Classificação

* Árvore de Decisão

* Balanceamento de Classes

* Métricas de Avaliação de Modelos

## Como Rodar este projeto
### Pré-requisitos
- Python 3.7+
- pip ou conda

### Instalação

```bash
# Clone o repositório
git clone https://github.com/GrizzoHenrique/DecisionTree.git
cd SQLadvanced

# Crie um ambiente virtual (recomendado)
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate

# Instale as dependências
pip install -r requirements.txt


