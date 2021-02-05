# Table of content

1. [Libraries](#lib)
2. [Project Motivation](#pm)
3. [File Description](#fd)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licesing)


## Libraries <a name="lib"></a>
The libraries used in this project:

- pyspark
  - pyspark.sql
  - pyspark.ml
- matplotlib
- seaborn

## Project Motivation <a name="pm"></a>
The project goal is predict the churn of music listeners (customers) using the
big data tool Spark due to its volume size.

## File Description <a name="fd"></a>
The files in this repository are structred as follows:

- Sparkify.ipynb
  - The notebook containing the code for data exploration, feature engineering,
  and modelling.
- mini_sparkify_event_data.json.zip
  - The data file 
- LICENSE
  - The MIT license file for this project.


## Results <a name="results"></a>

The performance of the models are evaluated using test Accuracy and F1 score. The best performing model was the logistic regression model based on the F1 score of 0.616. The metrics of the all the models after 2-folds cross-validation. 

The main findings of the code can be found at the post available [here.](https://raghad-a-otaibi.medium.com/prediction-of-music-listeners-churn-1874ace06318)

## Licensing, Authors, and Acknowledgements <a name="licensing"></a>

This project is part of the [Udacity](https://www.udacity.com) Data Scientist Nanodegree program.

The dataset is provided from [Udacity](https://www.udacity.com)

The contents of this repository are covered under the [MIT License.](https://github.com/Raghadd7/capstone-project/blob/main/LICENSE)
