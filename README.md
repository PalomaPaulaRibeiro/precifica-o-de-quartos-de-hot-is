# 🏨 Análise de Preços de Hotéis com Regressão Linear

Este projeto tem como objetivo prever o preço de diárias de hotéis com base em três variáveis principais:

- ⭐ Número de estrelas
- 📍 Proximidade de pontos turísticos
- 🛏️ Capacidade do quarto

Foram desenvolvidos e comparados **três modelos de regressão linear** com diferentes combinações de variáveis preditoras.

---

## 🔍 Etapas do Projeto

✅ **Análise Exploratória de Dados (EDA)**  
- Visualização com `pairplot` para investigar relações entre variáveis.

✅ **Construção e Avaliação de Modelos**  
- Três modelos de regressão linear:
  - Modelo 1: `Estrelas`
  - Modelo 2: `Estrelas + ProximidadeTurismo`
  - Modelo 3: `Estrelas + ProximidadeTurismo + Capacidade`

✅ **Comparação entre modelos**  
- Avaliação com métricas **R²** e **RMSE**.

✅ **Modelo final com interpretação**  
- Visualização dos resíduos
- Gráfico de importância das variáveis
- Equação da regressão linear gerada

---

## 📊 Resultados

| Modelo                               | R²     | RMSE     |
|-------------------------------------|--------|----------|
| Estrelas                            | 0.12   | 162      |
| Estrelas + ProximidadeTurismo      | 0.65   | 102      |
| Estrelas + Proximidade + Capacidade| 0.92 ✅ | 47.5 ✅   |

---

## ✅ Conclusões

- O modelo com todas as variáveis apresentou excelente desempenho (**R² = 0.92**).
- Hotéis com mais estrelas e mais próximos de atrações turísticas tendem a ter preços mais altos.
- A variável **Capacidade** também tem influência, mas menos expressiva.
- O modelo final pode ser utilizado para prever preços de novos hotéis com boa precisão.

---

## 🧠 Tecnologias Utilizadas

- Python
- Pandas, Seaborn e Matplotlib
- Scikit-learn (Regressão Linear)
- Google Colab

---

## 🚀 Como Executar

1. Faça upload do arquivo `hoteis.csv` no Google Colab.
2. Execute o notebook `analise_precos_hoteis.ipynb`.
3. Siga as instruções para visualizar os gráficos e resultados.

---

## 📎 Autor

**Paloma Paula Ribeiro**  
Cientista de Dados em formação 💻  
[🔗 LinkedIn](https://www.linkedin.com/in/seu-usuario-aqui)

