# **Zomato Restaurant Sentiment Analysis**

## **📌 Project Overview**

This project focuses on performing comprehensive Exploratory Data Analysis (EDA) and building a robust Machine Learning pipeline to conduct **Sentiment Analysis** on Zomato restaurant reviews. The objective is to automatically classify customer feedback into **Positive** or **Negative/Neutral** sentiments, enabling restaurant owners and Zomato stakeholders to derive actionable business insights from massive volumes of unstructured textual data.

IPYNB

## **🚀 Key Features**

* **Data Cleaning:** Rigorous handling of missing values, duplicate removal, and numerical outlier treatment (Winsorization).  
  IPYNB  
* **NLP Pipeline:** Advanced text preprocessing including contraction expansion, lemmatization, stopword removal, and TF-IDF Vectorization.  
  IPYNB  
* **Data Balancing:** Applied **SMOTE (Synthetic Minority Over-sampling Technique)** to handle extreme class imbalance in review ratings, ensuring fair model training.  
  IPYNB  
* **Model Implementation:** Built and tuned three distinct classification models:  
  * Logistic Regression (Final Production Model)  
  * Random Forest Classifier  
  * Multinomial Naive Bayes  
* **Optimization:** Utilized `GridSearchCV` and `RandomizedSearchCV` for hyperparameter tuning to maximize the **F1-Score**.  
  IPYNB  
* **Deployment Ready:** The final model and vectorizer are serialized using `pickle` for real-time inference.  
  IPYNB

## **🛠 Tech Stack**

* **Language:** Python 3.x  
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, NLTK, Imbalanced-Learn  
* **Environment:** Google Colab (GPU-accelerated)

## **📊 Summary of Insights**

* **Pricing Trends:** The vast majority of restaurants are mid-range (500–1,200 Rupees for two), providing a clear target for marketing campaigns.  
  IPYNB  
* **Engagement:** A positive correlation exists between restaurant cost and media engagement; high-end dining experiences generate significantly more photos in reviews.  
  IPYNB  
* **Sentiment Drivers:** The sentiment classification model achieves high stability and interpretability, allowing stakeholders to identify specific words (e.g., "delicious" vs. "disgusting") that drive positive or negative ratings.  
  IPYNB

## **📂 Repository Structure**

* `Zomato_ML_Tanim.ipynb`: The main Jupyter Notebook containing the full pipeline.  
* `Zomato Restaurant names and Metadata.csv`: Raw restaurant metadata.  
* `Zomato Restaurant reviews.csv`: Raw customer review data.

## **📈 Results**

The **Logistic Regression** model, tuned with `GridSearchCV`, was selected as the final production model due to its superior F1-Score, lightweight computational footprint, and high interpretability. It provides a reliable mechanism for businesses to transition from reactive to proactive quality control.

IPYNB+ 1

## **👤 Author**

**Tanim Naha**

