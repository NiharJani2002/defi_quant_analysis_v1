DeFi Quantitative Analysis Portfolio
Interactive web-based solutions to 6 quantitative finance case studies in decentralized finance (DeFi)
🎯 What This Code Does
This project demonstrates quantitative modeling capabilities through interactive HTML/JavaScript applications that solve real DeFi investment problems:

On-chain forensics - Graph theory to identify protocol reserve addresses
Yield derivative pricing - Expected value analysis for Pendle YT tokens
API integration - Hyperliquid leaderboard systematic trading workflow
Prediction market pricing - Log-normal ensemble model for token launch valuation
Token valuation - Multi-scenario comparative analysis (Monad vs MegaETH)
Risk assessment - Stablecoin fragility pattern detection

Each solution includes Python quantitative models, interactive Chart.js visualizations, and statistical frameworks inspired by Renaissance Technologies' methodology.
💡 What I Learned
Building this taught me to translate complex quantitative concepts into accessible interfaces. 

Key learnings:
-->Data visualization principles: Choosing appropriate chart types (scatter for correlation, doughnut for composition, line for time-series) to communicate statistical relationships clearly
-->Quantitative finance modeling: Implementing Kelly Criterion, Sharpe ratios, Monte Carlo simulations, and regime-weighted ensembles in JavaScript
-->Interactive UX for analysis: Creating sliders, toggles, and dynamic updates that let users explore parameter sensitivity without re-running Python models
-->Code organization: Structuring HTML artifacts with clear separation between data models, visualization logic, and UI interactions
-->Statistical rigor: Maintaining mathematical accuracy while simplifying presentation (e.g., beta sensitivity factors, correlation matrices, p-value thresholds)

The project bridges quantitative research and web development—making sophisticated financial models interactive and educational.
🚀 Quick Start
bash# No installation required - pure vanilla web
open index.html
```

## 📂 Project Structure
```
├── index.html          # Navigation hub
├── one.html           # Q1: CAP Protocol Reserves (Graph Theory)
├── two.html           # Q2: Pendle YT Pricing (Expected Value)
├── three.html         # Q3: Hyperliquid API (Systematic Trading)
├── four.html          # Q4: Monad Prediction Market (Log-Normal Model)
├── five.html          # Q5: Token Valuation (Multi-Scenario)
├── six.html           # Q6: Stablecoin Risk (Fragility Analysis)
└── README.md
🔬 Technical Highlights
Real-World Problem Solving

Live API integration: Hyperliquid leaderboard, Pendle markets
Production-ready Python: Complete implementations with error handling, rate limiting, connection pooling
Statistical rigor: p-value testing, correlation analysis, Monte Carlo simulations

Multiple Files & Substance

6 standalone applications: Each HTML file is a complete, deployable solution (1000-2000 lines)
Embedded Python models: Full quantitative code included in each page
Modular architecture: Separate data models, visualization logic, and UI components

Interactive Visualizations

Chart.js implementations: 10+ charts (scatter, line, radar, doughnut, bar)
Dynamic updates: Real-time recalculation based on user inputs (sliders, toggles)
Responsive design: Tailwind CSS, mobile-friendly

Framework Lightweight

Vanilla JavaScript: 
CDN dependencies only: Chart.js, Tailwind CSS (no npm, no build step)
Instantly deployable: Upload to any static host or open locally

🎓 Methodological Approach
Inspired by Renaissance Technologies' quantitative methodology:

Data > Narrative: Statistical evidence over market hype
Risk-adjusted returns: Sharpe ratios, Kelly Criterion, drawdown analysis
Systematic execution: Automated, emotion-free decision frameworks
Regime modeling: Multiple market scenarios with probability weights

📊 Example Visualizations
Each solution includes:

Correlation plots (Plotly) for reserve verification
Yield decay curves (Chart.js) for derivative pricing
Scatter plots for alpha vs luck separation
Distribution comparisons (normal vs fat-tail) for risk modeling
Radar charts for multi-factor competitive analysis

🔗 Original Case Study
Solutions address questions from: DeFi Analyst Case Study PDF
👤 Author
Nihar Mahesh Jani

📧 Personal: niharmaheshjani@gmail.com
🎓 University: njan0012@student.monash.edu
💼 LinkedIn: https://www.linkedin.com/in/nihar-mahesh-j-8824011b
💻 GitHub: https://github.com/NiharJani2002

⚠️ Disclaimer
Educational purposes only. Not financial advice. Models require rigorous backtesting before deployment.

"The only thing that matters is the statistical expectation." — Quantitative Trading Philosophy