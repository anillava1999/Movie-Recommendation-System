# Movie-Recommendation-System
A content based movie recommender system using cosine similarity

## Table of Content
  * Demo
  * Overview
  * Motivation
  * Data Collection
  * Data Cleaning
  * Cosine Similarity
  * Modeling
  * Deployement on Heroku
  * Installation and Run 
  * Database Link
  * Future scope of the project
 
## Linkdin Profile
For any queries regarding about this project contact me

Link : https://www.linkedin.com/in/anil-l-b023631b6/

## Demo
Project output demo Link: [https://mrs-campusx.herokuapp.com]

## Overview
Recommendation Engine created as an AI module integrated with mobile app to recommend movies with help content, Developed these POC for to get experience real time projects and Created API using Streamlit Framework and Deployed to the Heroku Cloud platform

## Motivation
What to do when you are at home due to this pandemic situation? I started to learn Machine Learning model to get most out of it. I came to know mathematics behind all supervised models and unspurervised models. Finally it is important to work on application (real world application) to actually make a difference. To get a experience you have to work thats the reason to perform my favourable work done.


## Data Collection 
Movie dataset Extracted the Dataset from the Kaggle you can also extract the data from this link https://www.kaggle.com/tmdb/tmdb-movie-metadata, Kaggle is an Open source and have a large community also they conduct competitions every month,Kaggle allows users to find and publish data sets, explore and build models in a web-based data-science environment, work with other data scientists and machine learning engineers, and enter competitions to solve data science challenges,Given the thousands of other people also doing them, it is becoming harder and harder for merely working through them to be enough to differentiate you. You'll learn a lot, but it won't make you stand out from your competition.Data scientists of all levels can benefit from the resources and community on Kaggle. Whether you are a beginner, looking to learn new skills and contribute to projects, an advanced data scientist looking for competitions, or somewhere in between, Kaggle is a good place to learn


## Data Cleaning

Data cleaning is the process of fixing or removing incorrect, corrupted, incorrectly formatted, duplicate, or incomplete data within a dataset. When combining multiple data sources, there are many opportunities for data to be duplicated or mislabeled. If data is incorrect, outcomes and algorithms are unreliable, even though they may look correct. There is no one absolute way to prescribe the exact steps in the data cleaning process because the processes will vary from dataset to dataset. But it is crucial to establish a template for your data cleaning process so you know you are doing it the right way every time.

In this project, we just split the data into two types are train data and test data to avoid data leakage for new data and remove the word punctuations and Renaming column names for easy access and converting all headlines into lowercase to get a unique word it means if word one contains 'Cycle' and 'cycle' Machine assumes both are different that's why converting all words into lower and after Join all 25 headline columns into one column to perform vectorization and same data cleaning procedure will also apply to the test data 

## How Cosine Similarity works?

Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.

![cosine](https://user-images.githubusercontent.com/71332138/134168633-f85a6481-82a4-445d-82e4-51208984ffbd.png)


For more Details about Cosine Similarity : [https://neo4j.com/docs/graph-data-science/current/alpha-algorithms/cosine/]

## Modeling

Model Training based on trial and error method or by experience, we select the algorithm and train with the selected features.Model evaluation Accuracy of the model , confusion matrix and cross-validation.If accuracy is not high, to achieve higher accuracy, we tune the model...either by changing the algorithm
used or by feature selection or by gathering more data, etc.

#### Perfromed Model : 
* Random Forest -->          86%
* Multinomial Navy Bayes --> 85%
* XGBoost          --->      81%


## Streamlit Framework
Streamlit is an open-source Python library that makes it easy to create and share beautiful, custom web apps for machine learning and data science. In just a few minutes you can build and deploy powerful data apps, We use the streamlit to develop the API for this project

Streamlit Tutorial : [https://streamlit.io/]

## Deployement on Heroku
Once the model has good accuracy, we deploy the model either in the cloud or Rasberry py or any other place. Once we deploy, we monitor the performance of the model.if its good...we go live with the model or reiterate the all process until our model performance is good.
It's not done yet!!!
What if, after a few days, our model performs badly because of new data. In that case, we do all the process again by collecting new data and redeploy the model.

Heroku is a container-based cloud Platform as a Service (PaaS). Developers use Heroku to deploy, manage, and scale modern apps. Our platform is elegant, flexible, and easy to use, offering developers the simplest path to getting their apps to market.



Login or signup in order to create virtual app. You can either connect your github profile or download ctl to manually deploy this project.

[![](https://i.imgur.com/dKmlpqX.png)](https://heroku.com)


## Screenshots

![Screenshot 2021-09-20 at 1 21 49 AM](https://user-images.githubusercontent.com/71332138/134139635-1ff23997-e557-4fe2-9d65-af098e9e12bd.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

![Screenshot 2021-09-20 at 1 22 03 AM](https://user-images.githubusercontent.com/71332138/134139644-3e155819-9105-4e8f-85dd-691d4342541c.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

![Screenshot 2021-09-20 at 1 26 40 AM](https://user-images.githubusercontent.com/71332138/134139661-1b29c50d-d7ad-46dc-8fca-3d1107c34896.png)

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Installation and Run
The Code is written in Python 3.9 If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:

Install Required Libraries

     Step 1: pip install -r requirements.tx
     
Running Project

     Step 2: Streamlit run app.py

## Technologies Used


![](https://forthebadge.com/images/badges/made-with-python.svg)  ![pandas](https://user-images.githubusercontent.com/71332138/134156736-9dcc4675-e588-42a6-9481-816ac08654ab.png)

## Database Link : 
[https://www.kaggle.com/nikhilmittal/flight-fare-prediction-mh/version/1?select=Test_set.xlsx]

## Deploy Heroku tutorial video link :

[https://www.youtube.com/watch?v=IWWu9M-aisA]
 
## Future Scope

* Optimize Streamlit app.py
* Perform Sentimental analysis
* Front-End 


