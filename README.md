# Anime Recommendation System

## Introduction

This project aims to provide users with personalized anime recommendations based on their favorite anime choices. The recommendation system utilizes Nearest Neighbors algorithm to find similar animes in the dataset.

## Setup

1. **Clone the Repository:**
   - Clone this repository to your local machine using the following command:
     ```
     git clone https://github.com/rahulmondal779/Anime-Recommendation-System.git
     ```

2. **Install Dependencies:**
   - Make sure you have Python installed on your machine.
   - Install the required Python packages by running the following command in your terminal:
     ```
     pip install pandas numpy matplotlib scikit-learn
     ```

3. **Dataset:**
   - Ensure you have the anime dataset file ("anime.csv") in the project directory. You can find the dataset on [MyAnimeList](https://www.kaggle.com/CooperUnion/anime-recommendations-database).

## Usage

### 1. Preprocessing the Dataset

- Open the `model.ipynb` file in a Jupyter Notebook environment or any Python environment that supports Jupyter Notebooks.
- Run the cells containing the data preprocessing code to clean and transform the dataset.

### 2. Running the Recommendation System

#### For Adults (18+):

- Run the `anime_recommend_adult()` function:
  ```python
  anime_recommend_adult()
  ```
  - Enter the name of your favorite anime when prompted.
  - Enter your age when prompted.
  - Receive recommendations based on your preferences.

#### For All Ages:

- Run the `anime_recommend()` function:
  ```python
  anime_recommend()
  ```
  - Enter the name of your favorite anime when prompted.
  - Receive recommendations based on your preferences.

**Note:** Ensure that you have the necessary Python libraries installed and the dataset file ("anime.csv") available in the project directory.

## Important Information

- The dataset used contains information about various anime, including genres, types, episodes, ratings, and more.
- The recommendation system utilizes Nearest Neighbors algorithm for finding similar animes.
- Adult content (18+) has been filtered out for age-restriction purposes.

**Please Go through the PPT to get a clear view of the project**

Feel free to explore and enjoy your personalized anime recommendations! If you encounter any issues or have suggestions for improvements, please let us know.

Happy watching! 🎉
