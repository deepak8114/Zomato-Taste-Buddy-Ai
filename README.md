# Zomato-Taste-Buddy-Ai
A full-stack AI solution combining Machine Learning, Large Language Models (LLMs), and Flask API to revolutionize how users discover food on Zomato.
# Zomato-TasteBuddy-AI

> An Intelligent, Hands-Free Meal Recommendation System Using Machine Learning + LLMs

TasteBuddy AI is an AI-powered restaurant and meal recommendation engine built using Zomato’s restaurant data. It combines Machine Learning, Large Language Models (LLMs), and a Flask API to deliver personalized, region-aware, hands-free food discovery experiences — especially for children, elderly people, and users with limited literacy.



##  Problem Statement

Zomato and Swiggy face high competition from new players like Rapido, rising commissions, and high bounce rates due to decision fatigue. Many users browse but don’t order — because they simply don’t know what to choose.



##  The Solution: TasteBuddy AI

A hands-free AI assistant that:
- Understands past orders and suggests dishes intelligently
- Offers voice/image input for accessibility
- Creates combos with discounts using purchase history
- Adds regional food emotion (Geo-flavor hooks)
- Works via API or app integration



##  Features

- ✅ Restaurant rating predictor (High/Low)
- ✅ Price range classifier (₹ / ₹₹ / ₹₹₹)
- ✅ Cuisine popularity insights
- ✅ Flask API endpoints for real-time prediction
- ✅ TasteBuddy AI architecture for LLM-based suggestions
- ✅ Power BI dashboard for executive view



##  Tech Stack

| Component           | Tools/Libraries                                |
|--------------------|-------------------------------------------------|
| Data Analysis       | Pandas, NumPy, Matplotlib, Seaborn             |
| ML Modeling         | Scikit-learn, XGBoost, SMOTE                   |
| API Deployment      | Flask, Pickle                                  |
| Dashboard           | Power BI                                       |
| AI/LLM Integration  | GPT-style prompt engine (conceptualized)       |



##  Folder Structure
Zomato-TasteBuddy-AI/
├── README.md
├── TasteBuddy_AI_Report_DeepakPatro.pdf
├── TasteBuddy_AI_Presentation.pptx
├── Zomato_Restaurants_.ipynb
├── flask_app/
│ ├── app.py
│ └── model.pkl
├── data/
│ └── zomato.csv
├── images/
│ ├── dashboard.png
│ ├── architecture.png
├── requirements.txt
└── LICENSE (optional)



##  Power BI Dashboard Highlights

- Restaurant distribution by city
- Top cuisines by ratings
- Rating distribution histogram
- Online delivery trends
- Cost-for-two by area

![Dashboard Preview](images/dashboard.png)

---

##  TasteBuddy AI Architecture



##  Flask API Endpoints

| Endpoint         | Description                            |
|------------------|----------------------------------------|
| `/predict_rating` | Predicts restaurant rating (High/Low) |
| `/predict_price`  | Predicts price tier (₹, ₹₹, ₹₹₹)       |
| `/analyze_sentiment` | Returns sentiment from review text  |


##  Business Value to Zomato

-  Boosts AOV and combo upsells
-  Smart, AI-driven food discovery
-  Inclusive: designed for children, elderly, rural users
-  Deployable via kiosk, voice interface, or mobile app



## References

- [Zomato Kaggle Dataset](https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants)
- [MoneyControl, ETtech - Financial insights]
- [IMARC, Research & Markets - Market growth reports]


## Author

Deepak Kumar Patro  
deepakpatro73@gmail.com  
(https://www.linkedin.com/in/deepak-patro-2a0330228/)



> _TasteBuddy AI isn't just data science — it's human-centered design powered by intelligence. Let's make food discovery accessible to all._

