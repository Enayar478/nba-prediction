# NBA Win Rating Prediction

This project uses machine learning to predict NBA players' "Win Rating" based on their game statistics. It demonstrates data preprocessing, exploratory data analysis, and linear regression modeling using Python and popular data science libraries.

## Dataset Description

The dataset contains statistics for 4000 NBA players, including:

- `season`: The season (yearly) the player played in
- `poss`: Possessions played
- `mp`: Minutes played
- `do_ratio`: A player's ratio of time spent in defense vs. offense; negative values mean more defense positioning
- `pacing`: Player impact on team possessions per 48 minutes
- `win_rating`: Wins Above Replacement rating, how many additional wins a player is worth over a same-level replacement

## Features

1. Data loading and preprocessing
2. Exploratory data analysis
3. Data preparation for modeling (train/test split, scaling)
4. Training a linear regression model
5. Model evaluation
6. Performance comparison with different feature sets
7. Prediction for a new player

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Installation

To run this project, you need to install the following dependencies:

```
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Usage

1. Clone this repository
2. Ensure the 'NBA.csv' data file is in the same directory as the notebook
3. Open and run the Jupyter notebook '2_Your_first_Regression_Challenge.ipynb'

## Results

The final model using multiple features (`poss`, `mp`, `do_ratio`, `pacing`) achieved an R² score of 0.64 on the test set, which is a significant improvement over the single-feature model.

## Contributing

Contributions to this project are welcome. Please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
