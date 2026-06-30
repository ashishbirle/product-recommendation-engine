# E-commerce Product Recommendation Engine

This application accepts a product from the user and recommends 5 similar products depending on its similarity with the top 5 product from the dataset.

The dataset contains a list of 20000 products with more than 10 attributes. By building a new attribute called 'Features' containing the value of three columns we convert it to numerical representation and understand the similarity among products. 

The jupyter notebook contains various steps performed:
- Cleaning
- EDA
- Analysis
- Charts 

## Working application images for reference
https://github.com/ashishbirle/Product-Recommendation-Engine/tree/main/app_working_images

### Built using:
- Python
- Scikit-Learn
- TfidfVectorizer
- Streamlit

### Run Locally:
1. pip install -r requirements.txt
2. streamlit run streamlit_app.py
