# Super Rugby Referee Nationality Analysis (2023–2025)

This Jupyter Notebook investigates whether **referee nationality** can be used to predict **match outcomes** in Super Rugby Pacific across the 2023, 2024, and 2025 seasons.

**Main questions:**  
*Can referee nationality help predict match outcomes in Super Rugby?*
and
*How did Australian sides do in Super Rugby 2025?*

### What’s inside
The analysis covers:
- Data scraping and preprocessing from Wikipedia
- Feature engineering (e.g. referee/team nationality alignment, home advantage)
- Logistic regression models (with and without team strength controls)
- Year-by-year comparisons
- Model diagnostics (VIF)
- Bootstrapping to validate findings
- Visualizations to make trends pop

### Key finding (spoiler alert!)
There’s a **noticeable statistical trend in 2025** suggesting teams may have fared better when referees were from the same country. While this doesn’t confirm bias or causation, it’s an interesting pattern worth exploring.

### Notes
- This is an independent, exploratory project for learning and curiosity.
- I’m not a professional statistician — this hasn’t been peer-reviewed or professionally audited.
- All data is public and sourced from Wikipedia match listings.
