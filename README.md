# IEEESBM-TechnoColosseum-ML

Techno Colosseum is IEEE SBM's flagship event, wherein I secured the [3rd position](/IEEESBM&#32;Certificate.pdf) in the Machine Learning Round.

The Machine Learning Round spanned over two days and consisted of the following tasks:

## Machine Learning Quiz:

A quiz based on Machine Learning with 10 multiple-choice multi-correct timed questions was hosted on HackerEarth. The quiz covered topics including Supervised and Unsupervised Learning, Computer Vision and Natural Language Processing.



## Dataset Analysis:

### Problem Statement:

Analyze the given synthetic [dataset](/Default_Fin.csv) from a financial institution and predict the potential loan defaulters. Split the dataset using random_state = 42, and find the score using the testing set.

### [My Model:](/Loan&#32;Defaulter.ipynb)

I constructed a Pipeline to predict the class of the dependent variable using XGBClassifier after transforming the numerical columns using Robust Scaler and Simple Imputer after performing basic Exploratory Data Analysis which included checking for missing values, checking for skewed features by plotting a distribution plot, checking for correlated features by plotting a heatmap and engineering a new feature to improve the accuracy, and finally calculating the Accuracy Score on the testing data.



## Telegram Bot:

### Problem Statement:
Deploy a bot on Telegram to answer any question related to IEEE SBM. Use IEEE SBM's website, Instagram handle and Facebook page for resources.

### [My Model:](https://t.me/zeus_ieee_bot)

I built a ChatBot on Google Dialogflow ES Console and integrated it with the Telegram interface. The ChatBot is enriched with Custom Payloads including Inline Keyboard Buttons specific to the Telegram interface alongwith Text Responses with links outbound to IEEE SBM's online presence.


<br></br>

***All the credits for hosting the competition, forming the problem statements, and constructing the dataset go to IEEE SBM.***
