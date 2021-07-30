# CapstoneProject-EmailClassification

## Data Analysis on Email Classification Data set
* In this we use emails.csv file which provide information of different emails.
* In this emails.csv file we have a target column "Prediction" that identify whether the mail is spam or not.
* In Order to Train the data we make a dataset that conatin equal number of spam and ham mails.

## Data Testing
In Data Testing we test the data on three Different models.
1. Naive Bayes: This model used for text identification through text it identify whether the mail is spam or not.
2. Support Vector Machine: Support Vector Machine is used for classic classification problems. SVMs work on the algorithm of Maximal Margin.
3. Random Forest Classifier: It Ensemble methods turn any feeble model into a highly powerful one.
* CASE 1 : Let's take a word 'Greetings'. Say, it is present in both 'Spam' and 'Not Spam' mails.
* CASE 2 : Let's take a word 'lottery'.Say, it is present in only spam mails.
* CASE 3 : Let's take a word 'cheap'. Say, it is present only in spam mails.

## To Run The Code
* Clone Github Repository to your computer
* Run Train Data.ipynb to prepare the data in your computer.
* Run Test Data.ipynb to check the accuracy of emails.
