# global-board-diversity-dataset

Board composition data for 8,000+ publicly listed companies across 12 countries, integrated with MSCI ESG ratings and Sustainalytics ESG Risk Scores.

## Scope
- 12 countries: China, South Korea, India, USA, UK, Japan, Spain, Taiwan, Australia, and others
- 8,000+ companies
- 5 data sources: corporate filings, financial APIs, MSCI ESG, Sustainalytics
- Metrics: total board members, female board members, female percentage, ESG ratings

## Files
- `ALL_BOARD_DATA_FIXED.csv` — board composition data
- `MSCI_ESG_BOARD_FINAL.csv` — integrated with MSCI ESG ratings
- `Sustainalytics_*.csv` — ESG risk scores by region
ESG integration performed using MSCI and Sustainalytics data (not included due to licensing).
## Methodology
Data collected via Python scripts and APIs. Cleaned, standardized, and merged from multiple sources with varying disclosure formats.

## Usage
Academic research on corporate governance patterns. Paper in preparation.

## Author
Daniil Terpugov — HSE University, St. Petersburg
