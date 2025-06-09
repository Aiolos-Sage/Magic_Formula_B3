# Magic Formula B3

A Streamlit dashboard for screening Brazilian stocks using Joel Greenblatt's **Magic Formula** and an additional dual-ranking methodology.

## 🚀 Features

- Fetches financial data from Financial Modeling Prep API
- Applies Magic Formula investing logic to B3 tickers
- Displays interactive ranking and visualizations

## 🧪 Tech Stack

- Python
- Streamlit
- Pandas, Requests, Matplotlib

## 🔧 Setup

1. **Install dependencies**:
   ```
   pip install -r requirements.txt
   ```

2. **Add your API key** in `.streamlit/secrets.toml`:
   ```toml
   API_KEY = "your_api_key_here"
   ```

3. **Run locally**:
   ```
   streamlit run Magic_Formula_B3.py
   ```

## 🌐 Deploy

To deploy on [Streamlit Cloud](https://streamlit.io/cloud):

- Push this repo to GitHub
- Deploy using:
  - Repository: `Aiolos-Sage/Magic_Formula_B3`
  - Branch: `main`
  - File path: `Magic_Formula_B3.py`
