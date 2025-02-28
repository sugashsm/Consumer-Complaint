# **Consumer Complaint Text Classification**  

## **Project Overview**  
This project performs text classification on consumer complaint data obtained from the [Consumer Complaint Database](https://catalog.data.gov/dataset/consumer-complaint-database). The goal is to classify complaints into the following categories:  

- **Credit reporting, repair, or other**  
- **Debt collection**  
- **Consumer Loan**  
- **Mortgage**  

## **Steps to Follow**  

1. **Exploratory Data Analysis (EDA) and Feature Engineering**  
   - Understanding the dataset structure  
   - Data cleaning and preprocessing  
   - Feature extraction  

2. **Text Pre-Processing**  
   - Tokenization  
   - Stopword removal  
   - Lemmatization  
   - Vectorization (TF-IDF, Word2Vec, etc.)  

3. **Selection of Multi-Classification Model**  
   - Logistic Regression  
   - Naïve Bayes  
   - Random Forest  
   - Deep Learning (LSTM, BERT, etc.)  

4. **Comparison of Model Performance**  
   - Accuracy, Precision, Recall, F1-score  
   - Hyperparameter tuning  

5. **Model Evaluation**  
   - Cross-validation  
   - Confusion matrix analysis  

6. **Prediction**  
   - Running the final model on unseen complaints  
   - Generating category predictions  

## **Installation**  

Clone the repository:  
```bash
git clone https://github.com/your-repo-name/consumer-complaint-classification.git
cd consumer-complaint-classification
```

Install dependencies:  
```bash
pip install -r requirements.txt
```

## **Usage**  

Run the training script:  
```bash
python train.py
```

Make predictions:  
```bash
python predict.py --input "Your complaint text here"
```

## **Dataset**  
The dataset can be downloaded from the [Consumer Complaint Database](https://catalog.data.gov/dataset/consumer-complaint-database).

## **Contributing**  
Feel free to submit issues or pull requests to improve the project.


