# Sentiment-Analysis-Using-reviews-
This project analyzes customer reviews of musical instruments to determine their sentiment (positive or negative) using machine learning.
This project focuses on performing sentiment analysis on customer reviews related to musical instruments. It applies natural language processing (NLP) and machine learning techniques to classify reviews as positive or negative.

📁 Dataset
File: Instruments_Reviews.csv

Content: Contains text reviews of musical instruments from online platforms.

⚙️ Technologies Used
Python

**Jupyter Notebook
Libraries:**
pandas for data handling
nltk for text preprocessing
scikit-learn for vectorization and machine learning
matplotlib & seaborn for visualization


📌 Steps to Run the Project
1. Clone the Repository
git clone (https://github.com/nanditasingh12/Sentiment-Analysis-Using-reviews-.git)

2. Set Up a Virtual Environment and activate the environment (Optional but Recommended) 
python -m venv env
# On Windows: env\Scripts\activate
3. Install Required Packages


![image](https://github.com/user-attachments/assets/4faa21cd-73d7-4a13-9eee-a7d98a29850f)

![image](https://github.com/user-attachments/assets/800a3565-55ca-4498-bcea-4044bc0cb2e7)

![image](https://github.com/user-attachments/assets/0b21e813-c723-4c17-8c6e-7c7b9ca0ec35)

pip install pandas scikit-learn nltk matplotlib seaborn wordcloud
4. Run the Notebook
Open the notebook in Jupyter or VSCode:

🔍 Project Workflow
🧹 1. Data Preprocessing
Convert text to lowercase

Remove punctuation and special characters
Tokenize text
Remove stopwords
Lemmatize words
![image](https://github.com/user-attachments/assets/9c92ebb4-eb81-4332-837a-bccf6faa1a19)


![image](https://github.com/user-attachments/assets/282df6a1-7ff4-4d16-91af-299edff46eb9)

Text Preprocessing:
![image](https://github.com/user-attachments/assets/be7ef702-03d8-4752-876b-df5399f551fb)


🧠 2. Feature Extraction
Use TF-IDF Vectorizer to convert text into numeric format

![image](https://github.com/user-attachments/assets/a7090f0a-5b7e-4aad-96ed-d7e4e0b2c398)


🧪 3. Model Training
Trains and evaluates three machine learning models:

Logistic Regression

Naive Bayes

Support Vector Machine (SVM)

![image](https://github.com/user-attachments/assets/64e0da9c-d82a-48e0-8b48-419e7ecf2ac9)


📊 4. Evaluation
Accuracy, Precision, Recall, F1-Score


Confusion Matrix
![image](https://github.com/user-attachments/assets/c731dede-27a2-439e-b270-9f074151ba9c)


📈 Results
The models are compared based on performance metrics. Logistic Regression and SVM typically show higher accuracy for this type of binary classification.
![image](https://github.com/user-attachments/assets/a11d57a6-6f85-4f44-b62f-7ac2b35da6b1)

![image](https://github.com/user-attachments/assets/e711c7a1-5492-4c79-84f7-1bd8eea52078)

![image](https://github.com/user-attachments/assets/0efc77ff-83d1-4060-8967-d6211f950d80)

![image](https://github.com/user-attachments/assets/5fbdcbba-eb62-4429-a55b-eca6d69d2de9)


📎 Screenshots


![image](https://github.com/user-attachments/assets/6bf5b387-d42c-4972-b8f4-24f764af5b97)


**Conclusion:**

Dataset

Our dataset contains many features about user reviews on musical instruments. But, we rarely need those features as our model variables because those features are not really important for sentiment analysis.
We might need to omit our part of removing stopwords in our preprocessing phase, because there might be some important words in determining user sentiments in our model.
From our text analysis, we know that most of the transactions made are related to guitars or other string-based instruments. We can say that guitar got a really high attention from the customers' pool and the sellers can emphasize their products on this instruments.

Model

We tried almost all classification models available. By using 10-Fold Cross Validation, we get that Logistic Regression Model got the best accuracy and we decided to use this model and tune it.
On our attempt on making prediction to our test set, we also received a nice accuracy and high F1 Score. This means that our model works well on sentiment analysis.
We need to consider more Cross Validation Method, such as Stratified K-Fold so that we do not really need to do resampling on our dataset. Also, we are fine without data scaling, but it is highly suggested to do it.





 
