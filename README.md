<a href="#"><img width="100%" height="auto" src="https://i.imgur.com/iXuL1HG.png" height="175px"/></a><br>

<h1 align="center">Hi , <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="30px"> I'm Thrishul Kumar</h1>
<h3 align="center">I'm a passionate be a Data Scientist from India <img align="center"src="https://img.icons8.com/color/23/000000/india-circular.png"/>



<br><br>

<img alt= "project icon" src="https://img.icons8.com/nolan/128/project-setup.png"/>
<br><br><br><br>

 # <h1>**Hit Predict<img align="top" src="https://img.icons8.com/nolan/36/explosion.png"/> : Predicting Billboard Hits Using Spotify Data**

## <h3 align=center>The Billboard Hot 100 Chart1 remains one of the definitive ways to measure the 🚀success of a popular song. We investigated using machine learning techniques to predict which songs will become Billboard Hot🔥100 Hits.
<br>


  
  <br>

# <h1><img align="center" src="https://img.icons8.com/nolan/56/database.png"/>  **Dataset - Spotify Data** <img src="https://img.icons8.com/color/30/000000/spotify--v3.png" align="center"/> 


##### <img align="center" src="https://img.icons8.com/color/13/000000/sphere.png"/> Data for ~10,000 songs were collected from Bilboard.com and Millions Songs Dataset. Songs were from 1990-2018
##### <img align="center" src="https://img.icons8.com/color/13/000000/sphere.png"/> Songs were labeled either 0 or 1 based on Bilboard
##### <img align="center" src="https://img.icons8.com/color/13/000000/sphere.png"/> Audio Features for each song were extracted from the Spotify web API
##### <img align="center" src="https://img.icons8.com/color/13/000000/sphere.png"/> K-Nearest Neighbour Classifier is used to predict the song's Billboard success   
<br>

# <h1><img align="center" src="https://img.icons8.com/nolan/64/service.png"/> **Features of the Song** 
<img align="center"src="https://img.icons8.com/nolan/30/musical-notes.png"/></h1>

##### <img align="center" src="https://img.icons8.com/fluency/15/000000/christmas-star.png"/> ***Danceability*** :&emsp;Describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity.<br>

##### <img align="center" src="https://img.icons8.com/fluency/15/000000/christmas-star.png"/> ***Energy***   :&emsp;Represents a perceptual measure of intensity and activity. Typically, energetic tracks feel fast, loud, and noisy. For example, death metal has high energy, while a Bach prelude scores low on the scale.

##### <img align="center" src="https://img.icons8.com/fluency/15/000000/christmas-star.png"/> ***Loudness***   : An attribute of auditory sensation in terms of which sounds can be ordered on a scale extending from quiet to loud.

##### <img align="center" src="https://img.icons8.com/fluency/15/000000/christmas-star.png"/> ***Speechiness***   :&emsp; Detects the presence of spoken words in a track.If the speechiness of a song is above 0.66, it is probably made of spoken words, a score between 0.33 and 0.66 is a song that may contain both music and words (e.g. rap music), and a score below 0.33 means the song does not have any speech.

##### <img align="center" src="https://img.icons8.com/fluency/15/000000/christmas-star.png"/> ***Acousticness***   :&emsp; A confidence measure from 0.0 to 1.0 of whether the track is acoustic. 1.0 represents high confidence the track is acoustic.

##### <img align="center" src="https://img.icons8.com/fluency/15/000000/christmas-star.png"/> ***Instrumentalness***   : &emsp;Predicts whether a track contains no vocals. “Ooh” and “aah” sounds are treated as instrumental in this context. Rap or spoken word tracks are clearly “vocal.” The closer the instrumentalness value is to 1.0,the greater likelihood the track contains no vocal content.

##### <img align="center" src="https://img.icons8.com/fluency/15/000000/christmas-star.png"/> ***Liveness***   :&emsp; This value denotes the probability that the song is recorded with a live audience. According to the official documentation, “a value above 0.8 provides a strong likelihood that the track is live”.

##### <img align="center" src="https://img.icons8.com/fluency/15/000000/christmas-star.png"/> ***Valence***  :&emsp;A measure from 0.0 to 1.0 describing the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative.

##### <img align="center" src="https://img.icons8.com/fluency/15/000000/christmas-star.png"/> ***Tempo***   :&emsp;Tempo is how fast or slow a piece of music is performed, while rhythm is the placement of sounds in time, in a regular and repeated pattern.

##### <img align="center" src="https://img.icons8.com/fluency/15/000000/christmas-star.png"/> ***Genre***   :&emsp; A music genre is a conventional category that identifies some pieces of music as belonging to a shared tradition or set of conventions. It is to be distinguished from musical form and musical style.

<br><br>

# <h1><img align="center" src="https://img.icons8.com/fluency/58/000000/statistics.png"/> **Exploratory Data Analysis - EDA**

####  <img align="center" src="https://img.icons8.com/color/13/000000/sphere.png"/>  &emsp; The Billboard Hot 100 Chart1 remains one of the definitive ways to measure the success of a popular song. We investigated using machine learning techniques to predict which songs will become Billboard Hot 100 Hits.
<br>

##  <img align="center" src="https://img.icons8.com/color/13/000000/sphere.png"/>&emsp;**Box-Plot for Release Year**<br><br>
&emsp;&emsp;&emsp;![Capture1](https://user-images.githubusercontent.com/79398894/129721608-f595b11d-71c7-4b3e-8cae-566356221a01.PNG)

##  <img align="center" src="https://img.icons8.com/color/13/000000/sphere.png"/>&emsp;**Heat Map to Study Correlation**<br><br>&emsp;&emsp;![Capture2](https://user-images.githubusercontent.com/79398894/129723023-1399d234-f4e3-409a-88c0-450e057c1288.PNG)<br>
 - The Heatmap showed that there is good positive correlation between Loudness and Energy. While Acoustiness and Energy are negatively correlated. Also there is negative correlation between Loudness and Acoustiness.<br>

##  <img align="center" src="https://img.icons8.com/color/13/000000/sphere.png"/>&emsp;**Scatter plot for Loudness and Acousticness**<br><br>&emsp;&emsp;![Capture3](https://user-images.githubusercontent.com/79398894/129724014-33e30a79-8941-41ec-87d9-97d71d1505a5.PNG)<br>
 - Scatter plot shows that loud songs with High Energy makes up on the billboard Top100.<br><br>
  
  ##  <img align="center" src="https://img.icons8.com/color/13/000000/sphere.png"/>&emsp;**Genre Classification on Billboard Top100**<br><br>&emsp;&emsp;![Capture4](https://user-images.githubusercontent.com/79398894/129724263-b9b4b567-1bcc-4a9d-8869-24ef2dc1d4f3.PNG)<br><br>
   -  Most of the songs on Billboard are of 'Pop' Genre followed by 'Rap'. It may be because songs of these Genre are released mostly. The songs of genre 'Jazz','reggae','alternative','classical','edm' doesnot make up on Billboard.
   -  After performing basic EDA we moved to modelling part. For building the model we used Danceability, Energy, Loudness, Speechiness, Acousticness, Instrumentalness,Liveness, Valence, Tempo and Genre as our Feature variables. While Top100 is target variable.<br><br>
  
  ##  <img align="center" src="https://img.icons8.com/color/13/000000/sphere.png"/>&emsp;**Steps taken to apply KNN algorithm**<br><br>
   1) Balancing the data using **SMOTE** technique.

   1) Scaling the independent features using StandardScalar().
   
   2) Splitting the data in train-test split, 80% for training purpose and 20% for testing purpose.
   
   3) Fitting the train data using **KNN** algorithm.
   
   4) Model Evaluation using Confusion matrix and ROC-AUC curve.
   
   5) Hyper-parameter tuning to obtain optimized scores.
   
   6) Evaluating the optimized model
  <br>
  
  ##  <img align="center" src="https://img.icons8.com/color/13/000000/sphere.png"/>&emsp;**Scores without Hyper-Parameter Tuning**<br><br>
  &emsp;&emsp; **Scores of initial model:**

  - **Accuracy:** 76 %

  - **Precision:** 77 %

  - **Recall:** 76 %

  - **ROC AUC Score:** 76.13 %<br><br>
##  <img align="center" src="https://img.icons8.com/color/13/000000/sphere.png"/>&emsp;**Classification Report**<br><br>
&emsp;&emsp;![knn_cr](https://user-images.githubusercontent.com/79398894/128306715-e1149037-a723-44af-b77b-069dfd14f17a.PNG)<br>
##  <img align="center" src="https://img.icons8.com/color/13/000000/sphere.png"/>&emsp;**AUC-Curve**<br><br>
&emsp;&emsp;![auc_knn](https://user-images.githubusercontent.com/79398894/128306840-afb5ab54-5186-4a48-ae91-9ad059209dd4.PNG)<br><br>

##  <img align="center" src="https://img.icons8.com/color/13/000000/sphere.png"/>&emsp;**Optimized KNN With Hyperparameter Tuning**<br><br>
&emsp;&emsp;<br>
&emsp;&emsp; **Scores of optimized model:**

  - **Accuracy:** 80 %

  - **Precision:** 82 %

  - **Recall:** 80 %

  - **ROC AUC Score:** 79.59 %<br><br>
  
  ##  <img align="center" src="https://img.icons8.com/color/13/000000/sphere.png"/>&emsp;**Classification report for KNN after Hyperparametyer tuning**<br><br>
  &emsp;&emsp;![Classification Report](https://user-images.githubusercontent.com/79398894/128154421-7f4637ec-f64f-4e6f-9752-dfea72716fca.PNG)<br>
  ##  <img align="center" src="https://img.icons8.com/color/13/000000/sphere.png"/>&emsp;**AUC curve obtained for optimized KNN model**<br><br>
  &emsp;&emsp;![AUC curve](https://user-images.githubusercontent.com/79398894/128154503-c5286e2f-4bb0-479a-9e5d-2f648d8e003d.PNG)<br>
<br>
<br>
<br>


# <img align="center" src="https://img.icons8.com/nolan/64/rocket.png"/>**Deployment** 

   <img align="center" src="https://img.icons8.com/color/13/000000/sphere.png"/> **Finally deployed the model on Heroku using Flask.**

 <img align="center" src="https://img.icons8.com/color/13/000000/sphere.png"/> **The screenshot of the app and link is attached below.**

 
 &emsp; **Link:** https://hit-prediction.herokuapp.com/

