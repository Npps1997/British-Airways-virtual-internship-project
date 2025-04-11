# ✈️ British Airways Data Science Virtual Experience (Forage)

This repository contains work completed during the **British Airways Data Science Virtual Experience Program** hosted on Forage. The simulation focused on using data to drive key decisions in customer satisfaction and sales.

## Completed Tasks

### Task 1: Customer Review Analysis
- Scraped and cleaned customer review data from Skytrax.
- Performed sentiment analysis and topic modeling using BERTopic.
- Visualized trends using Matplotlib and Seaborn.

### Task 2: Booking Prediction Model
- Analyzed customer booking data to understand purchase behavior.
- Encoded and preprocessed features.
- Built and tuned classification models (Random Forest, XGBoost).
- Achieved 71% accuracy and AUC of 0.78.
- Identified important booking features such as `booking_origin`, `route`, `purchase_lead`, and `length_of_stay`.

## Tools & Technologies Used
- Python (Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn, XGBoost)
- NLP: BERTopic, NLTK, TextBlob
- Model Evaluation: Classification report, ROC-AUC, Confusion Matrix
- Google Colab

## Key Takeaways
- Booking origin and travel logistics significantly influence booking behavior.
- High recall is crucial for identifying potential customers in the airline industry.
- Sentiment and topic analysis can provide actionable insights from unstructured text data.

## 📂 Folder Structure

british-airways-datascience-internship/
│
├── README.md
├── certificate/
│   └── british_airways_certificate.pdf
│
├── presentation/
│   └── project_summary_slides.pptx
│
├── task-1-customer-reviews-analysis/
│   ├── data/
│   │   └── raw_reviews.csv
│   ├── notebooks/
│   │   └── review_analysis.ipynb
│   └── outputs/
│       ├── sentiment_visualizations.png
│       └── topic_modeling_bertopic.png
│
├── task-2-booking-behavior-prediction/
│   ├── data/
│   │   └── Customer_booking.csv
│   ├── notebooks/
│   │   └── booking_behavior_modeling.ipynb
│   └── outputs/
│       ├── classification_report.png
│       ├── feature_importance.png
│       └── roc_curve.png
│
|
└── requirements.txt

### Program Link: https://www.theforage.com/simulations/british-airways/data-science-yqoz?ref=87jnjsrQEx6guHcaq
