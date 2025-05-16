<h1 align="center">💸 Loan Interest Rate Prediction</h1>
<h3 align="center">📈 Regression modeling of Lending Club loan data using economic and statistical analysis</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Domain-Econometrics-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Data-LendingClub-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Model-OLS%20%2B%20Robust%20Regression-yellow?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-MIT-lightgrey?style=for-the-badge" />
</p>

<hr>

<h2>📌 Project Overview</h2>

<p>
This project analyzes the relationship between <strong>debt-to-income ratio (DTI)</strong> and <strong>loan interest rate</strong> using real-world Lending Club data. It applies econometric techniques and statistical diagnostics to build a robust predictive model for financial risk evaluation.
</p>

---

<h2>🎯 Objectives</h2>

<ul>
  <li>Analyze how borrower characteristics influence interest rates</li>
  <li>Understand the impact of <strong>loan purpose, DTI, FICO score, and installment amounts</strong></li>
  <li>Develop and refine a <strong>linear regression model</strong> with appropriate assumptions</li>
  <li>Apply robust standard errors to account for heteroskedasticity and outliers</li>
</ul>

---

<h2>🔍 Dataset</h2>

<ul>
  <li>📁 <code>loan_data.csv</code> from Lending Club</li>
  <li>💵 Variables include: annual income, DTI, loan purpose, term, FICO score, interest rate</li>
  <li>🧹 Cleaned to remove missing/invalid entries, transformed with dummies and log variables</li>
</ul>

---

<h2>📊 Methodology</h2>

<ol>
  <li><strong>Exploratory Data Analysis (EDA)</strong>: Relationship plots, skewness check, correlation matrix</li>
  <li><strong>Initial OLS Regression</strong>: Baseline model with DTI and loan amount</li>
  <li><strong>Model Refinement</strong>:
    <ul>
      <li>Multicollinearity check (VIF)</li>
      <li>Heteroskedasticity tests (Breusch–Pagan)</li>
      <li>Influential points analysis (Cook's distance)</li>
      <li>Robust standard errors (HC1)</li>
    </ul>
  </li>
  <li><strong>Final Model</strong>: Multiple regression with transformed variables and fixed effects</li>
</ol>

---

<h2>📈 Model Performance</h2>

<ul>
  <li>Final Adjusted R²: <strong>0.758</strong> — strong model fit</li>
  <li><strong>Significant Predictors</strong>:
    <ul>
      <li>📊 Debt-to-Income (DTI)</li>
      <li>💳 FICO Score</li>
      <li>📦 Installment Amount</li>
      <li>🏢 Loan Purpose: Small Business, Debt Consolidation</li>
    </ul>
  </li>
</ul>

---

<h2>📸 Sample Visualization</h2>

<p align="center">
  <img src="assets/dti_vs_interest.png" width="80%" alt="DTI vs Interest Rate" />
</p>

---

<h2>🧰 Tools & Libraries</h2>

<ul>
  <li>🧮 Python (Pandas, Statsmodels, Matplotlib, Seaborn)</li>
  <li>📈 Econometric Modeling (OLS, HC errors, diagnostics)</li>
  <li>📊 Statistical Inference (t-tests, p-values, adjusted R²)</li>
</ul>

---

<h2>📁 Folder Structure</h2>

<pre>
loan-interest-rate-prediction/
├── Econ_Project_Group4.ipynb      # Full modeling notebook
├── loan_data.csv                  # Dataset
├── Presentation2.pptx             # Project slides
├── Report 1.docx, Report 2.docx   # Summary and proposal (optional)
├── requirements.txt               # Python dependencies
├── LICENSE                        # MIT License
├── README.md
└── assets/
    └── dti_vs_interest.png
</pre>

---

<h2>🙋‍♂️ Author</h2>

<p>
<strong>Prathamesh Nagraj</strong><br>
📧 <a href="mailto:ppnagraj.work@gmail.com">ppnagraj.work@gmail.com</a><br>
🔗 <a href="https://www.linkedin.com/in/prathamesh-nagraj/">LinkedIn Profile</a>
</p>

---

<h2>📄 License</h2>

<p>This project is licensed under the <strong>MIT License</strong>.</p>

---

<p align="center"><em>“From credit scores to interest rates — quantifying loan risk with data.”</em></p>
