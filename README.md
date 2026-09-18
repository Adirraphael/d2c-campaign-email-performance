# D2C Email Campaign Performance

A Streamlit dashboard comparing D2C email performance (Packs, OLM, Homeboost) between 2025 and 2026 — built to answer one question: **does sending more emails actually help, or does it just drive more unsubscribes?**

## What's in it

- **Email Performance tab** — sends, opens, and unsubscribe rates side by side for 2025 vs 2026, plus a few charts breaking down whether bigger sends actually perform better (spoiler: not really)
- **Unsubscribe Reasons tab** — why people unsubscribed from the two biggest campaigns of the year, with the actual reasons broken out

## Running it locally

```bash
pip install -r requirements.txt
streamlit run d2c_email_campaign_report.py
```

Needs `d2c-campaigns.csv` in the same folder (the campaign performance export). That file isn't in this repo since it's actual customer data.

