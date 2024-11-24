# Baseline-Model-for-Anime-Recommendation-System-Using-Wide-and-Deep-Learning
### Overview
This project implements a baseline anime recommendation system using a wide-and-deep learning model. The system predicts user ratings for anime based on embeddings for users, anime, and genres. The goal is to establish a benchmark for recommendation accuracy while exploring the potential of deep learning for personalization tasks.
### Dataset Link:
https://www.kaggle.com/datasets/dbdmobile/myanimelist-dataset
### Model Architecture
The model follows a wide-and-deep architecture:
Wide Component: Captures cross-product feature interactions directly.
Deep Component: Learns non-linear transformations of input features using embeddings for users, anime, and genres.
### Key Features:
Embedding Dimensions:
* Users: 16
* Anime: 16
* Genres: 8
* Optimizer: Adam with a learning rate of 0.0005
* Loss Function: Mean Squared Error (MSE)
* Epochs: 20
Training loss decreased consistently from 1.7980 to 1.3792, showcasing effective learning.
### Observations:
The model demonstrates reasonable accuracy for a baseline.
A test RMSE of 1.3105 indicates that the model is moderately accurate but has room for improvement.

Reference Paper: https://arxiv.org/pdf/1606.07792 
![The spectrum of Wide & Deep models](https://github.com/SaikiranBSK10/Baseline-Model-for-Anime-Recommendation-System-Using-Wide-and-Deep-Learning/blob/main/1.PNG)

