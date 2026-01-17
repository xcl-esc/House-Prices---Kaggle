# House Prices - Kaggle

Projeto de análise exploratória e modelagem preditiva utilizando o dataset
**House Prices: Advanced Regression Techniques** do Kaggle.

## Objetivo
Identificar os principais fatores que influenciam o preço de venda de imóveis
e construir um modelo preditivo com base nesses atributos.
Gerando assim recomendações de alterações no imóvel que possam aumentar o seu valor e também
ter uma base de valor inicial do imóvel.

## Dataset
- Fonte: Kaggle – House Prices
- Target: `SalePrice`

## Principais Insights
- Área construída (`GrLivArea`) e área do lote (`LotArea`) têm forte correlação com preço
- Garagem (área e número de vagas) impacta diretamente imóveis acima da média
- Localização (`Neighborhood`) pode anular efeitos positivos de área e idade
- Foram identificados outliers estruturais com alto impacto no preço

## Tecnologias
- Python 3.13.5
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## Como executar 
```bash
pip install -r requirements.txt
jupyter notebook


- Modelagem (em andamento)

Os próximos passos incluem:

- Treinamento de modelos de regressão

- Avaliação com métricas como MAE, RMSE e R²

- Comparação de modelos com e sem outliers

- Simulação de cenários para estimar faixas de preço com base em características do imóvel

