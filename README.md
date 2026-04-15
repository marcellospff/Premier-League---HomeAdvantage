# 🏟️ Home Advantage na Premier League (2015–2025)

[![PT](https://img.shields.io/badge/PT-Português-009C3B?style=flat-square)](README.md) &nbsp;|&nbsp; [![EN](https://img.shields.io/badge/EN-English%20below-012169?style=flat-square)](#english-version)

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

---

<a name="english-version"></a>

# 🏟️ Home Advantage in the Premier League (2015–2025)

> Exploratory analysis of the home field advantage in the Premier League across 10 seasons (2015/16 – 2024/25), focusing on the COVID-19 pandemic as a natural experiment.

---

## 📌 Context and motivation

Playing at home gives an advantage in football — but **how real and measurable is that advantage?**

Between 2020 and 2021, the Premier League was played without fans due to the pandemic. This created a **unique natural experiment**: for the first time, it was possible to directly compare team performance *with* and *without* crowd pressure, using the same teams, in the same league.

This project uses that historical window to quantify home advantage and understand what really changes when stadiums go empty.

---

## 🔍 Questions answered

- Do Premier League teams win significantly more at home?
- Did home advantage decline during the fanless seasons?
- Which teams depend most on the home factor?
- Did home advantage show up in goals or only in results?
- Does player behaviour (fouls, cards, shots) differ at home vs away?

---

## 📊 Key findings

| Metric | Pre-pandemic | Pandemic | Post-pandemic |
|---|---|---|---|
| Home wins | 45.9% | 41.6% | 44.7% |
| Away wins | 30.3% | 35.4% | 32.1% |
| Average goal difference | +0.345 | +0.161 | +0.266 |

**Without fans, home advantage was cut in half.** The average goal difference per match dropped from +0.345 to +0.161 — and away wins reached their highest level in the entire period.

After the pandemic, the advantage partially recovered, but visiting teams continue to score more goals than before — suggesting a structural shift in away-game strategy.

---

## 🗂️ Project structure

```
Projeto_PL_HomeAdvantage/
│
├── home_advantage_pl.ipynb   # Main notebook with the full analysis
├── epl_final.csv             # Dataset with 9,380 matches (2000–2025)
└── README.md                 # This file
```

---

## 📈 Visualisations produced

- Results distribution by era (pre-pandemic, pandemic, post-pandemic)
- Season-by-season evolution of home advantage with pandemic period highlighted
- Home-field dependency ranking by team
- Area chart comparing average goals scored at home vs away
- Heatmap of behavioural metrics (fouls, cards, shots) by era

---

## 🛠️ Tech stack

- **Python 3.14**
- **Pandas** — data manipulation and aggregation
- **NumPy** — numerical calculations
- **Plotly** — interactive visualisations
- **Seaborn / Matplotlib** — static visualisations and global styling

---

## ▶️ How to run locally

```bash
# 1. Clone the repository
git clone https://github.com/marcellospff/Projeto_PL_HomeAdvantage.git
cd Projeto_PL_HomeAdvantage

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn plotly

# 3. Open the notebook
jupyter notebook home_advantage_pl.ipynb
```

---

## 📁 Dataset

**English Premier League Match Data 2000–2025**
Source: [Kaggle](https://www.kaggle.com/datasets/marcohuiii/english-premier-league-epl-match-data-2000-2025)

9,380 matches with complete statistics: goals, shots, corners, fouls and cards for each team in every game.

---

## 👤 Author

**Marcello Siqueira**
Business Data Science student — UFPB, Brazil

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marcello-spff/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/marcellospff)
