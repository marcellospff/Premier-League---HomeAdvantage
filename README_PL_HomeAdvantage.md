# 🏟️ Home Advantage na Premier League (2015–2025)

[![Python](https://img.shields.io/badge/Python-3.14-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com/)

> Análise exploratória do fator campo na Premier League ao longo de 10 temporadas (2015/16 – 2024/25), com foco no impacto da pandemia de COVID-19 como experimento natural.

---

## 📌 Contexto e motivação

Jogar em casa dá vantagem no futebol — mas **o quanto essa vantagem é real e mensurável?**

Entre 2020 e 2021, a Premier League foi disputada sem torcida por causa da pandemia. Isso criou um **experimento natural único**: pela primeira vez foi possível comparar diretamente o desempenho dos times *com* e *sem* a pressão da torcida, nas mesmas equipes, na mesma liga.

Este projeto usa esse recorte histórico para quantificar o home advantage e entender o que realmente muda quando os estádios ficam vazios.

---

## 🔍 Perguntas respondidas

- Times da Premier League ganham significativamente mais em casa?
- O home advantage diminuiu durante as temporadas sem torcida?
- Quais times dependem mais do fator campo?
- A vantagem em casa se manifestou nos gols ou só nos resultados?
- O comportamento dos jogadores (faltas, cartões, chutes) muda em casa vs fora?

---

## 📊 Principais achados

| Métrica | Pré-pandemia | Pandemia | Pós-pandemia |
|---|---|---|---|
| Vitórias em casa | 45.9% | 41.6% | 44.7% |
| Vitórias fora | 30.3% | 35.4% | 32.1% |
| Saldo médio de gols | +0.345 | +0.161 | +0.266 |

**Sem torcida, o home advantage caiu pela metade.** O saldo médio de gols por partida despencou de +0.345 para +0.161 — e as vitórias fora de casa atingiram o maior nível histórico do período analisado.

Após a pandemia, a vantagem se recuperou parcialmente, mas os visitantes continuam marcando mais gols do que antes — sugerindo uma mudança estrutural no estilo de jogo fora de casa.

---

## 🗂️ Estrutura do projeto

```
Projeto_PL_HomeAdvantage/
│
├── home_advantage_pl.ipynb   # Notebook principal com toda a análise
├── epl_final.csv             # Dataset com 9.380 partidas (2000–2025)
└── README.md                 # Este arquivo
```

---

## 📈 Visualizações produzidas

- Distribuição de resultados por era (pré-pandemia, pandemia, pós-pandemia)
- Evolução do home advantage temporada a temporada com faixa pandêmica destacada
- Ranking de dependência do fator campo por time
- Gráfico de área comparando média de gols casa vs fora
- Heatmap de métricas comportamentais (faltas, cartões, chutes) por era

---

## 🛠️ Tecnologias utilizadas

- **Python 3.14**
- **Pandas** — manipulação e agregação dos dados
- **NumPy** — cálculos numéricos
- **Plotly** — visualizações interativas
- **Seaborn / Matplotlib** — visualizações estáticas e configurações globais

---

## ▶️ Como rodar localmente

```bash
# 1. Clone o repositório
git clone https://github.com/marcellospff/Projeto_PL_HomeAdvantage.git
cd Projeto_PL_HomeAdvantage

# 2. Instale as dependências
pip install pandas numpy matplotlib seaborn plotly

# 3. Abra o notebook
jupyter notebook home_advantage_pl.ipynb
```

---

## 📁 Dataset

**English Premier League Match Data 2000–2025**
Fonte: [Kaggle](https://www.kaggle.com/datasets/marcohuiii/english-premier-league-epl-match-data-2000-2025)

9.380 partidas com estatísticas completas: gols, chutes, escanteios, faltas e cartões para cada time em cada jogo.

---

## 👤 Autor

**Marcello Siqueira**
Estudante de Ciência de Dados para Negócios — UFPB

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marcello-spff/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/marcellospff)
