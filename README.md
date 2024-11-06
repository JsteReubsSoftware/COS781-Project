# COS781-Project

<div align='center'>
 <img altText='sentiment distribution for top 10 products' src='https://github.com/JsteReubsSoftware/COS781-Project/blob/main/docs/results/sentiment_dist_top10.png' width='500px' />
 <img altText='topic modelling sentiment distribution' src='https://github.com/JsteReubsSoftware/COS781-Project/blob/main/docs/results/topicmodelling_sentiment.png' width='430px' />
</div>

### About the project
This is a Data Mining Project for the COS781 Honours Module at the University of Pretoria. In this project we aim to enhance customer experience for software products by utilizing data mining techniques. In this paper we demonstrate how using sentiment analysis and topic modelling can help stakeholders derive meaningful insights from customer reviews. Furthermore, we classify sentiments as positive, negative, or neutral using a pre-trained model such as TextBlob. Additionally, we employ the Latent Dirichlet Allocation (LDA) for analysing the key themes in the reviews such as easy of use or product quality. By analysing statistical evaluations and visualisations such as coherence scores and distribution plots, we explore sentiment trends as well as how sentiments and topics vary across different ratings. Finally, we present our insights obtained from our results which stakeholders can use to enhance product offerings, increase customer satisfaction, and make data-driven decisions. It should be noted that we only focused on the top 10 popular products.

### How to run the project:
1. Clone the repository to your local machine using the command ```git clone https://github.com/JsteReubsSoftware/COS781-Project.git```
2. Next, run the command ```cd COS781-project``` to change the working directory.
3. We used Jupyter Notebook with Python to implement this project. Find the Notebook under the **Code** directory.
4. Install the package to work with Jupyter Notebook by running the command ```pip install notebook```
5. Create and activate a virtual environment by running the following commands in order:</br>
5.1 Run the command `pip install virtualenv` </br>
5.2 Create the `env` folder using the command `python -m venv env` </br>
5.3 Activate the environment using the command `source env\\Scripts\\activate`. You should see the name of the env folder after running any command.</br>
6. Install the required dependencies using the command `pip install -r requirements.txt` (*Make sure you are in the root directory when running this command*)

After running these commands the setup will be complete and you can run the Jupyter notebook cells and add your own experiments.

```text
Note: The requirements.txt file was generated on the Kaggle platform using the command `pip freeze > requirements.txt `.
This means the file will contain other dependencies that might not have been used in this project.
```

### Example output for the Sentiment Analysis and Topic Modelling
- Sentiment Analysis for top 10 products

![Top 10 Products Activity with sentiment analysis](https://github.com/JsteReubsSoftware/COS781-Project/blob/main/docs/results/top10_sentiment_activity.png)

- Topic Modelling for top 10 products

<div align='center'>
  <img src='https://github.com/JsteReubsSoftware/COS781-Project/blob/main/docs/results/candycrushsaga_topics.png' width='1000px' /> </br>
  <img src='https://github.com/JsteReubsSoftware/COS781-Project/blob/main/docs/results/candycrushsaga_text.png' width='500px' />
</div>
