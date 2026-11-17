# FlyersSoft AI Sales Assistant

## Features
- Two sales modes: Resource / Engineering Partnership and Industry-Specific Solution Selling
- Personalised call scripts, objection handling and discovery questions
- Optional public company website reading (homepage plus up to three same-domain pages)
- Session history, JSON export and individual TXT downloads

## Run locally
1. Install Python 3.10+.
2. Run `pip install -r requirements.txt`.
3. Create `.streamlit/secrets.toml` with:
   `GEMINI_API_KEY = "YOUR_KEY"`
4. Run `streamlit run app.py`.

## Deploy on Streamlit Community Cloud
1. Push files to GitHub.
2. Create an app at https://share.streamlit.io/.
3. Select this repository, branch `main`, main file `app.py`.
4. In app Settings → Secrets, add `GEMINI_API_KEY = "YOUR_KEY"`.
5. Deploy.

Never commit your API key or `.streamlit/secrets.toml`.
LinkedIn URLs are references only; the app does not scrape LinkedIn.
Website extraction is best-effort. Session history is temporary until exported.
Review all AI output before using it. Do not enter confidential patient/customer data.
