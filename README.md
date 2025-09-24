# AI-LearningInsights
Simple News Chatbot
This script is a simple, all-in-one news chatbot that scrapes news from various sources, finds and groups similar articles, and allows you to ask questions about the news using an AI model.

Features
Web Scraping: Gathers news articles from predefined websites.
Duplicate Detection & Clustering: Identifies and groups similar news stories using TF-IDF and cosine similarity.
News Highlights: Creates a list of top news highlights based on the frequency of reporting across sources.
Database Storage: Saves the news highlights to a MongoDB database.
AI Chatbot: Answers user questions about the news highlights using an OpenAI model.
Prerequisites
Before running the script, you need to have the following:

Python 3.6 or higher: The script is written in Python.
OpenAI API Key: Required to use the AI chatbot functionality.
MongoDB Database: A MongoDB database to store the news highlights.
.env file: A file in the same directory as the script containing your API keys and MongoDB connection string.
Setup
Clone the repository (if applicable) or save the script: Save the provided Python code as a .py file (e.g., news_chatbot.py).

Install required libraries: The script will automatically check for and install the necessary libraries if they are not already present.

Create a .env file: In the same directory as your script, create a file named .env and add the following lines, replacing the placeholder values with your actual keys and connection string:
