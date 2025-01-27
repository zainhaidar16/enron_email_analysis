# Enron Emails Dataset Analysis

This repository contains the code and analysis for the Enron Emails dataset. The Enron Emails dataset is a collection of emails from the Enron Corporation, which can be used for various data analysis tasks. This assignment focuses on data cleaning, preprocessing, and exploratory data analysis of the Enron Emails dataset.

## Purpose

The purpose of this assignment is to analyze the Enron Emails dataset and gain insights into the communication patterns, volume of emails, top senders and recipients, distribution of emails by recipient type, and common topics of discussion. The analysis involves data cleaning, preprocessing, SQL queries to extract relevant information from the database, and data visualization using Python libraries such as Pandas, Matplotlib, and NLTK.

## Dataset

The Enron Emails dataset is stored in an SQLite database file named `enron.db`. The database consists of three tables: `employeelist`, `message`, and `recipientinfo`. These tables contain information about employees, email messages, and recipients. The dataset provides a rich source of information to explore various aspects of email communication within the Enron Corporation.

## Repository Contents

- `enron.db`: SQLite database file containing the Enron Emails dataset.
- `Enron Email Analysis.ipynb`: Jupyter Notebook containing the code for data cleaning, preprocessing, and analysis of the Enron Emails dataset.
- `README.md`: This file providing an overview of the assignment and repository.

## Requirements

The following Python libraries are required to run the code in the Jupyter Notebook:

- SQLite3
- Pandas
- Matplotlib
- NLTK (Natural Language Toolkit)
- Wordcloud

You can install the required libraries using pip.

## Usage

To use this repository, follow these steps:

1. Clone or download the repository to your local machine.

2. Install the required Python libraries as mentioned in the Requirements section.

3. Open the Jupyter Notebook `Enron Email Analysis.ipynb` in Jupyter Notebook or Google Colab.

4. Run the cells in the notebook to execute the code and perform data analysis tasks.

5. Explore the results, visualizations, and insights generated by the notebook.