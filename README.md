# employee-career-analysis




## Overview

This repository contains an exploratory data analysis (EDA) of a synthetic survey dataset. The analysis explores respondent preferences and demographics, including country distribution, career influence factors, and preferred work setups.

## Dataset

The analysis uses `synthetic_survey_dataset_500.csv`, which includes the following fields:

* **Country**: Country of residence
* **Gender**: Gender of the respondent
* **Career Influence**: Factors influencing career choices
* **Prefer Remote**: Whether the respondent prefers remote work
* **Preferred Work Setup**: Ideal work environment for the respondent

## Analysis & Visualizations

The notebook performs the following analyses:

1. **Geographic Distribution of Respondents**
   Visualizes the distribution of survey respondents across different countries. Top countries include USA, France, India, Germany, UK, Japan, Australia, Brazil, Canada, and South Korea.

2. **Career Influence Factors**
   Visualizes factors that influence respondents' career decisions.

3. **Preferred Work Setup**
   Displays the overall distribution of preferred work setups.

4. **Teamwork Preference by Country**
   Analyzes teamwork preferences by country after filtering respondents who prefer to 'Work alone'. The `teamwork_by_country` table shows counts of respondents preferring teamwork per country.

5. **Gender-Specific Work Setup Analysis (Women)**
   Focuses on female respondents, showing a cross-tabulation of 'Country' and 'Preferred Work Setup'. The `women_team_preference_by_country` table provides insights into women's work setup preferences across countries.

## Libraries Used

* `pandas` for data manipulation
* `numpy` for numerical operations
* `plotly.express` & `plotly.graph_objects` for interactive visualizations

