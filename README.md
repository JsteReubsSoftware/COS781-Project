# COS781-Project

<div align='center'>
 <img altText='sentiment distribution for top 10 products' src='https://github.com/JsteReubsSoftware/COS781-Project/blob/main/docs/results/sentiment_dist_top10.png' width='500px' />
 <img altText='topic modelling sentiment distribution' src='https://github.com/JsteReubsSoftware/COS781-Project/blob/main/docs/results/topicmodelling_sentiment.png' width='430px' />
</div>

### About the project
This is a Data Mining Project for the COS781 Honours Module at the University of Pretoria. In this project we aim to enhance customer experience for software products by utilizing data mining techniques. In this paper we demonstrate how using sentiment analysis and topic modelling can help stakeholders derive meaningful insights from customer reviews. Furthermore, we classify sentiments as positive, negative, or neutral using a pre-trained model such as TextBlob. Additionally, we employ the Latent Dirichlet Allocation (LDA) for analysing the key themes in the reviews such as easy of use or product quality. By analysing statistical evaluations and visualisations such as coherence scores and distribution plots, we explore sentiment trends as well as how sentiments and topics vary across different ratings. Finally, we present our insights obtained from our results which stakeholders can use to enhance product offerings, increase customer satisfaction, and make data-driven decisions. It should be noted that we only focused on the top 10 popular products.

### How to run the project:
#### Option 1: Running on your local machine
1. Clone the repository to your local machine using the command ```git clone https://github.com/JsteReubsSoftware/COS781-Project.git```
2. Next, run the command ```cd COS781-project``` to change the working directory.
3. Due to the data file size being too large we could not upload it to GitHub. Please download the data files by clicking on [this](https://datarepo.eng.ucsd.edu/mcauley_group/data/amazon_2023/raw/review_categories/Tools_and_Home_Improvement.jsonl.gz) link (Software.json file) and [this](https://datarepo.eng.ucsd.edu/mcauley_group/data/amazon_2023/raw/meta_categories/meta_Software.jsonl.gz) link (metadata.json). You can also download the zipped files at [this](https://drive.google.com/file/d/1DNkLucm_GI4ez0fQ46rFP-B7dGSPaGUh/view?usp=sharing) link.
4. We used Jupyter Notebook with Python to implement this project. Find the Notebook under the **Code** directory.
5. Install the package to work with Jupyter Notebook by running the command ```pip install notebook```
6. Create and activate a virtual environment by running the following commands in order:</br>
6.1 Run the command `pip install virtualenv` </br>
6.2 Create the `env` folder using the command `python -m venv env` </br>
6.3 Activate the environment using the command `source env\\Scripts\\activate`. You should see the name of the env folder after running any command.</br>
7. Install the required dependencies using the command `pip install -r requirements.txt` (*Make sure you are in the root directory when running this command*)

After running these commands the setup will be complete and you can run the Jupyter notebook cells and add your own experiments.

```text
Note: The requirements.txt file was generated on the Kaggle platform using the command `pip freeze > requirements.txt `.
This means the file will contain other dependencies that might not have been used in this project.

Additionally, the notebook includes file paths starting with `/kaggle/input' since we implemented this using the Kaggle Platform. Be sure to update these paths according to your needs.
```

**Option 2: Running on the Kaggle Platform (*Recommended*)**
1. Download the Jupyter Notebook file in the *Code* directory.
2. Open Kaggle by clicking on [this](https://www.kaggle.com/) link.
3. Login or Sign up.
4. Create a New notebook by clicking on the Top Left `Create -> New Notebook` button.
5. Once the new notebook is opened, click on the `File` button underneath the notebook file's name. Then select `Import Notebook`.
6. Drag & drop or select the downloaded notebook from earlier. This will import the notebook and you will be ready to use it.
7. To import the dataset, open up the right-side menu and click on the `Add Input` button.
8. Filter the search for datasets only by clicking on the 'Datasets' option.
9. Search for the dataset named `cos781-Amazon-Software-Reviews`. It should contain the *Software.jsonl* and *meta_Software.jsonl* files. 
10. Next, click on the `+` icon to add the dataset to your notebook.
12. The setup is now complete and you can simply run the cells without worrying about file paths.

### Example output for the Sentiment Analysis and Topic Modelling
- Sentiment Analysis for top 10 products (note this is not the only output for the sentiment analysis section)

![Top 10 Products Activity with sentiment analysis](https://github.com/JsteReubsSoftware/COS781-Project/blob/main/docs/results/top10_sentiment_activity.png)

- Topic Modelling for top 10 products (note this is not the only output for the topic modelling section)

<div align='center'>
  <img src='https://github.com/JsteReubsSoftware/COS781-Project/blob/main/docs/results/candycrushsaga_topics.png' width='1000px' /> </br>
  <img src='https://github.com/JsteReubsSoftware/COS781-Project/blob/main/docs/results/candycrushsaga_text.png' width='500px' />
</div>
