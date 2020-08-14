# project--Deploying-sentiment-analysis-model

<div align="center">
<img src="https://s3.amazonaws.com/video.udacity-data.com/topher/2018/October/5bd36f2f_6-6-project-building-sentiment-analysis-model/6-6-project-building-sentiment-analysis-model.jpg" height="300" width="300" />
<br />
<h1>Deploying a Sentiment Analysis Model</h1>
</div>

## Project Overview

In this project, I have constructed a recurrent neural network to determine the sentiment of a movie review using the IMDB data set. I have created this model using Amazon's SageMaker service. Also, I have deployed my model and constructed a simple web app which will interact with the deployed model. The prediction model is implemented in PyTorch and deployed to AWS SageMaker.   
To serve it on a web page, I call the SageMaker model from a AWS Lambda service, which can be accessed via API Gateway.

## SageMaker Deployment Project

The notebook and Python files provided here, once completed, result in a simple web app which interacts with a deployed recurrent neural network performing sentiment analysis on movie reviews. This project assumes some familiarity with SageMaker, the mini-project, Sentiment Analysis using XGBoost, should provide enough background.

Please see the [README](https://github.com/udacity/sagemaker-deployment/tree/master/README.md) in the root directory for instructions on setting up a SageMaker notebook and downloading the project files (as well as the other notebooks).


## What is it?

It's a deployed web page which defines sentiment of a movie review.  

Below are results for some reviews for "[Au service de la France](https://www.imdb.com/title/tt4367560/reviews?ref_=tt_urv)":

---

![Positive review](https://github.com/iamRishabh07/project--Deploying-sentiment-analysis-model/blob/master/screenshots/PositiveReview2.png)

---

![Negative review](https://github.com/iamRishabh07/project--Deploying-sentiment-analysis-model/blob/master/screenshots/NegativeReview1.png)


## Authors

* Rishabh Srivastava

## License

[MIT](https://choosealicense.com/licenses/mit/)
