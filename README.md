# Machine Learnig Project
In this repository, one will find all code and data that we have used for our machine learning project.
In our project, we aimed to find out who are on Dutch Twitter by clustering users based on their biographies and searching for commonalities between them.
<General approach toevoegen (wat is onze baseline en waarom, wat is onze implementatie en waarom)>

## Data
We make use of two data files:
- 'data2021.csv', containing the original data set. Which consists of all Dutch tweets (inclusing metadata) sent between January 1st and December 31th 2021.
- 'data2021_preprocessed.csv', which contains the pre-processed data set. Take a look at 'preprocess.py' for the pre-processing steps that we have taken.

## Code
We separated the code in three files to retain a nice overview. The files are:
- 'preprocessed.ipynb', where one can find all the pre-processing that we have done.
- 'baseline.ipynb', where we carry out our baseline.
- 'MLP.ipynb', where we implement our K-means clusterer and plot the graphs.
