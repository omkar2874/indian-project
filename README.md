# India ML Studio

Streamlit frontend for the bundled `indian.pkl` machine-learning model.

## Run on Windows

From this project folder, create and activate a virtual environment, install the
dependencies, and start the app:

```powershell
py -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
python -m streamlit run App.py
```

The model file must remain in the same folder as `App.py`. The app reads the
model's feature names and creates a numeric input for each one.
