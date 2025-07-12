# fatigue-detection
new data science project on fatigue detection and analyses
fatigue-detection/
├── README.md                  # Project overview & documentation
├── requirements.txt           # Python dependencies
├── data/                      # Raw and processed data
│   ├── raw/
│   └── processed/
├── notebooks/                 # Jupyter notebooks for EDA & modeling
│   ├── 01_data_exploration.ipynb
│   ├── 02_preprocessing.ipynb
│   └── 03_lstm_modeling.ipynb
├── src/                       # Source code
│   ├── data_preprocessing.py
│   ├── model_utils.py
│   └── api.py                 # Flask API (Step 5)
├── models/                    # Saved models
└── reports/                   # Visualizations & evaluation reports
requirements.txt 
## We are looking at all the requirements needed to get this project running and tools needed
numpy>=1.21
pandas>=1.3
matplotlib>=3.4
seaborn>=0.11
scikit-learn>=0.25
tensorflow>=2.6
keras-tuner>=1.1.2
flask>=2.0
gunicorn>=20.1
jupyter>=1.0
