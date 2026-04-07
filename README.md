# 🏠 House Prices Prediction

Projeto de Machine Learning para prever preços de imóveis utilizando dados do Kaggle.

## 🎯 Objetivo

Prever o preço de venda de imóveis com base em características estruturais usando modelos de regressão.

## 🛠 Tecnologias

* Python
* Pandas, Numpy
* Scikit-learn
* XGBoost
* Matplotlib, Seaborn

## ⚙️ Pipeline

* Análise exploratória (EDA)
* Transformação log do target
* Feature engineering (seleção + encoding)
* Treinamento de modelos:

  * Random Forest
  * XGBoost
* Avaliação com MAE (escala real)

## 📊 Resultados

* Random Forest: ~17.000 MAE
* XGBoost: ~15.000 MAE

## 💡 Insight

As variáveis mais correlacionadas com o preço dos imóveis foram:

- OverallQual
- GrLivArea
- GarageCars

Isso indica que a qualidade geral da construção e a área habitável são os principais fatores que influenciam o preço.

Além disso, a transformação logarítmica do target ajudou a reduzir a assimetria dos dados, melhorando a performance dos modelos.

Isso pode ajudar corretores e investidores a entender melhor quais características impactam mais no valor de um imóvel.

## 🚀 Como executar

```bash
git clone https://github.com/seu-usuario/house-prices-prediction.git
pip install -r requirements.txt
jupyter notebook
```

## 📁 Estrutura

```
├── notebooks/
├── src/
├── data/
└── README.md
```

## 👩‍💻 Autora

Beatriz Morales Vilha Toledo
