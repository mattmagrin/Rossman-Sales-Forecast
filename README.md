## Sales Forecasting the upcoming six weeks

If you wish, you may interact with the final solutions data products I built, just click on the thumbnails below :

[<img alt="Telegram" src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white"/>](https://t.me/rossman_stores_bot) --> Created to provide easy and remote access to forecasts.

[<img alt="Streamlit" src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white"/>](https://rossmannforecast.herokuapp.com/) --> Allows deeper navigation through data.

-----

## Project Overview 🎯
* **Understanding the root cause behind the solution:**  The company wants to expand the operation, but is not sure how much to invest in each store. The investment needs to be consistent with the projected revenue in each case.


* **Solution developed:** To solve this business problem, I used an adaptation of the CRISP-DM methodology, from which I was able to increase understanding of the influence of factors such as promotion, holiday and competition on revenue. Furthermore, we obtain an assertive prediction in the sales for each storefor the upcoming
six weeks.

* **Top insights + model performance:** [Click here](notebooklink.com)
 
-----

## How was this solution developed? ✔
### Each step has a detailed notebook with explanations, just click on the links below

**1. Data Description -** In this step, after obtaining the data, i did an initial analysis of the data to familiarize myself with the variables involved and to have a clearer view of how to address the problem.


**2. Feature Engineering & Data Filtering -** Here I tried to create/remove some variables that might help on the understanding and usage of the data, as well as variables that might help M.L. algorithms learn patterns in the data to make predictions.


**3. Exploratory Data Analysis (EDA) -** Extremely important step to increase my understanding of the business dynamics, formulating and validating hypotheses.


**4. Data Preparation & Feature Selection: -** In order to obtain more accurate insights, i made some transformations as encodings for categorical data and scaling to numerical ones being careful to apply Minmax and Robust rescaling according to the presence or absence of outliers. In addition, I used the Boruta algorithm to help in the initial choice of the features used.


**5. Machine Learning Modelling & Hyperparameter Fine Tunning :** In this step I used some linear algorithms as well as some tree-based ones, to verify if the phenomena could be modeled linearly or not. In addition, Bayesian optimization was used to find the best hyperparameters for the model with the best performance for the chosen metrics.


**6. Converting Model Performance to Business Numbers & Deploy:** In the final step, I adapted the results to the business context and deployed them to the streamlit. Finally, from the API created, it was possible to launch a bot on telegram to return forecasts, enabling greater accessibility to the solution.

-----

## Key lessons learned 🤓

*   Models must be chosen while keeping in mind the deployment costs. Sometimes the performance difference won't make up for the risk/costs associated with more development time.

*   Exploratory data analysis provides not only important information about data and insights to the business team but also an understanding of how some features might help or not the chosen ML models.

*   Experimenting with the code may give insights on doing things differently, but it must not take forever. Remember Done is better than perfect.

-----

## Special thanks

Special thanks to Master Meigarom Diego Fernandes Lopes who created a phenomenal course, used as the basis for this project. Your content on youtube was what inspired me to take my first steps as a data scientist.
