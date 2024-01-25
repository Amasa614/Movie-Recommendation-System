# Movie-Recommendation-System


## Project Overview

This repository contains a Content-Based Movie Recommendation System developed using Python. The system is designed to recommend movies to users based on movie content like genres, movie overviews, and taglines. The project demonstrates the power of Natural Language Processing (NLP) and similarity measurement in creating personalized movie recommendations.

## Features

- **Data Processing**: Includes preprocessing of movie metadata (genres, overviews, and taglines).
- **TF-IDF Vectorization**: Transforming textual data into a numerical format for similarity computation.
- **Cosine Similarity**: Calculating similarity scores between movies based on their content.
- **Recommendation Engine**: A function that outputs a list of movies similar to a given movie.

## Dataset

The dataset used in this project is `movies_metadata.csv`, which contains metadata on various movies. Key columns used include `genres`, `overview`, and `tagline`.

## Technologies

- Python
- Pandas for data manipulation
- Scikit-learn for TF-IDF vectorization and cosine similarity

## How to Run

1. Clone this repository.
2. Install the required dependencies: `pip install -r requirements.txt`.
3. Run the Jupyter Notebook to see the recommendation system in action.

## Repository Structure

- `Recommendation System.ipynb`: The main Jupyter Notebook containing the implementation of the recommendation system.
- `movies_metadata.csv`: The dataset file.
- `requirements.txt`: A file listing all the necessary Python packages.

## Usage

To get movie recommendations, input the title of a movie into the recommendation function. The system will output a list of movies similar in content to the input movie.

## Contribution

Contributions to this project are welcome! Please feel free to fork the repository, make improvements, and submit pull requests.

## License

This project is open source and available under the [MIT License](LICENSE).
