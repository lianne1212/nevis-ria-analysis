# Nevis Data Analysis Hometask (Deployment): RIA market analysis

Lianne Naimer

Analysis of 5 years of SEC Form ADV data for SEC-registered investment advisers (RIAs): market segments by AUM, fastest-growing firms, capacity-strained firms, under-staffed firms, and a prospect shortlist and timing list for Nevis.

## Files
- `Nevis_RIA_Market_Analysis.ipynb`: the notebook (code, outputs, summary, assumptions)
- `Nevis_RIA_Market_Analysis.html`: the same notebook as a readable web page
- `ria_firm_table.csv`: the cleaned firm-level table, one row per firm per yearly snapshot (Nov 2021 to Nov 2026)
- `nevis_prospect_shortlist.csv`: top 25 wealth managers by prospect score
- `nevis_timing_list.csv`: wealth managers that grew their advisor team 30%+ in the last year

## How to run
Open the notebook in Jupyter or Google Colab and run all cells. It downloads the monthly files from the [SEC page](https://www.sec.gov/data-research/sec-markets-data/information-about-registered-investment-advisers-exempt-reporting-advisers) into `./data` (set `USER_AGENT` to your name and email first; the SEC requires it). Requires pandas, numpy, matplotlib, requests, beautifulsoup4 and openpyxl.
