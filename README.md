# Support Data Trends Dashboard

This project analyzes customer support messages and auto-tags them using a keyword-based classifier built in Python. It’s designed to explore support trends, reduce manual tagging, and lay the groundwork for future AI-powered categorization.

---

## Project Goals

- Load and clean customer support message data (from CSV)
- Tag messages into categories like Billing, Login Issue, Technical, etc.
- Save the categorized data for dashboards and trend analysis
- Explore use of OpenAI API for AI-based auto-tagging

---

## What’s Included

| File | Description |
|------|-------------|
| `sample.csv` | Original raw support messages |
| `keyword_tagged.csv` | Cleaned and categorized messages using Python |
| `auto_tagging_keyword_model.ipynb` | Colab notebook for data loading, tagging, and export |
| `README.md` | This file (project summary + instructions) |

---

## How It Works

1. **Load CSV** of support tweets or tickets into a Pandas DataFrame  
2. Use a simple Python function to **tag messages** using keywords  
3. *(Optional)* Use `getpass()` to securely insert an OpenAI API key  
4. Tag messages using **GPT-3.5** with contextual classification  
5. Save the final results to a new CSV for analysis or visualization

---

## Tools Used

- Google Colab (for notebook)
- Python (`pandas`)
- `getpass` for securely handling API keys
- *(Optional)* OpenAI API for AI-driven tagging

---

## Possible Next Steps

- Create bar charts or pie charts of ticket categories
- Group by date to find trends (e.g., busiest support days)
- Visualize tagged results in Excel or Google Sheets
- Build a lightweight dashboard using Streamlit or Dash
- Use this logic to auto-tag Zendesk tickets (via API)

---

## Security Note

This project uses `getpass.getpass()` to handle API keys safely during runtime. Keys are never hardcoded or committed to GitHub.

---

## About the Creator

Created by TJ Pearce 
Portfolio: https://github.com/tpearce90
Email: tpearce111590@gmail.com

