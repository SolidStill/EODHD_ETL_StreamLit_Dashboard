# 🎈 Dashbund Sovereign Bond Yield Tracker App

A simple Streamlit app connecting to my ETL DB that displays multiple bonds simultaneously on a single chart. The selected instruments also have their respective rows from the DB summary table displayed - displaying moving averages and their differentials vs current prices.

The credentials file is not currently shared with this repo for obvious reasons - as such this is not currently viewable on public systems. That being said, all that is required to demo this app when credentials are supplied is the following:

1. Install the requirements

   ```
   $ pip install -r requirements.txt
   ```

2. Run the app

   ```
   $ streamlit run dashbund.py
   ```
