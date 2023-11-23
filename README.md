# Reuters News Classification and Analysis
Develop a model for categorizing news articles, perform web scraping and translation on articles, and make predictions on their categories using TensorFlow, Keras, and the Google Translate API.

This project comprises three primary Python files:

1. **reuters_classification.py**: Implements a classification model for Reuters news utilizing TensorFlow and Keras.
2. **news_scraper_translator.py**: Encompasses classes for scraping news and translating text.
3. **demo.py**: Illustrates how to train the Reuters model and analyze news articles.

### reuters_classification.py
Within this file, you'll find the `ReutersModel`, `ReutersTrainer`, and `ReutersPredictor` classes. The `ReutersModel` class is responsible for constructing, training, and evaluating the news classification model using the Reuters dataset. The `ReutersTrainer` class facilitates model training, and the `ReutersPredictor` class predicts the category based on a given text input.

### news_scraper_translator.py
This file introduces the `NewsScraper` and `TextTranslator` classes. The `NewsScraper` class manages the retrieval and extraction of news articles' titles and content from a provided URL. The `TextTranslator` class is in charge of translating text using the Google Translate API.

### demo.py
Within this file, you'll discover how to train the Reuters model and analyze news articles using the `ModelTrainer` and `NewsAnalyzer` classes. The `ModelTrainer` class handles the training of the Reuters model, while the `NewsAnalyzer` class analyzes news articles, translates text, and predicts their category using the trained model.

## Usage
To utilize this project, follow these steps:

1. Install the necessary Python libraries:

   ```bash
   pip install -r requirements.txt

2. Run demo.py to train the Reuters model and analyze a news article:

   ```bash
   python demo.py   
The script will output the predicted category for the given news article.
