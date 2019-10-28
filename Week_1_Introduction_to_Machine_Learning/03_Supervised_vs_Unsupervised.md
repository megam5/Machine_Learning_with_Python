# Week 1

This week, you will learn about the applications of Machine Learning in different fields such as health care, banking, etc. 
You’ll get a general overview of Machine Learning topics such as supervised vs unsupervised learning, and the usage of each algorithm. 
Also, you'll understand the advantages of using Python libraries for implementing Machine Learning models.

## Supervised vs Unsupervised

### What is Supervised Learning?

Supervise means to observe, and direct the execution of a task, project, or activity. 
We aren't going to be supervising a person, instead will be supervising a machine learning model that might be able to 
produce classification regions.

![GitHub13](https://user-images.githubusercontent.com/55942773/67646954-71027180-f956-11e9-8362-9d415a31d93e.JPG)

So, how do we supervise a machine learning model? 
We do this by teaching the model, that is, we load the model with knowledge so that we can have it predict future instances. 
But this leads to the next question which is, how exactly do we teach a model?

#### Teaching the model with labeled data

We teach the model by training it with some data from a labeled dataset. 
It's important to note that the data is labeled, and what does a labeled dataset look like? 
Well, it could look something like this. This example is taken from the cancer dataset.

![GitHub14](https://user-images.githubusercontent.com/55942773/67647097-f554f480-f956-11e9-8a68-42551cee7d60.JPG)

As you can see, we have some historical data for patients, and we already know the class of each row. 
Let's start by introducing some components of this table. The names up here which are called clump thickness, uniformity of cell size and so on are called attributes. 
The columns are called features that include the data. 
If you plot this data and look at a single data point on a plot, it'll have all of the attributes that would make a row on the chart also referred to as an observation. 
Looking directly at the value of the data, you can have two kinds. The first is numerical. 
When dealing with machine learning, the most commonly used data is numeric. 
The second is categorical, that is it's non-numeric because it contains characters rather than numbers. 
In this case, it's categorical because this dataset is made for classification.

![GitHub15](https://user-images.githubusercontent.com/55942773/67647337-f4709280-f957-11e9-8623-bd183cf70e20.JPG)

#### Types of Supervised Learning

There are two types of supervised learning techniques.
1) `Classification:` Classification is the process of predicting a discrete class label, or category. 
2) `Regression:` Regression is the process of predicting a continuous value as opposed to predicting a categorical value in classification. 

![GitHub16](https://user-images.githubusercontent.com/55942773/67647565-c3449200-f958-11e9-96d4-51990ddecc04.JPG)

### What is Unsupervised Learing?

Unsupervised learning is exactly as it sounds. We do not supervise the model, 
but we let the model work on its own to discover information that may not be visible to the human eye.
It means, the unsupervised algorithm trains on the dataset, and concludes unlabeled data.
Generally speaking, unsupervised learning has more difficult algorithms than supervised learning since 
we know little to no information about the data, or the outcomes that are to be expected.

![GitHub17](https://user-images.githubusercontent.com/55942773/67647981-3b5f8780-f95a-11e9-9a77-1253410e754f.JPG)

Dimension reduction, density estimation, market basket analysis, and clustering are the most widely used unsupervised machine learning techniques.
Dimensionality reduction, and/or feature selection, play a large role in this by reducing redundant features to make the classification easier.
Market basket analysis is a modeling technique based upon the theory that if you buy a certain group of items, 
you're more likely to buy another group of items.
Density estimation is a very simple concept that is mostly used to explore the data to find some structure within it. And finally, clustering.

Clustering is considered to be one of the most popular unsupervised machine learning techniques used for grouping data points, or somehow similar objects. Cluster analysis has many applications in different domains, whether a bank desires to segment his customers based on certain characteristics, or helping an individual to organize in-group his, or her favorite types of music.
Generally speaking though, clustering is used mostly for discovering structure, summarization, and anomaly detection.

![GitHub18](https://user-images.githubusercontent.com/55942773/67648177-fb4cd480-f95a-11e9-8241-a0056c1451b9.JPG)

### Supervised vs Unsupervised Learning

So, to recap, the biggest difference between supervised, and unsupervised learning is that supervised learning deals with labeled data while unsupervised learning deals with unlabeled data. In supervised learning, we have machine learning algorithms for classification and regression. In unsupervised learning, we have methods such as clustering. 

In comparison to supervised learning, unsupervised learning has fewer models and fewer evaluation methods that can be used to ensure
that the outcome of the model is accurate. As such, unsupervised learning creates a less controllable environment as the machine is
creating outcomes for us.

![GitHub19](https://user-images.githubusercontent.com/55942773/67648326-61d1f280-f95b-11e9-96b3-7e44d6eacf98.JPG)
