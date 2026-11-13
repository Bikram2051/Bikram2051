# Bikram Bhattarai

Data engineer in Melbourne. Over two years writing the SQL behind recurring product reporting as a customer insights analyst, now finishing a Master of Data Science at Swinburne University of Technology. I work in SQL and Python, keep everything in Git, and check that the numbers reconcile before anyone builds on them.

I build data that still adds up six months later: agree the definition before building anything, fix the splits before anyone models, and keep the workings reproducible.

**[Portfolio](https://bikrambhattarai.com)** &nbsp;|&nbsp; [Articles](https://bikrambhattarai.com/articles/) &nbsp;|&nbsp; [LinkedIn](https://www.linkedin.com/in/bikram2051/) &nbsp;|&nbsp; [Tableau Public](https://public.tableau.com/app/profile/bikram.bhattarai/vizzes) &nbsp;|&nbsp; [Resume (PDF)](https://bikrambhattarai.com/assets/Bikram-Bhattarai-Resume.pdf) &nbsp;|&nbsp; [Email](mailto:vikrambhattarai1994@gmail.com)

Open to graduate and junior data engineering roles in Melbourne, and to data analyst roles. Australian permanent resident with full working rights.

## Latest: vehicle weight and driver injury in two-car crashes

<a href="https://bikrambhattarai.com/projects/crash-weight/">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/crash-weight-dark.svg">
    <img src="assets/crash-weight-light.svg" alt="Chart: in two-car crashes where one driver was killed or seriously injured, the share where it was the lighter car's driver rises from 52% when the cars are within 100 kg to 86% when the gap is over 800 kg." width="800">
  </picture>
</a>

A matched-pair study of 57,217 crashes in Victoria, done in R with a teammate for a big data unit at Swinburne. We compared the two drivers inside each crash with conditional logistic regression, so the road, the weather and the speed limit cancel out.

After adjusting for driver age and sex, vehicle age, seatbelt use and point of impact, each 10% of extra weight went with about 20% lower odds of that car's driver being killed or seriously injured (odds ratio 0.796, 95% CI 0.784 to 0.808). The planned straight-line model did not hold up when tested, so the final model works on the ratio of the two weights.

My part was the data build, the models and the figures. **[Read the case study](https://bikrambhattarai.com/projects/crash-weight/)**

`R` `survival` `dplyr` `ggplot2`

## Other work

| Project | What it is | Built with |
|:--|:--|:--|
| [Domain adaptive sentiment analysis](https://github.com/TDP-2026-Repository/TECHNOLOGY-DESIGN-PROJECT) | As the team's data engineer I built one preprocessing pipeline and fixed train, validation and test splits across GoEmotions and the Financial PhraseBank, so no modelling notebook could leak data into its own evaluation. | Python, pandas, Hugging Face |
| [OSHC When It Matters](https://github.com/Bikram2051/oshc-when-it-matters) | A learning prototype that helps international students understand their Overseas Student Health Cover. Every chat answer passes an input review, a grounded draft and an output audit. I wrote the bill explainer's extraction, the benefit arithmetic (tests first), the question classifier and the evaluation code. Industry partner: Medibank. | Python, Streamlit, pytest |
| [Australian beach and water locations](https://github.com/Bikram2051/Bikram2051-COS60008-Assignment) | Open data on beach amenities and regional climate, cleaned and analysed in a notebook that can be rerun end to end. | Python, pandas, Jupyter |
| [EchoSphere](https://github.com/Bikram2051/university-web-app-php-java) | A full-stack PHP and MySQL store with server-side validation and an order dashboard. | PHP, MySQL |

Dashboards are on [Tableau Public](https://public.tableau.com/app/profile/bikram.bhattarai/vizzes). The [portfolio](https://bikrambhattarai.com/projects/) has the full write-ups.

## Toolkit

| | |
|:--|:--|
| Querying | SQL (MS SQL Server, PostgreSQL, MySQL), CTEs, window functions, data modelling for reporting |
| Data preparation | Cleaning, standardising and combining sources in Python, split design, validation and reconciliation |
| Programming | Python (pandas, NumPy, scikit-learn), R |
| Engineering | Git and GitHub, GitHub Actions, Docker, pytest, Django REST, Streamlit |
| Statistics | Regression, A/B testing, cohort and retention analysis, survey weighting |
| Reporting | Tableau, Power BI, Looker Studio, Excel |
