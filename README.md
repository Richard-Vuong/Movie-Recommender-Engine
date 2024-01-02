# Movie Recommender Engine
This is a movie recommender engine I created for my capstone project, that utilises text vectorization, and K-means clustering with the elbow and silhouette method to evaluate the optimal K value.

Premise of project:
User inputs a movie -> User gets an output of a list of movies similar to the user input. This similarity is based on Cosine similarity, ensembled with other features used in the dataset, such as popularity of the movie, or profit using K-Means

## Installation
The following libraries in Python need to be installed:

- pandas
- scikit-learn
- ast
- itertools
- matplotlib
- seaborn
- fuzzywuzzy
- python-Levenshtein
- re


## License
[GNU General Public License version 3](https://opensource.org/license/gpl-3-0/)
