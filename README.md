# Urban Mobility Summative Project – Group 9

## How to Set Up the Project

### 1. Clone the Repository
```bash
git clone https://github.com/teniolaiji/UrbanMobilitySummative_Group9.git
cd UrbanMobilitySummative_Group9
```
### 2. Download the Dataset
Download the train.csv file from https://www.kaggle.com/competitions/nyc-taxi-trip-duration/data?select=train.zip , extract train.csv and place in in project directory
```
UrbanMobilitySummative_Group9/
├── train.csv
├── app.py
├── clean.py
└── ...
```
### 3. Create a Virtual Environment
Windows
```
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```
Mac/Linux
```
python3 -m venv .venv
source .venv/bin/activate
```
### 4. Install Dependencies
```
pip install -r requirements.txt
```
### 5. Preprocess and clean the data
```
python clean.py
# or
python3 clean.py
```
### 6. Run the application
```
python app.py
# or
python3 app.py
```

### 7. Open http://127.0.0.1:5000/ in your browser

# About the Project
This project provides insights into urban mobility by analyzing the New York city taxi trip duration dataset.

# Project Structure
```
UrbanMobilitySummative_Group9/
├── app.py                     # Flask web server
├── clean.py                    # Data cleaning script
├── train.csv                   # NYC taxi trip dataset (download separately)
├── requirements.txt            # Python dependencies
├── static/                     # CSS files
│   ├── analytics.css
│   └── home.css
├── templates/                  # HTML templates
│   ├── analytics.html
│   └── home.html
├── dump.sql                    # SQL dump of the database
└── README.md

```

# Features
- Data cleaning and preprocessing of NYC taxi trip data
- SQLite database storage for efficient data queries
- Web-based dashboard for exploring urban mobility patterns
- Interactive analytics and visualizations
- Trip filtering and analysis capabilities

# Documentation
- https://drive.google.com/file/d/1NadTnYolpn8ciR3_9_e3TQkuRYI9RsCF/view?usp=sharing

# Video Walkthrough
- https://youtu.be/t68nBCRILag

