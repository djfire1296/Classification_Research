# Classification_Research
## Goal
>Find relation to a given specific target.

## Constraints
    Each category value must be boolean or binary value.

## Definitions
    1. y_propotion = count(y) / total_amount
    2. n_propotion = 1 - y_propotion
    3. y_weight = 1 / y_propotion
    4. n_weight = 1 / n_propotion

## Steps
    1. Find each categories' Y propotion of whole database.
    2. Calculate each categories' y_wieght and n_weight.
    3. Calculate each data's score to the target.
    4. Sort score.
    5. Calculate relation.

## Data
- From [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Zoo)
- [zoo_data.csv](https://github.com/djfire1296/Classification_Research/blob/master/zoo_data.csv)

## Data Description
- [zoo_name.txt](https://github.com/djfire1296/Classification_Research/blob/master/zoo_name.txt)