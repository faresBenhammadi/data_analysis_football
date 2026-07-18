# ⚽ Football Matches 2024/2025 Data Analysis

A data analysis project exploring the **2024/2025 football season** across the **Top 5 European leagues and the UEFA Champions League** using **Python, Pandas, NumPy, and Matplotlib**.

The goal of this project is to answer common football questions through data visualization and statistical analysis.

---

## 📊 Dataset

Dataset:
- **Football Matches 2024/2025 - Top 5 Leagues**
- Source: Kaggle

The dataset contains information such as:

- Home and away teams
- Final and halftime scores
- Match outcome
- Competition
- Matchday
- Goal difference
- Total goals

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- KaggleHub
- Jupyter Notebook

---

## 📈 Project Analyses

### 🏠 Home Advantage

- Computes the probability of a home victory.
- Visualizes the distribution of:
  - Home wins
  - Away wins
  - Draws

**Question answered**

> Does playing at home provide a significant advantage?

---

### ⚽ Goal Distribution

The project compares goals scored in:

- First Half
- Second Half

It also calculates:

- Average goals per match
- Percentage of goals scored in each half

Visualizations include:

- Pie chart
- Goal histogram

**Question answered**

> Are more goals scored before or after halftime?

---

### 🏆 League Comparison

Compares every competition by:

- Average goals per game
- Average goal difference

This allows identifying which leagues are generally more offensive.

---

### 🥇 Winning Teams Analysis

Creates a new feature identifying the winner of every match.

Then determines:

- Teams with the most victories
- Top winning clubs

---

### 📅 Matchday Analysis

Studies how the average number of goals changes throughout the season.

**Question answered**

> Do matches become more defensive as the season progresses?

---

### 🎯 Best Scoring Teams

Calculates total goals scored by every club by combining:

- Home goals
- Away goals

Ranks the highest-scoring teams.

---

### 📉 Goals vs Wins Correlation

Combines:

- Number of victories
- Total goals scored

Then computes the **Pearson correlation coefficient** and visualizes the relationship using a scatter plot.

This analysis investigates whether scoring more goals strongly correlates with winning more matches.

---

## 📊 Example Visualizations

The notebook includes visualizations such as:

- Bar charts
- Scatter plots
- Histograms
- Pie charts
- Line plots

---

## 📂 Project Structure

```
Football-Analysis/
│
├── football_analysis.ipynb
├── README.md
└── images/              # (optional screenshots of plots)
```

---

## 🚀 How to Run

Clone the repository:

```bash
git clone https://github.com/yourusername/Football-Analysis.git
cd Football-Analysis
```

Install the required packages:

```bash
pip install pandas numpy matplotlib kagglehub
```

Run the notebook:

```bash
jupyter notebook
```

---

## 📌 Key Findings

- Home teams win significantly more often than away teams.
- A larger proportion of goals are scored during the second half.
- Some competitions produce considerably more goals than others.
- Teams that score the most goals are generally the teams that win the most matches.
- There is a strong positive correlation between goals scored and total victories.

---

## 📚 Skills Demonstrated

- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis (EDA)
- GroupBy Operations
- Statistical Analysis
- Correlation Analysis
- Data Visualization
- Python Programming

---

## 📄 License

This project is intended for educational and portfolio purposes. 
