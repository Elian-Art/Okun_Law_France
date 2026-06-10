# Okun's law, France(2000-2026)

Empirical test of Okun's law on french macroeconomic data.
Analysis of the relationship between GDP growth and unemployment rate variations, using quarterly FRED data and linear regression

## Data sources 
- French GDP volume index (CLVMNACSCAB1GQFR), FRED
- French unemployment rate(LRHUTTTTFRQ156S), FRED

## Tools 
Python, pandas, numpy, matplotlib, scipy, google colab

## Key findings
- Okun coefficient (β): -0.271 ( excluding COVID)
- R²: 0.401
- p-value: 0.0

## Note on COVID-19
The 2020-2021 period was excluded from the main regression. 
Fench short-time work schemes decoupled unemployment from GDP during this period, illustating a structural limit of Okun's law under state intervention
