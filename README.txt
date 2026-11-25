AURUM single-file Streamlit app

Files:
- app.py: combines the dashboard and forecasting model in one Python file.
- data/occupancy_birmingham.csv: model training occupancy dataset.
- data/parking_sessions.csv: behaviour modifier dataset.
- requirements.txt: Python dependencies.

Run locally:
  pip install -r requirements.txt
  streamlit run app.py

For Streamlit Community Cloud, upload all files/folders preserving this structure,
then set the main file path to app.py.

Note: forecasts use Birmingham training data mapped to indicative Delhi parking locations.
They are estimates, not live parking availability.
