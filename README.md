## Kaggle TMDB Box Office Prediction
**Building a model to predict the box office figures for movies using the Random Forest algorithm.**

### The solution notebook (R) is available [here](https://meenal-narsinghani.github.io/Kaggle-TMDB-BO-Prediction/Kaggle-TMDB_BO_Prediction.html).

![Test](https://i.imgur.com/nCUVhIO.jpg)


#### Background & Problem Description

In a world where movies made an estimated $41.7 billion in 2018, the film industry is more popular than ever. But what movies make the most money at the box office? How much does a director matter? Or the budget?

In this competition hosted by [**Kaggle**](https://www.kaggle.com/c/tmdb-box-office-prediction), we were presented with metadata on over 7,000 past films from The Movie Database to try and predict their overall worldwide box office revenue. Data points provided include cast, crew, plot keywords, budget, posters, release dates, languages, production companies, and countries. Only the data that is available before a movie's release is used to implement the model.

#### Data Source

The data is made available by the famous [**The Movie Database**](https://www.themoviedb.org/?language=en-US). 

Two data files [train.csv](train.csv) and [test.csv](test.csv) were provided as part of this competition - 

  * **Training Dataset:** In this dataset, information on 7398 movies and a variety of metadata obtained from The Movie Database (TMDB) is provided. Movies are labeled with id. Data points include cast, crew, plot keywords, budget, posters, release dates, languages, production companies, and countries.

  * **Testing Dataset:** Predcition of worldwide revenue is to be done for 4398 movies provided in this test file.

*Additionally a third file [sample_submission.csv](sample_submission.csv) was availavle that provides the structure of the solution file to be submitted.*

More details can regarding the data can be found [here](https://www.kaggle.com/c/tmdb-box-office-prediction/data).

#### Analytical Approach
The [R notebook](https://meenal-narsinghani.github.io/Kaggle-TMDB-BO-Prediction/Kaggle-TMDB_BO_Prediction.html) shows the end-to-end analytical process (described below) and its implementation to address this business problem -
 
 1. Intial Setup & Loading the data
 2. Feature Engineering
 3. Exploratory Data Analysis
 4. Missing Values treatment
 5. Analytical Dataset creation
 6. Model Building
 7. Prediction on Test dataset

#### Evaluation

For each movie (id) available in the test data set, international box office revenue had to be predicted. Submissions were evaluated on Root-Mean-Squared-Logarithmic-Error (RMSLE) between the predicted value and the actual revenue.

I took up this competition to practice and polish my analytical skills. As the competition was over long ago, I could not make it to the public leaderboard.







