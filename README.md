Movie Recommendation System
Overview
This Movie Recommendation System is a web application built using Flask, providing users with movie recommendations based on collaborative filtering and natural language processing. The system uses a machine learning model to analyze user reviews and suggest similar movies.

Dependencies
Flask==1.1.1
gunicorn==19.9.0
Jinja2==2.11.3
MarkupSafe==1.1.1
Werkzeug==0.15.5
numpy>=1.9.2
scipy>=0.15.1
nltk==3.5
scikit-learn>=0.18
pandas>=0.19
beautifulsoup4==4.9.1
jsonschema==3.2.0
tmdbv3api==1.6.1
lxml==4.6.3
urllib3==1.26.5
requests==2.23.0
pickleshare==0.7.5
Installation
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run the application:

bash
Copy code
python app.py
Access the application at http://127.0.0.1:5000/ in your web browser.

Features
Home Page:

Provides a user interface to input movie titles for recommendations.
Offers autocomplete suggestions based on the dataset.
Similarity Calculation:

Uses collaborative filtering and natural language processing techniques for movie recommendations.
Utilizes a machine learning model trained on movie reviews.
Movie Details:

Displays detailed information about a selected movie, including cast, reviews, and recommendations.
Web Scraping:

Scrapes user reviews from IMDB to enhance recommendations.
Usage
Visit the home page (http://127.0.0.1:5000/) to enter the movie title for recommendations.

Explore detailed information about a movie, including cast details, user reviews, and suggested movies.

Enjoy personalized movie recommendations based on collaborative filtering and user reviews.

File Structure
app.py: Main Flask application file.
nlp_model.pkl: Pickled machine learning model for sentiment analysis.
tranform.pkl: Pickled TF-IDF vectorizer for natural language processing.
main_data.csv: CSV file containing movie data.
templates/: HTML templates for rendering web pages.
Notes
This project uses Flask as the web framework and incorporates machine learning for movie recommendations.
Ensure that dependencies are installed using the provided requirements.txt file.
