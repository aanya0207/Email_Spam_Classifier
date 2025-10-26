📧 Email Spam Detection using Machine Learning

🔍 Overview
This project aims to detect whether an email is spam or ham (not spam) using Machine Learning techniques.  
The dataset is preprocessed, analyzed, and modeled using Python and libraries such as Pandas, NumPy, Scikit-learn, Seaborn, and Matplotlib.
By performing EDA, text preprocessing, TF-IDF vectorization, and Logistic Regression, the model achieves 96.7% accuracy and high precision in classification.


Steps: 
1. Data Collection: Loaded dataset containing labeled messages (`spam` or `ham`).
2. Data Cleaning: Handled missing values, duplicates, and formatting issues.
3. **EDA:** Visualized message length, spam frequency, and text distributions.
4. **Feature Extraction:** Converted text into numerical vectors using **TF-IDF**.
5. **Model Building:** Trained a **Logistic Regression** model for classification.
6. **Evaluation:** Calculated **accuracy, precision, recall, and F1-score**.
7. **Visualization:** Created word clouds, bar plots, and distribution graphs for insights.


🧩 Dataset
The dataset consists of ~5,500 email messages labeled as:
- Spam (1): Unwanted or promotional messages  
- Ham (0): Legitimate emails  

| Column | Description |
|:--------|:-------------|
| `label` | Indicates whether the email is spam or not |
| `message` | The content of the email message |


🧰 Tech Stack
- Programming Language: Python  
- Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, WordCloud  
- ML Algorithm: Logistic Regression  
- Vectorization: TF-IDF  


📈 Model Performance
| Metric | Score |
|:-------|:------:|
| Accuracy | 96.7% |
| Precision | 0.96 |
| Recall | 0.98 |
| F1 Score | 0.98 |



🖼️ Visualizations
- Distribution of spam vs. ham emails  
- Word cloud for most frequent spam and ham terms  
- Message length and frequency plots  
- Correlation between features and labels  



🪄 Key Insights
- Spam messages are generally shorter and repetitive.  
- Certain keywords (like *free, win, offer*) are strong spam indicators.  
- Logistic Regression with TF-IDF achieved the best performance among tested models.



🚀 How to Run
1. Clone the repository  
   ```bash
   git clone https://github.com/<your-username>/email-spam-detection.git
   cd email-spam-detection
