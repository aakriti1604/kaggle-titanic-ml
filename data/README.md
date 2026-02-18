This folder contains raw datasets and intermediate data files.


Files:

- train.csv → Training dataset containing passenger features and survival labels.
- test.csv  → Test dataset used for generating predictions.

Key Features:

- Survived → Target variable (0 = No, 1 = Yes)
- Pclass   → Passenger class (proxy for socioeconomic status)
- Sex      → Passenger gender
- Age      → Passenger age (contains missing values)
- Fare     → Ticket fare (skewed distribution)

Other Features:

- sibsp    → # of siblings / spouses aboard the Titanic
- parch	   → # of parents / children aboard the Titanic
- embarked → Port of Embarkation	C = Cherbourg, Q = Queenstown, S = Southampton

Notes:

- Missing values present in Age and Cabin
- Feature engineering and preprocessing handled in notebooks/

