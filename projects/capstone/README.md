# Machine Learning Engineer Nanodegreee

## Capstone Project

### New York City Taxi Trip Duration 

The goal of this project is to present a solution for the Kaggle's playground competition [New York City Taxi Trip Duration](https://www.kaggle.com/c/nyc-taxi-trip-duration) which will be used as the capstone project of the [Machine Learning Engineer Nanodegree](https://udacity.com/course/machine-learning-engineer-nanodegree--nd009) by [Udacity](https://br.udacity.com/).

### Dataset

After accepting [Kaggle's Terms](https://www.kaggle.com/terms), the data can downloaded from two zip files, one containing the [training dataset](https://www.kaggle.com/c/6960/download/train.zip) and other the [testing dataset](https://www.kaggle.com/c/6960/download/test.zip). Additionally, a [sample submission file](https://www.kaggle.com/c/6960/download/sample_submission.zip) is provided.

File descriptions

- `train.csv` - the training set (contains 1458644 trip records)
- `test.csv` - the testing set (contains 625134 trip records)
- `sample_submission.csv` - a sample submission file in the correct format

Data fields

- `id` - a unique identifier for each trip
- `vendor_id` - a code indicating the provider associated with the trip record
- `pickup_datetime` - date and time when the meter was engaged
- `dropoff_datetime` - date and time when the meter was disengaged
- `passenger_count` - the number of passengers in the vehicle (driver entered value)
- `pickup_longitude` - the longitude where the meter was engaged
- `pickup_latitude` - the latitude where the meter was engaged
- `dropoff_longitude` - the longitude where the meter was disengaged
- `dropoff_latitude` - the latitude where the meter was disengaged
- `store_and_fwd_flag` - This flag indicates whether the trip record was held in vehicle memory before sending to the vendor because the vehicle did not have a connection to the server -`Y`=store and forward; `N`=not a store and forward trip
- `trip_duration` - duration of the trip in seconds

### Requirements

- [`python`](https://www.python.org/downloads/release/python-360/) 3.x*
- [`numpy`](www.numpy.org/)*
- [`pandas`](https://pandas.pydata.org/)*
- [`scikit-learn`](scikit-learn.org/)*
- [`matplotlib.pyplot`](https://matplotlib.org/api/pyplot_api.html)*
- [`plotly`](https://plot.ly/)
- [`mglearn`](https://github.com/amueller/mglearn)

The items marked with * are available in [Anaconda](https://anaconda.org/). 


