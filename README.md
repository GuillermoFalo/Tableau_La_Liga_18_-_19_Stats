# ⚽ La Liga 2018–2019 Analytics Dashboard  
### A Tactical and Statistical Breakdown of Spain's Top Football League

This project analyzes the **La Liga 2018–2019 season** from both a **team and player perspective**, going beyond surface-level stats to critically assess performance trends, playing styles, and tactical tradeoffs.

> Based on data from 556 players, the dashboards expose tactical truths, debunk common assumptions, and provide data-driven clarity into what truly happened on the pitch.

---

## 📁 Overview of Dashboards

### 🟢 Dashboard 1 — General KPIs Across the League

This dashboard aggregates core performance metrics for all players and teams:

- **Games Played / Started**
- **Minutes Played**
- **Goals, Shots, Assists**
- **Dribbles, Duels, Cards, Fouls**

**Objective:** Understand how performance is distributed league-wide and identify outliers.  
Key insight: Players with high minutes don’t always contribute efficiently. Several mid-table teams displayed worse disciplinary records than relegation sides.

> ⚠️ _Data reality often contradicts reputation. “Dirty” isn’t exclusive to the bottom of the table._

---

### 🔵 Dashboard 2 — Style of Play: Long Balls vs Short Passes

This dashboard explores tactical identity and its consequences. It features:

- 📦 **Boxplots**: Team-level distributions of short vs long passes  
- 📈 **Scatter 1**: Long Passes vs Aerial Duel Success  
- 📉 **Scatter 2**: Long Passes vs Fouls Committed  

**Key findings:**

- Teams that favor long balls tend to win more aerial duels — logical and expected.
- However, a **positive linear correlation** was found between long passes and **fouls committed**.

> 🧠 _Long-ball systems are not just about territory — they encourage physical play, which translates into more fouls. The “dirty team” label is supported by data, not just narrative._

Team finish segments (Champions League, Europa, Mid Table, Relegation) help visualize how style correlates with success — and when it doesn’t.

---

### 🔴 Dashboard 3 — The Matchup Machine: Head-to-Head Player Comparison

A dynamic tool to compare **any two La Liga players** side-by-side. Key metrics include:

- **Appearances, Minutes Played**
- **Goals, Assists, Shots**
- **Dribbles, Duels Won**
- **Fouls, Yellow and Red Cards**

Players are visualized with custom bar charts and labeled with taglines like _“Solid Attacking Contribution”_ or _“Tough Tackler”_ to quickly frame performance.

> 🤔 _This tool exposes performance gaps hidden behind big reputations or inflated minutes._

Example: Comparing **Vidal vs Modrić** shows the former’s physical dominance and duel success, versus the latter’s playtime efficiency and discipline.

---

## 🔍 Methodology

| Phase               | Tools Used                      |
|---------------------|---------------------------------|
| Data Cleaning       | Excel          |
| Aggregation         | Player-to-team roll-ups         |
| Visualization       | Tableau                         |
| Analysis Focus      | Style impact, performance bias  |

---

## 📌 Key Takeaways

- **Playing style has real tactical consequences.** Long-ball teams are not only more aerially dominant — they’re also more foul-prone.
- **Minutes ≠ value.** Many players racked up high minutes but provided low impact. This analysis filters volume from efficiency.
- **Success is pragmatic.** Even top-tier teams use long balls and commit fouls — clean football doesn’t always win leagues.

---

## 📂 Data Source

> _Official La Liga Stats (2018–2019), transformed and analyzed for visual reporting._

---

## 👤 About the Author

**Guillermo Falo**  
*Account Manager | Business Analytics Candidate | Former Academy-Level Footballer*

> My background in football, data, and business gives me a unique lens: I don’t just find trends — I translate them into tactical reality.

