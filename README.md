These projects were completed as part of Udacity's Deep Learning nanodegree. They include: 


## Bike sharing project.

Builds a fully connected neural net from scratch. Trains it on bike-sharing dataset. Uses the result to predict future use.

## Dog breed classification.

Builds and trains a convolutional net to classify dog breeds, or to classify a human face into the "closest" dog breed.

## Generates "Seinfeld" scripts.

Builds an LSTM-base RNN. Trains it on a dataset of "Seinfeld" scripts. Produces a new script.

## Face generation.

Trains and uses a GAN to generate images of faces.

## Sentiment analysis web app.

Using SageMaker, builds and trains an LSTM-based network for sentiment analysis of IMDB review data. 
Deploys the trained model as a web app to perform sentiment analysis of user-input reviews (via SageMaker backend).


#### Note: 

The SageMaker endpoint that the web app uses has been shut down. To redeploy the app one would need to modify the Lambda function to work with new endpoint,  configure a REST  API Gateway to work with the lambda function, and modify index.html to point to the new gateway.  This is explained in the section **Step 7 (again)** of the SageMaker Project notebook file (and in the same section of the report files).
