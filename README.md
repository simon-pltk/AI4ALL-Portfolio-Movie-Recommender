# Top 5000 Movie Recommendation System 

My group and I have built a movie recommendation system that utilizes NLP and Sentiment Analysis to recommend the top 3 movies based on user input. The main inputs the user gave were a release date, the genre, the tone, and a short description of what they wanted to watch. We applied skills such as vectorization, k-means clustering, sentiment scoring, and data visualization using PCA. We did this because we wanted to provide more accurate movie predictions and limit the number of streaming services one would own. This project was done during the AI4ALL ignite program.

## Problem Statement <!--- do not change this line -->

(UPDATE IN README.md)
Describe the motivation for this project, why it is relevant, and what its impacts are.

According to a survey conducted by Talker Research, Americans spend an average of 110 hours per year deciding what to watch. Furthermore, movies are distributed across many different streaming services and, as a result, many households have more than one streaming service. By creating a movie recommender that lists certain movies a person would want to watch, we can help cut decision fatigue as well as narrow the number of streaming services people would own, saving them money.

## Key Results <!--- do not change this line -->

1. Incorporating a database of the top 5,000 movies internationally and sorting through 48 genres to deliver accurate recommendations.
2. Developed a 3D PCA graph to plot each different movie cluster and list each movie in a specific cluster.


## Methodologies <!--- do not change this line -->

To accomplish this, we cleaned and preprocessed all movie overviews and applied TF-IDF vectorization to them to convert simple plot descriptions into numerical feature vectors. We used KMEANS clustering to group similar movies based on the textual features, which allowed us to match the user input within thematically similar clusters.

We also implemented sentiment analysis using VADER to compute a sentiment score on each movie overview. These scores would then lead to the movies being classified as either positive, neutral, or negative. Finally, we created a custom recommendation function to accept user input consisting of a text description, optional genre, year range, and tone. We would calculate similarity scores using cosine similarity and return the top 3 movies.  

## Data Sources <!--- do not change this line -->
*TMDB Top 5,000 Movies Dataset on Kaggle: [Link to Kaggle Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata/data)*

## Technologies Used <!--- do not change this line -->

- Python
- Pandas
- VADER
- Matplotlib
- Numpy
- Scikit-learn

## Authors <!--- do not change this line -->

*EXAMPLE:*
*This project was completed in collaboration with:*
- Simon Plotkin ([simon.m.plotkin@vanderbilt.edu](mailto:simon.m.plotkin@vanderbilt.edu))*
- Shatoya Gardner
- Nathan Seife 
- Aysha Bushra
