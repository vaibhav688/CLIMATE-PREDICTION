**NAME:** **Vaibhav vaidyanathan**
**COURSE:** **DATASCIENCE**
**DURATION:** **3MONTHS**
# 🌍 Climate Engagement Prediction Using Machine Learning

This project predicts **user engagement in climate change discussions** using supervised machine learning models.  
It classifies posts into **High Engagement** and **Low Engagement** categories based on features such as likes, comments, text length, and posting time.  
Additionally, the project includes a **Recommendation System** that suggests improvements to increase engagement.

---

## 📁 Project Structure

📦 Climate-Engagement-Prediction
├── 📄 Climate_Engagement_Prediction_Report_IEEE.docx
├── 📊 project 2 climate.csv
├── 📓 CLIMATEPREDICTION.ipynb
└── 📜 README.md

---

## 🧠 Models Used

| Model | Accuracy | Description |
|--------|------------|---------------------------|
| Decision Tree | ~0.68* | Simple interpretable baseline model |
| Extra Trees Classifier | ~0.74* | Ensemble model giving better performance and feature importance |

> *Accuracy values depend on dataset split and processing.*

---

## 📊 Visualizations Included

- Distribution of Likes Count
- Feature Importance (Extra Trees)
- Model Accuracy Comparison
- Average Likes Over Time

These charts help understand engagement behaviour and evaluate model performance.

---

## 🧾 Features Used

| Feature | Description |
|---------|-------------|
| commentsCount | Number of comments |
| text_length | Characters in content |
| word_count | Total words |
| year & month | Temporal posting behaviour |

Target variable:
- **High Engagement** = likes >= median likes count

---

## 🤖 Recommendation System

Based on trained model insights, the system suggests:
- Creating posts that encourage discussions (more comments)
- Posting longer but meaningful content
- Posting during time periods with historically higher engagement

This assists content creators in optimizing climate-related posts for maximum reach.

---

## 🧪 How to Run

```bash
# Clone repository
git clone https://github.com/your-username/Climate-Engagement-Prediction.git

cd Climate-Engagement-Prediction

# Install dependencies
pip install -r requirements.txt

# Run Jupyter notebook
jupyter notebook CLIMATEPREDICTION.ipynb
