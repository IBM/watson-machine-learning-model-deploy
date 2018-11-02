
# Short title

Predict Heart Medicine Using Machine Learning

# Long title

Use machine learning with anonymous patient data to predict the best drug to treat heart discease.

# Authors

* Lukasz Cmielowski lukasz.cmielowski@pl.ibm.com

# URLs

### Github repo

> "Get the code": Provide the link to GitHub repo for the code.

* https://github.com/IBM/prediction-using-watson-machine-learning

# Summary

> **DISCLAIMER**: This notebook is used for demonstrative and illustrative purposes only and does not constitute an offering that has gone through regulatory review. It is not intended to serve as a medical application. There is no representation as to the accuracy of the output of this application and it is presented without warranty.

In this Code Pattern, we will use anonymous patient data to predict the best drug to treat heart disease. This notebook introduces commands for getting data, building the model, model deployment, and scoring.

When the reader has completed this Code Pattern, they will understand how to:

* Prepare data, create an Apache Spark machine learning pipeline, and train a model.
* Publish a sample model in the Watson Machine Learning (WML) repository.
* Deploy a model for online scoring (as a web service).
* Score the model using sample scoring records and the scoring endpoint.

# Technologies

* [Analytics](https://developer.ibm.com/watson/): Analytics delivers the value of data for the enterprise.
* [Artificial Intelligence](https://medium.com/ibm-watson): Artificial intelligence can be applied to disparate solution spaces to deliver disruptive technologies
* [Data Science](https://medium.com/ibm-watson): Systems and scientific methods to analyze structured and unstructured data in order to extract knowledge and insights.

# Description

# Flow

> Provide a draft architecture diagram followed by the flow steps; the architecture diagram needs to show a complete set of people, components, and technologies covered by your pattern; add numbers to the diagram that correspond with the written flow steps. The flow steps provide the  details of what happens at each stage, and the tasks performed by each component or technology; these are not steps to reproduce the code, but a description of the architecture of the code.

> Upload a draft architecture diagram to this issue. Remember to include numbers in the diagram to represent the flow steps that you provide below the diagram. A graphic designer will use your draft to create the production-ready image.

1. Flow step 1
2. Flow step 2
3. Flow step 3

# Instructions

> Find the detailed steps for this pattern in the [readme file](https://github.com/IBM/prediction-using-watson-machine-learning/blob/master/README.md). The steps will show you how to:

1. Clone the repository.
1. Create Watson services in IBM Cloud.
1. Save the credentials for your Watson Machine Learning Service.
1. Create the DB2 Warehouse on Cloud Service and load data.
1. Create a notebook in IBM Watson Studio.
1. Run the notebook in IBM Watson Studio.

# Components and services

> List all components and services that play a prominent role in your pattern. Components are IBM products, any open source project, or solutions that are NOT IBM Cloud Services. Services are services available in the IBM Cloud (public) Catalog.

> To view all components see [http://developer.ibm.com/components](http://developer.ibm.com/components).

> To view services, see [https://console.bluemix.net/catalog/](https://console.bluemix.net/catalog/)

* IBM Watson Studio
* IBM Machine Learning
* Apache Spark
* IBM DB2 Warehouse on Cloud

# Runtimes

* Apache Spark 2.1
* python 3.5

# Related IBM Developer content

> List any IBM Developer resources that are closely related to this pattern, such as other patterns, blog posts, tutorials, etc..

* [title](url): description
* [title](url): description

# Related links

> Provide any non-IBM Developer resources that you need to link to that are NOT components or services

* [title](url): description
* [title](url): description

# Announcement
Using machine learning in an application can produce impressive results, but moving from model training stage to production application is a lot of work. While frameworks like Apache Spark MLlib, Scikit-learn, Xgboost help to reduce model building workload, the IBM Watson Machine Learning is a solution that can productionalize those models in minutes. By taking advantage of Watson Machine Learning web service deployment of models, developers can easily start building their application with powerfull REST API.

In this code pattern, we use the machine learning classification algorithm to solve a requirement from biomedical company that produces heart drugs. The company has collected data about a set of patients, all of whom suffered from the same illness. During their course of treatment, each patient responded to one of five medications. Based on treatment records they would like to predict the best drug for the patient. 
The pattern shows exact steps how that data and Spark MLlib package are used to train a model that predicts the best drug.


Next, the trained model is published to Watson Machine Learning repository on CLoud and finally deployed as a web-service.
Using web-service details such as: scoring endpoint and credentials the model is being scored i.e.: new patient's records is being send in a request and drug recommendation is returned in response.

Try it out and let me know what you think!
