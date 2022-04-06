![Language](https://img.shields.io/badge/language-Python%20-blue.svg)
![License](https://img.shields.io/badge/License-MIT%20-red.svg)

# Images Segmentation
## What is this ?
This is a study of the use of K-means and Normalized cut using KNN with k = 5  on the Berkeley Segmentation Benchmark.

## Tunning
The tuning was done on 200 images of the training set to get the best k between {3,5,7,9,11} which is K=3 according to F-measure.
We used the best k to test our algorithm using 50 images of the test set.

## Sample Images
![image](https://user-images.githubusercontent.com/58489322/161772648-17641284-772d-44c0-9d15-4485be20eb52.png)
![image](https://user-images.githubusercontent.com/58489322/161773045-ea346616-9509-42ea-ada5-9a0b48119585.png)

## The Data
To downoad the original used data use this link : http://www.eecs.berkeley.edu/Research/Projects/CS/vision/grouping/BSR/BSR_bsds500.tgz
