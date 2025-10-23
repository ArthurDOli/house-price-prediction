# House Price Prediction

Este repositório contém o código para um projeto de Machine Learning que prevê
os preços de venda de casas com base no dataset "[House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview)" do Kaggle.

## Visão Geral

Este repositório contém notebooks usados para explirar, pré-processar, modeloar e submeter as previsões para a competição do Kaggle, que até o momento se encontra entre os **top 10%~15%** melhores resultados da competição.

## Estrutura do Repositório

- `house_price_prediction.ipynb`: Notebook "Laboratório" - Contém todo o processo de exploração e a busca _lenta_ por hiperparâmetros usando Validação Cruzada (`cv=5`). **Saída:** Melhor score CV e melhores parâmetros.
- `house_price_prediction_submission.ipynb`: Notebook "Produção" - Código **limpo e rápido** que usa os melhores parâmetros encontrados no laboratório para treinar o modelo final e gerar o arquivo de submissão.

## Instalação e Configuração

Siga os passos abaixo para configurar e executar o projeto localmente:

1.  **Clone o repositório:**

    ```bash
    git clone https://github.com/ArthurDOli/house-price-prediction.git
    cd house-price-prediction
    ```

2.  **Crie e ative um ambiente virtual:**

    ```bash
    python -m venv venv
    # No Windows
    venv\Scripts\activate
    # No macOS/Linux
    source venv/bin/activate
    ```

3.  **Instale as dependências:**

    ```bash
    pip install -r requirements.txt
    ```

4.  **Acessar os dados:**
    Para acessar os dados, faça download deles no [site oficial da competição](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)
