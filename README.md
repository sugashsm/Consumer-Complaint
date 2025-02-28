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
## **Screenshot**

Model : Multinomial Naive Bayes
![image](https://github.com/user-attachments/assets/296295c7-b97f-4151-bba6-4c36e06c74a8)
![image](https://github.com/user-attachments/assets/6a19df81-b787-4c1b-9f7d-1435e16ec35e)



Model : Logistic Regression
![image](https://github.com/user-attachments/assets/409e59dc-0634-47de-b5ad-2926fff29ba1)
![image](https://github.com/user-attachments/assets/34934e08-c38d-4346-a7cf-3014f80cfa36)



Model : Random Forest

![image](https://github.com/user-attachments/assets/ac76c223-5eab-4ff9-9b41-72e3fc733d71)

![image](https://github.com/user-attachments/assets/827718be-4894-4a30-8c2f-8bc4b3e254c3)


## **Dataset**  
The dataset can be downloaded from the [Consumer Complaint Database](https://catalog.data.gov/dataset/consumer-complaint-database).

## **Contributing**  
Feel free to submit issues or pull requests to improve the project.


