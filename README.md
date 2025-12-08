# Medical Cost Prediction & Analysis

Projeto de Modelagem Estatística desenvolvido para a disciplina de Ciência da Computação do CESUPA. O objetivo é prever custos médicos e identificar perfis de risco (fumantes) utilizando Machine Learning.

## 📊 Visão Geral
Este repositório contém uma análise completa "end-to-end":
1. **EDA:** Análise exploratória detalhada dos dados de seguro.
2. **Regressão:** Modelos Lineares, Polinomiais e AutoML para prever o valor `charges`.
3. **Classificação:** Algoritmos (Naive Bayes, Regressão Logística) para identificar a variável `smoker`.

## 🛠️ Instalação e Execução

Para reproduzir este projeto, siga os passos abaixo:

1. Clone o repositório:
   ```bash
   git clone https://github.com/davib4d/insurance-data-analysis.git
   cd medical-cost-prediction

2. Crie e ative um ambiente virtual:
    python -m venv venv
    # Windows: venv\Scripts\activate
    # Linux/Mac: source venv/bin/activate

3. Instale as dependências:
    pip install -r requirements.txt

4. Execute o notebook:
    jupyter notebook projeto_modelagem.ipynb
