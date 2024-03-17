# Instagram_Fake_Account_Detection

The project uses machine learning algorithm to find out the fake accounts available .
We used Logistic Regression model to train the model with a small dataset . 
The accuracy of the project is 93% and 91% after 5 folds . 
The model works using the data available about Instagram User on instagram, It uses data such as followers, following , availability of profile pic , posts and some more details as such .

Team members Details:

L V Manikanta Maguluri(magulurimanikanta123@gmail.com)

Charan Veeranki(vv2052@srmist.edu.in)

Project Title: Fake Instagram Account Detection

Problem Statement:

Develop a machine learning model to detect fake Instagram accounts based on profile characteristics and activity metrics. Given a dataset containing features such as profile picture presence, username characteristics, bio length, posting frequency, and follower count, the model should accurately classify accounts as fake or genuine.

Use Cases:
These are main areas where concern is and needs to be taken care of 

Content Moderation: Automatically detect and remove fake accounts to maintain platform integrity and user experience.

User Protection: Identify and prevent potential scams, fraudulent activities, and privacy breaches associated with fake accounts.

Brand Safety: Ensure brand safety and integrity by identifying fake follower counts and engagement metrics in influencer marketing collaborations.

Ad Fraud Prevention: Detect and mitigate ad fraud by identifying fake accounts artificially inflating ad engagement metrics.

Trust and Transparency: Foster trust among users and demonstrate commitment to combating fraudulent activities by transparently disclosing and removing fake accounts.

Regulatory Compliance: Align with regulatory requirements and standards related to online platforms and data privacy by implementing measures to detect and remove fake accounts.

Research and Analysis: Enable researchers and analysts to study trends and patterns related to fake accounts, enhancing understanding of social media manipulation tactics.

User Education: Empower users to identify and report suspicious activities, contributing to a safer and more trustworthy online community.

Challenges Faced:

There are multiple models out there finding the one which is suitable for our dataset and get the maximum accuracy possible .

Balancing feature selection, addressing class imbalance, and deploying scalable, ethical solutions for detecting fake Instagram accounts.

Youtube video link for demo : https://youtu.be/h4WYTyjY6pI

Images :

![image](https://github.com/Manikanta2502/Instagram_Fake_Account_Detection/assets/117504575/70a67518-411e-46e1-b667-45f43d2f733e)
![image](https://github.com/Manikanta2502/Instagram_Fake_Account_Detection/assets/117504575/e99fe6d8-d1d5-4ec6-b39d-0d59becb92d4)
![image](https://github.com/Manikanta2502/Instagram_Fake_Account_Detection/assets/117504575/e730d77f-0d09-4358-a1be-d5445268ba57)




Live Links : We are working on building a website which links the model to it and can be used through internet.(Coming Soon)

Steps to Run the code Locally:
We recommand using Google Colab or Jupyter Notebook for the process.
1) Download all the files available here and unzip them.
2) Open the main ipynb file .
3) Upload the instagram.csv file to the program.
4) Run the code
5) The code automatically downloads all the required libraries and modules needed.
6) It automatically gives you the model(saved) file as well.
7) You can use the model file whenever needed instead of running all the program
8) Input the details the program asks for such as profile pic status and so.
9) The program gives you the output as "Fake" or "Not Fake"


Technologies Used :

1)Python with scikit-learn and pandas for machine learning model development.

2)ONNX for model interoperability and scalability, deployed using onnxruntime for real-time inference.

