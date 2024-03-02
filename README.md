# Music-Recommendation-System-Using-NLP
Music Recommendation System Using NLP
# Music Recommendation System

This project implements a music recommendation system using content-based filtering. It suggests similar songs based on the input song provided by the user.

## Overview

The system utilizes a dataset containing song information, including song titles, artists, and song lyrics. Using natural language processing techniques, it computes the similarity between songs based on their lyrics. When a user selects a song, the system recommends a list of similar songs.

## Technologies Used

- Python
- Flask
- HTML/CSS
- Bootstrap
- Pandas
- Scikit-learn

## Dataset

The project uses the Spotify Million Song Dataset, which contains a million songs' metadata and audio features.

## File Descriptions

- `app.py`: Contains the Flask application code for handling user requests and providing recommendations.
- `df.pkl`: Pickled Pandas DataFrame containing the preprocessed song data.
- `similarity.pkl`: Pickled cosine similarity matrix between songs.
- `templates/index.html`: HTML template for the user interface.
- `templates/recommendations.html`: HTML template to display recommended songs.
- `static/style.css`: CSS file for styling the web interface.

## Usage

1. Ensure you have Python installed on your system.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Run the Flask application by executing `python app.py`.
4. Access the application through a web browser at `http://localhost:5000`.

## Acknowledgments

- Spotify for providing the Million Song Dataset.
- Kaggle for hosting the dataset and fostering a community of data enthusiasts.
- OpenAI for providing language models like GPT-3, which can be used for text processing tasks.

## Future Improvements

- Incorporate collaborative filtering techniques to enhance recommendations based on user preferences and behaviors.
- Implement user authentication to provide personalized recommendations for each user.
- Improve the user interface to make it more interactive and visually appealing.
- Deploy the application on a cloud platform for wider accessibility.

## Interface

![Uploading image.png…]()
