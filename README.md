# 🏏 Data-Driven Cricket Team Selection

This project challenges the traditional, often subjective, methods of cricket team selection. It introduces a systematic, data-driven framework to identify the optimal 12-player squad by objectively analyzing historical player performance.

By processing and analyzing comprehensive data from **T20, ODI, and IPL formats**, this analysis provides a quantifiable, performance-based model to build a well-balanced and statistically superior team.

### 🎯 The Problem: Bias in Selection

Traditional team selection often relies on subjective judgment, recent form (which can be misleading), or "gut feeling," leading to inconsistent and biased squad composition. This project provides an objective, performance-driven alternative to address these inconsistencies.

### ✨ Key Features

* **Objective Player Evaluation:** Replaces subjective opinion with hard metrics (Strike Rate, Economy, Average, etc.).
* **Role-Specific KPIs:** Defines unique Key Performance Indicators (KPIs) for different player roles (Opener, Finisher, Specialist Bowler, All-Rounder).
* **Automated Data Pipeline:** Includes Python scripts (`BeautifulSoup`, `Requests`) to scrape and preprocess data from ESPN Cricinfo.
* **Statistically-Backed Squad:** The final 12-player squad is selected based *only* on players who meet predefined, stringent statistical criteria.

---

### 🛠️ Technical Workflow & Methodology

The project follows a systematic data analysis workflow:

1.  **Data Collection:** Player and match statistics were scraped from **ESPN Cricinfo** using Python's `BeautifulSoup` and `Requests` libraries.
2.  **Data Preprocessing:** The raw scraped data was extensively cleaned. This involved handling missing values (`NaN`), removing duplicate entries, and standardizing metrics (e.g., strike rates, economy rates) for consistent analysis.
3.  **Feature Selection:** Key Performance Indicators (KPIs) were selected to evaluate players based on their specific roles:
    * **Batting Metrics:** Strike Rate, Batting Average, Boundary Percentage.
    * **Bowling Metrics:** Economy Rate, Bowling Strike Rate, Dot Ball Percentage.
    * **All-Rounder Metrics:** A balance of both batting and bowling KPIs.
4.  **Analysis & Team Selection:** The cleaned data was analyzed using descriptive statistics. Strict, role-based filters were applied to rank players and build a final, balanced squad.

---

### 📊 Key Insights

The analysis successfully identified top-tier players who consistently meet the objective performance criteria.

* **Top Performers Identified:** The model successfully shortlisted elite players who consistently met the objective criteria:
    * **David Warner:** 1256 runs at an average T20 Strike Rate of 124.00.
    * **Jos Buttler:** A high-impact T20 Batting Average of 50.76.
    * **Suryakumar Yadav:** An exceptional T20 Strike Rate of 158.56.
    * **Jasprit Bumrah:** A world-class T20 Economy of 6.81 with a high 46.90% Dot Ball Percentage.

* **Metric Validation:** The analysis confirmed the critical importance of a **high strike rate** for T20 batting success and a **low economy rate** as a primary indicator of a bowler's ability to control a game.

---

### 🏆 The Optimal 12-Player Squad

Based on the predefined role-based criteria, the following squad was selected as the optimal, data-driven team:

* **Batters:**
    * Virat Kohli (C)
    * David Warner
    * Suryakumar Yadav
    * Travis Head
* **Wicketkeepers:**
    * Jos Buttler
    * Heinrich Klaasen
* **All-Rounders:**
    * Glenn Maxwell
    * Marcus Stoinis
    * Glenn Phillips
* **Specialist Bowlers:**
    * Jasprit Bumrah
    * Arshdeep Singh
    * Taskin Ahmed

---

### 🔮 Future Scope

This project serves as a strong foundation for more advanced sports analytics. Future improvements could include:

* **Real-Time Data Integration:** Incorporating live match data to provide dynamic, in-tournament selection recommendations.
* **Predictive Modeling:** Utilizing Machine Learning (e.g., regression, clustering) to predict player performance and optimize team composition for specific opponents or conditions.
* **Expanded Datasets:** Expanding the analysis to include other major domestic leagues like the Big Bash League (BBL) and Caribbean Premier League (CPL).
* **Interactive Visualizations:** Creating interactive dashboards (e.g., using Tableau or Power BI) for easier exploration of player stats and team insights.
