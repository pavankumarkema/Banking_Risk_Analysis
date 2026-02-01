# Banking Risk Analysis

End-to-end credit-risk analysis: data cleaning & EDA → feature engineering → baseline & tree-based classification → evaluation and stakeholder recommendations.

Tech
- Power BI

Quick summary
- Goal: Build an interpretable credit-risk model and evaluate business trade-offs between approval rate and expected loss.  
- Key outputs: model evaluation (ROC-AUC, confusion matrix), feature importance, and threshold scenarios with business metrics.

Power BI dashboard (interactive)
- File (local): `reports/banking_risk_dashboard.pbix` — open with Power BI Desktop. 

How to view the Power BI dashboard locally
1. Install Power BI Desktop (free) — https://powerbi.microsoft.com/  
2. Open `reports/banking_risk_dashboard.pbix` in Power BI Desktop.  
3. If the PBIX expects external CSV/DB sources: either place `data/banking_sample.csv` in the expected path or update the data source in Power Query → Transform Data → Data source settings → Change Source.  
4. Refresh visuals and explore the Report pages.

🛡️Banking Risk Analysis: Project Description
This Power BI dashboard provides a critical analysis of a bank's performance and risk exposure across its core business lines: Loans and Deposits. Designed for bank management and advisors, the project showcases the financial overview and detailed segment-level risk indicators.<img width="1455" height="815" alt="Screenshot 2025-10-28 195005" src="https://github.com/user-attachments/assets/3042b1ac-4e35-4a47-af9b-8c0a104de9ba" />
Key Dashboard Functions:
The **Loan Analysis section** focuses on credit risk, breaking down loan portfolios by Occupation, Banking Relationship, and Income Band. It reveals that $\mathbf{\$2.60bn}$ is allocated to Business Lending and highlights the concentration of bank loans, with the Low Income Band accounting for $\mathbf{53.12\%}$.<img width="1465" height="820" alt="Screenshot 2025-10-28 195105" src="https://github.com/user-attachments/assets/3bb29245-2681-4c65-a3e6-a16d5abf8931" />
The **Deposit Analysis section** assesses funding stability by segmenting deposits by client Income Band and Nationality. The analysis shows a rising trend in bank deposits, with the Med Income Band contributing the largest share ($\mathbf{\$1.09bn}$).<img width="1454" height="813" alt="Screenshot 2025-10-28 200312" src="https://github.com/user-attachments/assets/5cc1b0cf-611a-4cf5-8043-de2e61136bb2" />
The **Summary view** establishes the bank's scale, reporting $\mathbf{3000}$ Total Clients, $\mathbf{\$4.38bn}$ in Total Loans, and $\mathbf{\$2.01bn}$ in Total Deposits.<img width="1451" height="815" alt="Screenshot 2025-10-28 200409" src="https://github.com/user-attachments/assets/f595c622-062e-4110-a8ff-fa423267c778" />
