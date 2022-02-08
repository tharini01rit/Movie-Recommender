# Movie-Recommender
The idea behind Content-based (cognitive filtering) recommendation system is to recommend an item based on a comparison between the content of the items and a user profile.In simple words,I may get recommendation for a movie based on the description of other movies
# Project description
By updating the entire status of each movie database,we can predict the movie decision accordingly.so that one could predict which movie is mosted rated.if the movie's viewer count is increasing then the movie review will increases which will be more useful for a new user.this model not only helps the fresh user,it also helps in reducing the man labour work.
# Azure services used
Azure machine learning studio is used to create, train and evaluate the machine learning model. In Azure machine learning portal, select or import a dataset for the model. After uploading the dataset as CSV file, then select the blocks for the model and then connect and visualize the blocks. The final output will be visualized in the evaluated model
# Movie recommender macine learning model
![image](https://user-images.githubusercontent.com/89441844/152484760-6f77886b-18c4-44d4-a1a2-810fa1862df3.png)
# Movie recommender dataset
![image](https://user-images.githubusercontent.com/89441844/152484134-6e8e63c6-0841-4c20-b107-d8579297a587.png)
# Trained model
![image](https://user-images.githubusercontent.com/89441844/152484293-db05781b-a87c-45f9-b8f6-f82bc925b678.png)
# Scored model
![image](https://user-images.githubusercontent.com/89441844/152484465-4b902fb1-e195-4ba1-8d34-f6f07fce6485.png)
![image](https://user-images.githubusercontent.com/89441844/152484557-1015c847-cb4b-4c49-bfd6-bc0b7b2a533c.png)
![image](https://user-images.githubusercontent.com/89441844/152484641-f901e757-7f23-4e94-9049-8733664a4463.png)
# Evaluated model
![image](https://user-images.githubusercontent.com/89441844/152484862-65205ebd-267e-45d5-ac2c-618b6c19d518.png)
![image](https://user-images.githubusercontent.com/89441844/152484904-27ac0ee3-7e89-4531-a59e-647a329dad26.png)
![image](https://user-images.githubusercontent.com/89441844/152484959-12c73ae7-d71a-47ae-b8c8-1d4ec15a4e57.png)
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
 # Project link
 https://gallery.cortanaintelligence.com/Experiment/Movie-recommender-prediction
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

