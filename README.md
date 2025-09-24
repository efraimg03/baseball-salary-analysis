# Baseball Player Salary Analysis (R Project)

This project explores the factors that influence the salaries of professional baseball players in the USA, using a dataset of 206 players from the 1986–1987 seasons.  
It was completed as part of a university data analysis course and demonstrates skills in data wrangling, statistical testing, regression modeling, and R programming.


# Contents
 `εργασια_Εφραιμ_Γιαννικος.pdf` → Full written report (in Greek) with results and visualizations.  


# Tools & Methods
**Software:** R (RStudio)  
**Libraries:** `foreign`, `psych`, `moments`, `sjPlot`, `car`  
**Techniques applied:**  
  - Descriptive statistics (mean, median, variance, skewness, kurtosis)  
  - Data visualization (histograms, boxplots, correlation plots)  
  - Non-parametric tests (Shapiro-Wilk, Agostino, Wilcoxon)  
  - Correlation analysis (Spearman’s rho)  
  - Multiple linear regression with log-transformed variables  
  - (VIF) and residual diagnostics  

# Key Insights
- Experience matters: Career-wide statistics (total wins, winnings, games played) are strongly correlated with salary.  
- Recent performance is less important: Wins in 1986 (WINS86) had no significant effect on salary once overall career stats were considered.  
- Negative effects: More losses in 1986 reduced salaries, as expected.  
- Positive effects: Saves (relief pitching role) had a small but positive effect.  
- Final model: Explained **76.8% (Adjusted R² = 0.768)** of salary variability.  

 
