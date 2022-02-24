# movie-recommender
The idea behind Content-based (cognitive filtering) recommendation system is to recommend an item based on a comparison between the content of the items and a user profile.
# Project description
By updating the entire status of each movie database,we can predict the movie decision accordingly.so that one could predict which movie is mosted rated.if the movie's viewer count is increasing then the movie review will increases which will be more useful for a new user.this model not only helps the fresh user,it also helps in reducing the man labour work.
# Azure services used
Azure machine learning studio is used to create, train and evaluate the machine learning model. In Azure machine learning portal, select or import a dataset for the model. After uploading the dataset as CSV file, then select the blocks for the model and then connect and visualize the blocks. The final output will be visualized in the evaluated model
# Movie recommender machine learning tool
![image](https://user-images.githubusercontent.com/100063182/155484082-4a0f0a74-8acc-484e-a72b-3169e832062c.png)
# Movie recommender dataset
![image](https://user-images.githubusercontent.com/100063182/155482847-d66bdd7c-1153-4ab6-b264-f18c9c08880a.png)
# Trained model
![image](https://user-images.githubusercontent.com/100063182/155483000-db27f672-e9b8-41d7-9299-64970514368c.png)
# Scored model
![image](https://user-images.githubusercontent.com/100063182/155483254-56891209-92ba-41a2-b746-e76d1c27acdf.png)
![image](https://user-images.githubusercontent.com/100063182/155483840-67273a04-1de5-4e1a-85f5-e9676ebc73b0.png)
![image](https://user-images.githubusercontent.com/100063182/155483919-fcec47db-abc3-47b9-a4ef-08dde4cb97af.png)
# Evaluated model
![image](https://user-images.githubusercontent.com/100063182/155484195-6cb943fd-3921-425d-a9d3-4feeee02abed.png)
![image](https://user-images.githubusercontent.com/100063182/155484322-7c1aef8c-ac9a-4595-9f73-259051dbac1e.png)
![image](https://user-images.githubusercontent.com/100063182/155484415-6f1827ac-c63a-49d9-984e-e8f607eb612e.png)
# Detailed description
Create Project/Experiment and import movie rating data set from saved dataset samples. After creating experiment, we need to drag and drop the required modules in canvas:

DATA SET: Data set required for experiment is added IMDB MOVIE TITLES: This data set consists of movie id and movie names. Editing Metadata: Used to change data type of fields, etc. Join data: Used to join the above two dataset. Select column in dataset: Select columns to inclue or exclude from a dataset in an operation formally known as columns. Remove duplicate rows: Remove the duplicate rows from a dataset. Split data: split the rows of a dataset into two distinct areas,here the dataset is splitted into Train and Score matchbox recommender. Train matchbox recommender: Train a bayesian recommender using the matchbox algorithm. Score matchbox recommender: It scores a dataset using matchbox recommender. Evaluate recommender: this is the final dataset it evaluates and gives the accuracy values this evaluate recommender is used to evaluates a recommender model.

After creating, run the model by clicking run button in the bottom side. After running successfully, we can score and evaluate the model and Deploy the model by Setting up Web Service in ML Studio. For first time select Update Predictive Experiment. after deployment of model, it can be used in webs.
# Demo video
https://user-images.githubusercontent.com/100063182/155485818-d5211898-16cf-42d8-9734-11a18eebe485.mp4



