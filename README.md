# Banking Risk Analysis

End-to-end credit-risk analysis: data cleaning & EDA → feature engineering → baseline & tree-based classification → evaluation and stakeholder recommendations.

Tech
- Power BI

Quick summary
- Goal: Build an interpretable credit-risk model and evaluate business trade-offs between approval rate and expected loss.  
- Key outputs: model evaluation (ROC-AUC, confusion matrix), feature importance, and threshold scenarios with business metrics.

Power BI dashboard (interactive)
- File (local): `reports/banking_risk_dashboard.pbix` — open with Power BI Desktop.  
- Screenshot preview (embed the image file you add):  
  ![Banking risk dashboard overview](reports/assets/banking_risk_dashboard_overview.png)  

- Published report (optional): paste your Power BI publish link here:
  - Published link: <PASTE_PUBLISH_LINK_HERE>

How to view the Power BI dashboard locally
1. Install Power BI Desktop (free) — https://powerbi.microsoft.com/  
2. Open `reports/banking_risk_dashboard.pbix` in Power BI Desktop.  
3. If the PBIX expects external CSV/DB sources: either place `data/banking_sample.csv` in the expected path or update the data source in Power Query → Transform Data → Data source settings → Change Source.  
4. Refresh visuals and explore the Report pages.

If you don't want to include the `.pbix`:
- Export the report to PDF (File → Export → PDF) or export page screenshots and add them to `reports/assets/`. Embed the PNGs in this README (example above).

Viewing notes / privacy
- If you publish using Power BI Service → Publish to web, the report becomes public. Do not publish sensitive or PII-containing data. Alternatively, include a PDF or PNG snapshots for public repos.

Suggested quick additions for this repo (high impact)
- `reports/banking_risk_dashboard.pbix` (or PDF + screenshots in `reports/assets/`)  
- `data/banking_sample.csv` (small sanitized sample) or a README section describing the schema  
- `requirements.txt` and a short run instruction: `pip install -r requirements.txt` and `jupyter nbconvert --execute notebooks/analysis.ipynb`  
- `reports/executive_summary.md` — 1-page summary with top 3 takeaways and recommended next steps

Replace placeholders:
- Replace `reports/assets/banking_risk_dashboard_overview.png` with your actual screenshot path.  
- Paste your published link at `<PASTE_PUBLISH_LINK_HERE>` to enable a direct view from the README.
