# Data-Visualization-and-Exploration-Project

In this project I analyse, visualize and explore the Netflix and IMDB datasets, as well as the Human Activity Recognition dataset.

## Netflix and IMDB

Here, the netflix_titles.csv, which contains movies and TV shows available on the US Netflix is augmented with various IMDB data. This is then cleaned in order to describe, analyse, visualize and gain insights into the popularity of movies and TV shows and the differences between them based on certain categories.

## Human Activity Recognition

This is a well known dataset provided by D. Anguita et. al. (https://archive.
ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones), and is described by the authors as:

"The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING UPSTAIRS, WALKING DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, there- fore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain."

First, initial exploration of this dataset is performed in order to gain initial insights. Thereafter baseline models () are applied to the data in order to gather further insights. From here I try improve these initial baseline models by using feature selection methods. Showing that feature selection is able to drastically improve training times, while maintaining a similar F1-score, I investigate and compare to feature extraction and engineering methods such as PCA, Modified LLE, ISOMAP, and UMAP. A conclusion is provided summarising all the findings and discussing the trade-offs between feature selection and feature engineering in terms of training time, performance, and interpretability.
