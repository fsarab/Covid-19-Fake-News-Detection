# COVID-19 Fake News Detection
## Description
This project is a Fake News Detection for the Machine Learning Course at Tehran-Polytechnic (AUT) University . The goal is classification task (real vs fake) and benchmark the annotated dataset with machine learning techniques.
Fake news and rumors are rampant on social media.We annotated dataset with four machine learning baselines - Decision Tree, Logistic Regression, Gradient Boost, and Support Vector Machine (SVM). We obtain the best performance of 93.46% F1-score with SVM.

## Challenge
This was a competition challenge based project arranged by CodaLab (https://competitions.codalab.org/competitions/26655). The challenge was to build a system which can detect fake news based on given training dataset (which included tweets and comments from various social media users)
The following article is mainly used.
paper:
[https://arxiv.org/abs/2011.03327]

website:
[https://constraint-shared-task-2021.github.io/]


## Data 
(train, validation, test, test labels): 
[https://competitions.codalab.org/competitions/26655]

• Real- Tweets from verified sources and give useful information on COVID-19.

• Fake- Tweets, posts, articles which make claims and speculations about COVID-19 which are verified to be not true.

@misc{

      patwa2020fighting,
      title={Fighting an Infodemic: COVID-19 Fake News Dataset}, 
      author={Parth Patwa and Shivam Sharma and Srinivas PYKL and Vineeth Guptha and Gitanjali Kumari and Md Shad Akhtar and Asif Ekbal and Amitava Das and Tanmoy Chakraborty},
      year={2020},
      eprint={2011.03327},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}

## Results

10 mostfrequent tokens after removing stopwords are: 

• Fake: coronavirus, covid19, people, will, new, trump, says, video, vaccine, virus. 

• Real: covid19, cases, new, tests, number, total, people, reported, confirmed, states. • Combined: covid19,cases,coronavirus, new, people, tests, number, will, deaths, total.

### **Decision Tree**

Decision Tree Accuracy(test):  0.8864485981308411

Decision Tree Precision(test):  0.8866216229482448

Decision Tree Recal(test):  0.8864485981308411

Decision Tree F1_score(test):  0.8864914934620883

### **Logistic Regression**

Logistic Regression Accuracy(test):  0.9200934579439253

Logistic Regression Precision(test):  0.9203180956962224

Logistic Regression Recal(test):  0.9200934579439253

Logistic Regression F1_score(test):  0.9200590271473257

### **Gradient Boost**

Gradient Boost Accuracy(test):  0.8906542056074767

Gradient Boost Precision(test):  0.8906463847221131

Gradient Boost Recal(test):  0.8906542056074767

Gradient Boost F1_score(test):  0.8906495159369164

### **SVM** 

SVM Accuracy(val):  0.9285046728971963

SVM Precision(val):  0.9285379607450457

SVM Recal(val):  0.9285046728971963

SVM F1_score(val):  0.9284869868371163
##  About Me
I'm M.Sc student in Computer Science at Tehran-Polytechnic (AUT) and interested research in Machine Learning ,Natural Language Processing and Data Science.


## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fatemeh-arab/)


