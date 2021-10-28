<!--- [![Build Status](https://dev.azure.com/davidsmi0786/davidsmiRtest/_apis/build/status/revodavid.RMLops?branchName=master)](https://dev.azure.com/davidsmi0786/davidsmiRtest/_build/latest?definitionId=1&branchName=master)
--->
# Machine Learning Operations

When deploying machine learning models, it is useful to create portable, efficient, automated code. Using Docker and popular languages R and Python, I am creating trainable models using Docker and Amazon Web Serivices. These examples are recreated from existing resources with credit attributed.

## PyMLops: A Complete Guide for Docker Beginners

This is a Github repostitory following along Tina Bu's [Build a Docker Container with Your Machine Learning Model](https://towardsdatascience.com/build-a-docker-container-with-your-machine-learning-model-3cf906f5e07e) to create a Docker instance in AWS. This is a beginner example of how to use AWS and Python to train a machine learning model.

## RMLops: A simple R example for Azure Pipelines

This is the Github repository associated with this Azure Pipelines project: https://dev.azure.com/davidsmi0786/davidsmiRtest. It is intended as a simple example
of using R with ~~Azure Pipelines to use a CI/CD process to trigger training of a
predictive model.~~ Docker to create a playlist generator using Spotify datasets.

## Model Contents

The model I will be porting is a Spotify dataset (my own. Don't worry I have excellent taste) containing my streaming history, sorted into the best possible playlists using K-nearest neighbors. I will let you know which ones are the best. If you would like to know for yourself, use this model to design your own playlists.



### Presentations

Slides from the presentation [A DevOps process for deploying R to production](https://github.com/revodavid/RMLops/blob/master/earl2019slides.pdf) are available. Presented at the [EARL 2019 conference](http://www.earlconf.com/) in London, September 11 2019.

Slides from the presentation [A DevOps process for deploying R to production](https://github.com/revodavid/RMLops/blob/master/user2019slides.pdf) are available. Presented at the [useR!2019 conference](http://www.user2019.fr/) in Toulouse, July 12 2019. A [video recording](https://youtu.be/o6sIB0MJyOs) of this presentation is available.

### Resources

[Integrating the Data Science and App Development Cycles](https://aka.ms/AA5ib6c) (Medium), Francesca Lazzeri, Microsoft. 

[MLOps: Manage, deploy, and monitor models with Azure Machine Learning Service](https://aka.ms/mlopsdoc) (Microsoft Docs).  

[Train and deploy machine learning models with Azure Pipelines](https://aka.ms/azpipe) (Microsoft Docs). 

[Azure Machine Learning Service](https://aka.ms/amlsvc) (Microsoft Docs). 

[Build a Docker Container with Your Machine Learning Model](https://towardsdatascience.com/build-a-docker-container-with-your-machine-learning-model-3cf906f5e07e)

#### Development Details

Developed in RStudio using Quarto and Jupyter Notebooks.
