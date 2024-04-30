# AI-MAVERICKS-Movie_Recommender_System_with_Sentiment_Analysis
The main task of the system is to provide personalized recommendations using cosine similarity and count vectorization as Content-based filtering. Presentation of recommendations is an important part of the overall user experience.

In today’s world watching online movies have become a popular trend and a daily habit of our new generation. Movies are a reliable source for gaining knowledge and it is easier to grasp information through videos, movies than reading. The internet is flooded with billions of movies hence it is a time-consuming task for user to find a relevant movie to watch. So to save time as well as efforts there is a necessity to build a strong, efficient and accurate recommendation system which will display appropriate movies for the users. movie recommendation system saves users from browsing lots of movies to choose the appropriate ones, and on the other hand, it also brings the movie websites more network traffic and user stickiness. The main task of the system is to provide personalized recommendations using cosine similarity and count vectorization as Content-based filtering.
# How to get your own API key?
Create an account in https://www.themoviedb.org/ else login if you have already just login, click on the API from menu bar  in your account settings and click on create new API key and fill all the details to apply for API key. It gonna ask for the website URL, just give "NA" if you don't have one. You will see the API key in your API menu bar once your request is approved.
# How to setup and run?
Here's a step-by-step guide to setting up and running our movie recommendation system project using sentiment analysis in Anaconda Jupyter Notebook:

1. *Install Anaconda* : If you haven't already, download and install Anaconda from the official website: https://www.anaconda.com/products/distribution. Follow the installation instructions for your operating system.

2. *Launch Anaconda Navigator* : Once Anaconda is installed, you can launch Anaconda Navigator, which provides a graphical interface for managing your Python environments, packages, and applications.

3. *Create a New Environment* : In Anaconda Navigator, you can create a new Python environment for your project. Click on the "Environments" tab and then click the "Create" button. Give your environment a name and select the Python version you want to use (e.g., Python 3.8).

4. *Install Jupyter Notebook* : After creating your environment, go to the "Home" tab in Anaconda Navigator and make sure your new environment is selected in the "Applications on" dropdown menu. Then, click the "Install" button next to Jupyter Notebook to install it in your environment.

5. *Launch Jupyter Notebook* : Once Jupyter Notebook is installed, you can launch it from Anaconda Navigator. Click on the "Home" tab, select your environment in the "Applications on" dropdown menu, and then click the "Launch" button next to Jupyter Notebook.

6. *Create a New Notebook* : In Jupyter Notebook, navigate to the directory where you want to store your project files. Click on the "New" button in the top right corner and select "Python 3" to create a new Python notebook.

7. *Import Libraries* : In your Jupyter Notebook, start by importing the necessary libraries for our project which was mentioned in the requriments.txt file.

8. *Load the Dataset*: Next, load our movie dataset into the notebook. You can use pandas to read data from CSV files.

9. *Preprocess the Data*: Preprocess the text data in our dataset to prepare it for sentiment analysis. This might involve steps like removing punctuation, converting text to lowercase, tokenizing the text into words, removing stopwords, and stemming or lemmatizing words.

10. *Perform Sentiment Analysis*: Apply sentiment analysis techniques to analyze the text data in our dataset. You can use pre-trained sentiment analysis models or train your own model using machine learning algorithms like Naive Bayes, Support Vector Machines, or neural networks.

11. *Recommend Movies*: Finally, use the sentiment analysis results to recommend movies to users based on their preferences. You can recommend movies with positive sentiment scores for users who prefer upbeat movies and movies with negative sentiment scores for users who enjoy more intense or dramatic films.

12. *Test and Evaluate*: Test your recommendation system with sample queries or user interactions to see how well it performs. You can also evaluate the system's accuracy and effectiveness using metrics like precision, recall, and accuracy.

That's a high-level overview of setting up and running our movie recommendation system project in Anaconda Jupyter Notebook.
