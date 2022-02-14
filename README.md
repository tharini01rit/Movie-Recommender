# Movie-Recommender
The idea behind Content-based (cognitive filtering) recommendation system is to recommend an item based on a comparison between the content of the items and a user profile.In simple words,I may get recommendation for a movie based on the description of other movies
# Project description
By updating the entire status of each movie database,we can predict the movie decision accordingly.so that one could predict which movie is mosted rated.if the movie's viewer count is increasing then the movie review will increases which will be more useful for a new user.this model not only helps the fresh user,it also helps in reducing the man labour work.
# Azure services used
Azure machine learning studio is used to create, train and evaluate the machine learning model. In Azure machine learning portal, select or import a dataset for the model. After uploading the dataset as CSV file, then select the blocks for the model and then connect and visualize the blocks. The final output will be visualized in the evaluated model
# Movie recommender machine learning model
![image](https://user-images.githubusercontent.com/89441844/152938114-44e83dc8-5418-4a2e-a28b-c883ada97a0f.png)
# Movie recommender dataset
![image](https://user-images.githubusercontent.com/89441844/152938271-935edd2b-0255-4df2-a000-3a29dfe3ff00.png)
# Trained model
![image](https://user-images.githubusercontent.com/89441844/152938447-f951048b-7ce6-4328-853b-5d4724524869.png)
# Scored model
![image](https://user-images.githubusercontent.com/89441844/152938567-5e544aae-0db5-4f4f-a5bd-73f09416ca6d.png)
![image](https://user-images.githubusercontent.com/89441844/152938672-ff83791f-67d6-4ebb-9c42-69b3c50f4a00.png)
![image](https://user-images.githubusercontent.com/89441844/152938810-fdc41552-401e-4c73-b386-1c8bc1f1eb49.png)
# Evaluated model
![image](https://user-images.githubusercontent.com/89441844/152938950-3f7103e9-d130-45bb-a986-0a1c356f22cc.png)
![image](https://user-images.githubusercontent.com/89441844/152939013-186cfb8a-2ae4-4769-a4a6-3c77878a9d6f.png)
![image](https://user-images.githubusercontent.com/89441844/152939091-ab6f8a72-21bc-4a07-b669-7161a42d877f.png)
# Detailed description
Create Project/Experiment and import movie rating data set from saved dataset samples. After creating experiment, we need to drag and drop the required modules in canvas:

DATA SET:
  Data set required for experiment is added
IMDB MOVIE TITLES:
  This data set consists of movie id and movie names.
Editing Metadata:
  Used to change data type of fields, etc.
Join data:
  Used to join the above two dataset.
Select column in dataset:
  Select columns to inclue or exclude from a dataset in an operation formally known as columns.
 Remove duplicate rows:
  Remove the duplicate rows from a dataset.
Split data:
  split the rows of a dataset into two distinct areas,here the dataset is splitted into Train and Score matchbox recommender.
Train matchbox recommender:
  Train a bayesian recommender using the matchbox algorithm.
Score matchbox recommender:
  It scores a dataset using matchbox recommender.
Evaluate recommender:
  this is the final dataset it evaluates and gives the accuracy values 
  this evaluate recommender is used to evaluates a recommender model.

After creating, run the model by clicking run button in the bottom side. After running successfully, we can score and evaluate the model and Deploy the model by Setting up Web Service in ML Studio. For first time select Update Predictive Experiment. after deployment of model, it can be used in webs.
# project link
https://gallery.cortanaintelligence.com/Experiment/Movie-recommender-prediction
# Demo video
https://user-images.githubusercontent.com/89441844/153903322-7f1589bc-2acf-438a-8523-769c551ccf89.mp4




