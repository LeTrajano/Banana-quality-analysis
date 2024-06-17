# Análise da Qualidade da Banana

Este repositório contém um estudo completo sobre a qualidade das bananas, incluindo limpeza, processamento, análise de dados e a construção de um modelo de classificação utilizando Random Forest. Além disso, foram geradas diversas visualizações para entender a distribuição das variáveis e a relação entre elas.

  Sumário:

    - Introdução
    - Pré-processamento dos Dados
    - Análise Exploratória de Dados (EDA)
    - Construção e Avaliação do Modelo
    - Análise de Correlação
    - Visualizações Adicionais
    - Dashboard Interativo
    - Conclusão

## Introdução

Este projeto tem como objetivo analisar a qualidade das bananas com base em várias características, como tamanho, peso, doçura, tempo de colheita, suavidade, maturação e acidez. A classificação da qualidade (Boa ou Ruim) é realizada com o uso de algoritmos de machine learning.
 
  *Estrutura do Projeto:*

- `banana_quality.ipynb`: Notebook Jupyter contendo o código e análises.
- `banana_quality.csv`: Arquivo de dados utilizado no projeto.
- `README.md`: Este arquivo.


  *Requisitos*

- Python 3.x
- Bibliotecas: pandas, numpy, matplotlib, seaborn, scikit-learn, plotly, dash
- 
## Pré-processamento dos Dados

Os dados são carregados de um arquivo CSV, colunas são renomeadas para português, valores ausentes são preenchidos com zero e valores negativos são substituídos pela mediana de cada coluna.

## Análise Exploratória de Dados (EDA)

Diversas visualizações foram geradas para entender a distribuição das variáveis e a relação entre elas, incluindo histogramas, boxplots e scatter plots.

## Construção e Avaliação do Modelo

Utilizamos o Random Forest para classificar a qualidade das bananas. O desempenho do modelo foi avaliado utilizando métricas como acurácia, sensibilidade, especificidade, precisão e f1-score.

## Análise de Correlação

Visualizamos a matriz de correlação para entender as relações entre as variáveis.

## Visualizações Adicionais

Foram gerados gráficos de barras e scatter plots para diferentes variáveis, destacando a distribuição e a relação entre as variáveis e a qualidade das bananas.

## Dashboard Interativo

Criamos um dashboard interativo utilizando Dash para explorar os dados de forma dinâmica.

 Como Usar:

1. Clone o repositório.
2. Instale os requisitos utilizando `pip install -r requirements.txt`.
3. Execute o notebook `banana_quality.ipynb` para visualizar as análises.
4. Para visualizar o dashboard, execute o script `app.py` utilizando `python app.py`.


## Conclusão

Este projeto forneceu uma análise detalhada da qualidade das bananas utilizando técnicas de pré-processamento, visualização de dados e modelagem preditiva. A construção de um dashboard interativo com Dash também permite uma exploração dinâmica e intuitiva dos dados.


 *Resultados:*

Os principais resultados e visualizações incluem:
- Análise exploratória dos dados
- Treinamento e avaliação de um modelo Random Forest
- Visualizações de correlação e distribuições
- Dashboard interativo utilizando Dash e Plotly

----------------------------------------------------------------------------------------------

**- Exemplo de Uso:**

python

import pandas as pd

# Carregar dados
dados_banana = pd.read_csv('/path/to/banana_quality.csv')

# - Pré-processar dados
# (ver script principal para detalhes)

# - Treinar modelo
# (ver script principal para detalhes)

# - Avaliar modelo
# (ver script principal para detalhes)

*Para detalhes completos, veja o código no arquivo Jupyter Notebook neste repositório.* 

