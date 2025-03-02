
# Song Identification from Snippets

Project Overview

This project utilizes TF-IDF and Cosine Similarity to identify songs based on small lyric snippets. Given a few words from a song, the model finds the best match from a dataset of over 57,000 songs.

Technologies Used

•	Python
•	Pandas
•	NumPy
•	Scikit-learn (TF-IDF and Cosine Similarity)

Installation & Setup

1.	Install required dependencies:
pip install pandas numpy scikit-learn
2.	Download the dataset from Kaggle and place it in the project directory.
3.	Run the script:
python identify_song.py

Usage
•	The user enters a lyric snippet.
•	The algorithm searches for the closest matching song.
•	Outputs the song title and artist name.

Future Enhancements
•	Convert into a web app using Streamlit.
•	Improve accuracy using deep learning models like Word2Vec or BERT.
