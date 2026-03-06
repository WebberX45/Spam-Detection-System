# Spam-Detection-System


Welcome to my **Spam Detection System** project. In this project, I built a **machine learning model that classifies SMS messages as Spam or Not Spam (Ham)** using Natural Language Processing (NLP) techniques.

The project focuses on **text preprocessing, feature extraction, and model training** to accurately identify unwanted spam messages.

---

## Dataset

The dataset used in this project is the **SMS Spam Collection Dataset**, which contains thousands of SMS messages labeled as either **spam** or **ham (not spam)**.

Dataset features include:

- **Label** – Indicates whether the message is spam or ham
- **Message** – The actual SMS text content

The dataset enables the development of machine learning models for **spam classification and text analysis**.

---

## Tools & Libraries

- **Google Colab**
- **Python**
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Scikit-learn** – Machine learning models
- **NLTK / NLP preprocessing techniques**
- **CountVectorizer & TF-IDF** – Text feature extraction

---

## Project Workflow

1. **Data Loading**
   - Imported the dataset using Pandas.

2. **Data Cleaning**
   - Removed unnecessary columns.
   - Handled missing values and duplicate records.

3. **Text Preprocessing**
   - Converted text to lowercase
   - Removed punctuation and special characters
   - Tokenization and stopword removal

4. **Feature Engineering**
   - Converted text data into numerical format using:
     - **CountVectorizer**
     - **TF-IDF Vectorization**

5. **Model Training**
   - Split dataset into training and testing sets.
   - Applied multiple machine learning algorithms including:
     - Naive Bayes
     - Logistic Regression
     - Support Vector Machine (SVM)
     - Decision Tree
     - Random Forest
     - K-Nearest Neighbors
     - Gradient Boosting
     - XGBoost

6. **Model Evaluation**
   - Evaluated models using:
     - Accuracy Score
     - Precision Score
     - Confusion Matrix

---

## Key Insights

- Text vectorization techniques such as **TF-IDF significantly improve model performance**.
- **Naive Bayes models perform exceptionally well for text classification tasks.**
- Feature extraction plays a critical role in improving spam detection accuracy.
- Ensemble models can also provide competitive results in classification problems.

---

## Real-World Applications

This spam detection system has many practical uses:

- **Email Spam Filtering**  
  Used by email services like Gmail and Outlook to filter unwanted emails.

- **SMS Security Systems**  
  Telecom companies use spam detection to block malicious or promotional messages.

- **Fraud Prevention**  
  Helps detect phishing messages and scam links.

- **Customer Protection**  
  Prevents users from receiving harmful or fraudulent messages.

- **Social Media Moderation**  
  Platforms can detect and remove spam content automatically.

---

## Conclusion

This project demonstrates how **Natural Language Processing and Machine Learning** can be used to classify text messages effectively.

By applying preprocessing techniques, feature extraction methods, and multiple machine learning models, the system can **accurately distinguish between spam and legitimate messages**.

Spam detection systems like this play an important role in **improving digital communication security and user experience**.

---

## Contact

For questions, feedback, or collaboration:

LinkedIn: https://www.linkedin.com/in/pranav-kumar-553583394  
Email: d.sci.pranav@gmail.com
