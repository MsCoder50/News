# News Aggregator 📰

## 📖 Overview
This **News Aggregator** is a Python-based desktop application that pulls the latest headlines and articles from global news APIs. It acts as a centralized dashboard, allowing users to stay informed without needing to navigate through multiple news websites.

## 💡 Concept & Architecture
Building a news aggregator requires a robust pipeline for fetching, parsing, and displaying remote JSON data.
- **API Integration (`news.py`)**: This module acts as the networking layer. It connects to external News REST APIs (like NewsAPI or similar services), authenticating via API keys and fetching structured data based on categories or keywords.
- **User Authentication (`signup.py`)**: Demonstrates a fundamental user-management system, allowing the application to save individual user preferences, localized news, or saved articles.
- **Presentation (`main.py` & `/Assets`)**: The central hub that takes the raw JSON data and formats it into a readable, visually pleasing format within a graphical interface. The `/Assets` folder contains icons and visual styling elements.

## ✨ Key Features
- **Live Feed Updates**: Fetches data dynamically, ensuring you are always reading the most recent articles.
- **User Accounts**: Personalize your news feed by signing up and configuring your preferences.
- **Clean UI**: Bypasses the clutter, ads, and popups of modern news sites, delivering pure content.

## 🚀 Getting Started
```bash
# First, ensure you have configured your API keys if required in news.py
# Then run the main application:
python main.py
```
