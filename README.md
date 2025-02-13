# Yelp-Business-Analysis-Spark-Project

## 📌 Project Overview
<a href="https://colab.research.google.com/github/UVI2k/Portfolio-Projects/blob/main/Yelp_Business_Analysis_Project.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

# Data Management and Analysis with Yelp API and Apache Spark

### **Data Collection with Yelp API**

1.1 - Setup Yelp API
Before collecting data, you'll need to set up access to the Yelp API. Make sure you have your API key as outlined in the final project assignment document.

## 🛠️ Installation & Setup
To run this project, install the required dependencies:
```bash
pip install -r requirements.txt
```

## 💊 Dataset Details
This project analyzes business performance and customer reviews from Yelp. The dataset includes business attributes, customer ratings, and review text.

## 🚀 Key Features
- Data Extraction from Yelp API
- Business Performance Analysis
- Sentiment Analysis on Reviews
- Data Visualization & Insights

## 📝 Example Code
```python
# Yelp API Key
api_key = 'YOUR_API_KEY'  # Replace with your API key

# Yelp API endpoint for Business Search
endpoint_url = 'https://api.yelp.com/v3/businesses/search'

import requests
import pandas as pd

# Initiating an empty list to collect all data before making a dataframe
EdmontonBusinesses = []

# Search parameters
terms = ['restaurants', 'bars', 'cafes']
locations = ['Edmonton', 'Sherwood Park', 'Beaumont']
maximum_radius = 15000 # 15km range
```

## 🔮 Future Improvements
- Improve sentiment classification using deep learning  
- Expand analysis with geospatial mapping  
- Deploy as an interactive business analytics dashboard  

## 🐄 License
This project is licensed under the MIT License.

