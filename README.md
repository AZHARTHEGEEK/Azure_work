# Azure_work
Explore and analyze data with Python
Data exploration and analysis is at the core of data science. Data scientists require skills in languages like Python to explore, visualize, and manipulate data.
# Introduction
Unsurprisingly, the role of a data scientist primarily involves exploring and analyzing data. The results of this analysis might form the basis of a report or a machine learning model; but it all begins with data.
Usually, a data analysis project is designed to establish insights around a particular scenario or to test a hypothesis. For example, suppose a university professor collects data from data science students, including the number of lectures attended, the hours spent studying, and the final grade achieved on the end of term exam. The professor could then take a sample of the data and analyze it to determine if there is a relationship between the amount of study a student undertakes and the final grade they achieve. They might use the data to test a hypothesis that only students who study for a minimum number of hours can expect to achieve a passing grade; or even prepare the data to train a machine learning model that predicts a student's grade based on their study habits.
# Exercise - Explore data
Data exploration and analysis is typically an iterative process, in which the data scientist takes a sample of data, and performs the following kinds of task to analyze it and test hypotheses:

* Clean data to handle errors, missing values, and other issues.
* Apply statistical techniques to better understand the data, and how the sample might be expected to represent the real-world population of data, allowing for random variation.
* Visualize data to determine relationships between variables, and in the case of a machine learning project, identify features that are potentially predictive of the label.
* Derive new features from existing ones that might better encapsulate relationships within the data.
* Revise the hypothesis and repeat the process.

Data scientists can use a variety of tools and techniques to explore, visualize, and manipulate data. One of the most common ways in which data scientists work with data is to use the Python language and some specific packages for data processing.

The best way to learn about exploring and preparing data is to try it for yourself, so that's what you'll do in this exercise.

Before you start
To complete the exercise, you'll need:

* A Microsoft Azure subscription. If you don't already have one, you can sign up for a free trial at https://azure.microsoft.com/free.
* An Azure Machine Learning workspace with a compute instance and the ml-basics repository cloned.
# Create an Azure Machine Learning workspace
If you don't already have an Azure Machine Learning workspace in your Azure subscription, follow these steps to create one:

1. Sign into the Azure portal using the Microsoft account associated with your Azure subscription.
2. Select ＋Create a resource, search for Machine Learning, and create a new Machine Learning resource with the following settings:
  * Workspace Name: enter a unique name of your choice
  * Subscription: your Azure subscription
  * Resource group: create a new resource group with a unique name
  * Location: choose any available location
3. Wait for your workspace resource to be created (it can take a few minutes). Then go to it in the portal, and on the Overview page for your workspace, launch Azure Machine Learning studio (or navigate to https://ml.azure.com), and sign in using your Microsoft account.
4. In Azure Machine Learning studio, toggle the ☰ icon at the top left to view the various pages in the interface. You can use these pages to manage the resources in your workspace.
