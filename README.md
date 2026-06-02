# 🩺 Global Tuberculosis Burden Analysis · 2000–2024

Data cleaning, transformation and Excel reporting pipeline built in Python.

## Project Overview

Extracted and analyzed WHO Global TB data across 226 countries (2000–2024).  
Merged 3 raw CSV files, calculated statistics and year-over-year trends,  
and delivered a formatted multi-sheet Excel workbook with visualizations.

## Results

| Output | Link |
|--------|------|
| 📗 Excel Workbook | [Google Sheets](https://docs.google.com/spreadsheets/d/1cp5fRA8mbPuci_8Ntdpz5lBX9a3ZTbRo/edit?usp=sharing&ouid=107564873355874201227&rtpof=true&sd=true) |
| 📈 Charts | [View PNG](https://drive.google.com/file/d/1SkU2d9zXtV0eaSb0z09hBe8GbbN6XkQL/view?usp=sharing) |
| 📓 Notebook | [GitHub](https://github.com/AnfisaAnalytics/tb-global-analysis-python/blob/5e3524e1f6d9c6679b6584b78d75c82e3abd7fce/TB_Global_Analysis.ipynb) |

## Key Findings

- Global TB cases fell 6% from 2000 to 2019, then spiked 10.6M in 2021 (COVID-19 impact)
- India, Indonesia and Philippines account for ~43% of all global cases
- Africa CFR ~17% vs global average ~12% — reflects healthcare access gap
- WHO End TB 2030 target is severely off track

## Stack

| Tool | Purpose |
|------|---------|
| `pandas` | Data loading, cleaning, merging, transformation |
| `openpyxl` | Formatted Excel workbook export |
| `matplotlib` | Trend and bar chart visualizations |
| `seaborn` | Heatmap by continent |

## Data Sources

- **Our World in Data** — https://ourworldindata.org/tuberculosis  
- **WHO Global Tuberculosis Programme** — Burden Estimates  
- License: CC BY 4.0

## Project Structure
