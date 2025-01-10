# Movie Recommender System

This project implements a Movie Recommender System using collaborative filtering techniques. The system predicts user preferences for movies based on historical data of user ratings and movie information.

## Features

- **Movie Recommendation**: Suggests movies to users based on their past preferences.
- **Collaborative Filtering**: Uses user-item interaction data to generate recommendations.
- **Data Visualization**: Provides insights into the dataset and user behavior.

## Dataset

### 1. `Movie_Id_Titles.csv`

- This file contains mappings between movie IDs and their corresponding titles.
- Example:
  ```
  item_id              title
  1        Toy Story (1995)
  2        GoldenEye (1995)
  3        Four Rooms (1995)
  4        Get Shorty (1995)
  5        Copycat (1995)
  ```

### 2. `file.tsv`

- This file includes user interaction data such as user IDs, movie IDs, ratings, and timestamps.
- Example:
  ```
      user_id  movie_id  rating  timestamp
      0       50        5       881250949
      0      172        5       881250949
      0      133        1       881250949
    196      242        3       881250949
    186      302        3       891717742
  ```

## Requirements

To run the project, you need the following:

- Python 3.x
- Jupyter Notebook
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

You can install the required libraries using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage

1. Clone the repository and navigate to the project directory:

   ```bash
   git clone <repository_url>
   cd movie-recommender-system
   ```

2. Ensure the dataset files (`Movie_Id_Titles.csv` and `file.tsv`) are in the project directory.

3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook Python___Implementation_of_Movie_Recommender_System.ipynb
   ```

4. Run the notebook cells step by step to:

   - Load and preprocess the dataset.
   - Train the recommender model.
   - Generate recommendations.

## Project Workflow

1. **Data Loading**:

   - Load user interaction data (`file.tsv`) and movie metadata (`Movie_Id_Titles.csv`).

2. **Data Preprocessing**:

   - Clean and prepare the data for modeling.

3. **Model Building**:

   - Implement collaborative filtering techniques to predict user ratings for movies.

4. **Evaluation**:

   - Assess the model's performance using metrics such as RMSE.

5. **Recommendation Generation**:

   - Generate personalized recommendations for users.

## File Descriptions

- `Python___Implementation_of_Movie_Recommender_System.ipynb`: The main implementation of the project.
- `Movie_Id_Titles.csv`: Metadata file mapping movie IDs to titles.
- `file.tsv`: User interaction data (e.g., ratings and timestamps).

## Results

The recommender system provides accurate and relevant movie suggestions by leveraging user preferences and interaction data. Insights from the dataset visualization help understand user behavior and movie popularity trends.

## Future Enhancements

- Add support for content-based filtering.
- Improve scalability to handle larger datasets.
- Integrate with a web interface for user interaction.



