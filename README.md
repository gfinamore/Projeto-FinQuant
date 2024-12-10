## Projeto final de Finanças Quantitativas - Minimização de Variância
<div align="center">

  *Participantes:*  
  <a href="https://github.com/juliacvieira">[![GitHub Badge](https://img.shields.io/badge/juliacvieira-100000?style=for-the-badge&logo=GitHub&logoColor=white)](https://github.com/juliacvieira)</a>
  <a href="https://github.com/gfinamore">[![GitHub Badge](https://img.shields.io/badge/gfinamore-100000?style=for-the-badge&logo=GitHub&logoColor=white)](https://github.com/gfinamore)</a>

</div>

# Estratégia de investimento de longo prazo

Quando abordamos risco em investimento, geralmente pensamos que está ligado com a variância dos retornos - sobretudo os negativos. Nesse sentido, a ideia principal do nosso projeto é realizar uma minimização da variância do portfólio, para mitigar os riscos de um possível drawdown. Assim, rebalanceando os pesos a cada mês, é possível obter retornos consistentes para uma carteira de investimentos no longo prazo.

## Overview 🧐

O desenvolvimento da estratégia está dividido da seguinte forma:

1. Alocação inicial - portfólio com pesos iguais;
2. Otimização - minimização da volatilidade e rebalanceamento dos pesos alocados para cada ação do portfólio;
3. Cálculo e apresentação de métricas de risco - VaR, CVaR e EWMA;
4. Avaliação de performance - comparativo com *benchmark*.

Os dados utilizados para o projeto foram retirados da biblioteca `yfinance`.

## Instalação 👨‍💻👩‍💻

As seguintes dependências foram utilizadas:

### Manipulação de dados:

- `pandas`
- `numpy`

### Visualização de dados:

- `matplotlib`
- `plotly.express`
- `plotly.graph_objects`

### Outros:

- `statsmodels`
- `scipy`


## Resultados 💛🖤

Os resultados das análises podem ser conferidos nos arquivos Jupyter Notebook (.ipynb) disponíveis neste repositório, bem como na [publicação feita no perfil do FEA.dev no Instagram]().
