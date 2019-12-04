# Deploying a Sentiment Analysis Model with SageMaker

## Project Overview
I built a simple web page which a user can use to enter a movie review. The web page will then send the review off to the deployed recurrent neural network which will predict the sentiment of the entered review.

## Key Skills Demonstrated
- Text analysis
- Model deployment via SageMaker
- APIs for web deployment

## Data

I used the [IMDb dataset](http://ai.stanford.edu/~amaas/data/sentiment/)

> Maas, Andrew L., et al. [Learning Word Vectors for Sentiment Analysis](http://ai.stanford.edu/~amaas/data/sentiment/). In _Proceedings of the 49th Annual Meeting of the Association for Computational Linguistics: Human Language Technologies_. Association for Computational Linguistics, 2011.

## Project Steps
The project is documented in [sentiment_analysis_rnn.ipynb](https://github.com/iDataist/Deploying-a-Sentiment-Analysis-Model-with-SageMaker/blob/master/sentiment_analysis_rnn.ipynb). Below are the steps.

1. Download the IMDb dataset.
2. Preparing and Processing the data.
3. Upload the processed data to S3.
4. Train a recurrent neural network model.
5. Deploy the model.
6. Test the trained model.
7. Deploy the model for the web app.

## Project Output
<img src="App Test 1.png">
<img src="App Test 2.png">
