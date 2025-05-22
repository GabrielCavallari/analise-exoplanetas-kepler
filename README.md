# 🌌 Análise de Exoplanetas da Missão Kepler – NASA

Este projeto tem como objetivo aplicar técnicas de análise de dados sobre o conjunto de dados públicos da missão **Kepler** da **NASA**, que detectou exoplanetas utilizando o método de trânsito.

As técnicas utilizadas foram:

- 📊 **Inferência Estatística**
- 🔍 **Clusterização**
- 📈 **Regressão**
- 🧠 **Classificação**

A análise buscou responder perguntas como:

- Existem grupos distintos de exoplanetas com características comuns?
- Quais fatores mais influenciam o raio de um planeta?
- Podemos prever a classificação de um planeta (confirmado ou falso positivo)?

Os dados foram obtidos do [Kepler Exoplanet Archive – Kaggle](https://www.kaggle.com/datasets/nasa/kepler-exoplanet-search-results).

---

## ✅ Técnicas Aplicadas

- **Estatística Descritiva**: para explorar a distribuição das variáveis do conjunto de dados.
- **K-Means Clustering**: para agrupar exoplanetas com características semelhantes.
- **Regressão Linear Múltipla**: para prever o raio de um planeta com base em outras variáveis.
- **Árvore de Decisão (Decision Tree Classifier)**: para prever se um planeta é confirmado ou um falso positivo.

---

## 📌 Conclusão

O projeto proporcionou uma compreensão mais aprofundada dos exoplanetas detectados pela missão Kepler, revelando padrões interessantes através da análise estatística e da aplicação de modelos de Machine Learning. Com isso, foi possível:

- Identificar agrupamentos distintos de planetas;
- Determinar quais variáveis impactam mais o raio dos exoplanetas;
- Desenvolver modelos preditivos com boa performance para prever a classificação dos planetas.

A análise também serve como um estudo de caso didático, integrando estatística, aprendizado de máquina e visualização de dados para gerar conhecimento a partir de um problema real de astronomia.

---

## 🛠 Tecnologias Utilizadas

- Python 3.10+
- Google Colab
- Pandas, Matplotlib, Seaborn, Scikit-learn

---

## 👤 Autor

**Gabriel Lopes Cavallari**  
[https://github.com/GabrielCavallari](https://github.com/GabrielCavallari)

---

## 📁 Como executar

1. Baixe o notebook `analise_exoplanetas_kepler.ipynb`.
2. Baixe o conjunto de dados usado a partir do Kaggle:
   [Kepler Exoplanet Search Results](https://www.kaggle.com/datasets/nasa/kepler-exoplanet-search-results)
   - O arquivo utilizado foi `cumulative.csv`
3. Execute o notebook no Google Colab ou Jupyter Notebook.
   - Certifique-se de enviar o arquivo `.csv` ao ambiente antes de rodar as células.
     
---

## 📌 Licença

Este projeto está sob a licença MIT.
