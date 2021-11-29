### Recomender Systems using Python 
- Collaborative Filtering 
- Content Based Filteirng

This project was created for demo purposes for MIS 753 - Independant study class that I took in Fall 2021 on Recommender Systems. 

The porpose of this project is to provide an introduction to recommender systems using the python programming language. The specific emphasis is given to collaborative filtering and content based filtering.
Within the repo you can find 2 jupyter notebooks (one for each topic). 

Each notebook goes through data cleaning, text processing, text vectorization, modeling and recommendation generation. 

### Data
- The main data source for this project is: yelp open dataset - https://www.yelp.com/dataset
- This dataset contains inforamtion about 160,000 businessess and 0ver 8 mission customer reviews for those businessess. 
- This dataset contains 5 json files (business, tip, reviews, user, checkin). 
- I downloaded all of these files and queried these files using mongoDb and Studio3T. 
- I then created subsets of these datasets via sql queries on Studio3T and saved subsets of the data using Stuidio3T as csv files. 
- ***business.csv*** file contains information about restaurants and reviews. 
- ***business250k.csv*** file contains information about 250k reataurents and their reviews. 
- All data files can be found in the Data directory of the repo. 

### Jupyter Notebooks
- The repo contans 2 jupyter notebooks, 
- One for collaborative filtering - dataset used: business.csv
- The second for content based filtering - dataset used: business250k.csv

### Sources: 
- I refered to several sources to assist me in the coding and ideation process. 
- Some of the code in sections, such as data cleaning, word cloud generation, and modeing is copied from several sources. 
- These sources can be founf below: 
  - https://predictivehacks.com/item-based-collaborative-filtering-in-python/
  - https://chrisalbon.com/code/machine_learning/feature_engineering/select_best_number_of_components_in_tsvd/
  - https://realpython.com/build-recommendation-engine-collaborative-filtering/
  - https://medium.com/mlearning-ai/content-based-recommender-system-using-nlp-445ebb777c7a
  - https://towardsdatascience.com/tf-idf-for-document-ranking-from-scratch-in-python-on-real-world-dataset-796d339a4089
  - https://towardsdatascience.com/nlp-text-data-visualization-5d5c64c86019
