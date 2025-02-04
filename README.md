# Predicao_de_preco_de_aluguel
Modelo de predição de preço de aluguel

# Análise e Modelagem Preditiva de Preços

Este projeto realiza a análise exploratória de dados (EDA) e a modelagem preditiva de preços de aluguéis temporários na cidade de Nova York. O modelo final utiliza uma regressão com **Random Forest** para estimar o preço de locação de propriedades.

## 📁 Estrutura do Projeto

- `EDA.ipynb`: Notebook com a análise exploratória dos dados.
- `modelo.ipynb`: Notebook com o pipeline de modelagem preditiva.
- `modelo_predicao1.pkl`: Arquivo com o modelo treinado.
- `train.csv` e `test.csv`: Dados de treino e teste separados.
- `requirements.txt`: Lista de pacotes necessários para rodar o projeto.

## 🚀 Como Executar o Projeto

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/victoriaT19/Predicao_de_preco_de_aluguel.git
   cd nome-do-seu-repositorio

📊 Resultados
O modelo foi avaliado utilizando as métricas:

- MAE (Erro Absoluto Médio): Resultado 44,65
- RMSE (Raiz do Erro Quadrático Médio): Resultado 73,08
- R² (Coeficiente de Determinação): Resultado  0,51

📦 Requisitos

- joblib
- matplotlib
- nbconvert
- nbformat
- numpy
- pandas
- scikit_learn
- scipy
- seaborn
- statsmodels
- wordcloud
