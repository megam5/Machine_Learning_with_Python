# Week 1

This week, you will learn about the applications of Machine Learning in different fields such as health care, banking, etc.
You’ll get a general overview of Machine Learning topics such as supervised vs unsupervised learning, and the usage of each algorithm.
Also, you'll understand the advantages of using Python libraries for implementing Machine Learning models.

## Introduction to Machine Learning

#### Is this a Benign or Malignant cell?

A human cell sample extracted from a patient. And the cell has characteristics…for example, its Clump thickness is 6, its Uniformity of cell size is 1, its Marginal adhesion is 1, and so on.

![GitHub1](https://user-images.githubusercontent.com/55942773/67641732-69c56e80-f92a-11e9-8b17-3b68116c9bbb.JPG)

One of the interesting questions we can ask, at this point is: "Is this a Benign or Malignant cell?" In contrast with a benign tumor, a malignant tumor is a tumor that may invade its surrounding tissue or spread around the body, and diagnosing it early might be the key to a patient’s survival. One could easily presume that only a doctor with years of experience could diagnose that tumor and say if the patient is developing cancer or not. Right?

#### Machine Learning helps with predictions!

Well, imagine that you’ve obtained a dataset containing characteristics of thousands of human cell samples extracted from patients who were believed to be at risk of developing cancer. You can use the values of these cell characteristics in samples from other patients to give an early indication of whether a new sample might be benign or malignant. You should clean your data, select a proper algorithm for building a prediction model, and train your model to understand patterns of benign or malignant cells within the data. Once the model has been trained by going through data iteratively, it can be used to predict your new or unknown cell with high accuracy. This is machine learning!

![GitHub2](https://user-images.githubusercontent.com/55942773/67641902-456a9180-f92c-11e9-9b89-b930bd2df62b.JPG)

#### What is Machine Learning?

> **_Machine learning is the subfield of computer science that gives "computers the ability to learn without being explicitly programmed. -[Arthur Samuel](https://en.wikipedia.org/wiki/Arthur_Samuel)”_**

####  How Machine Learning works?

Let me explain what I mean when I say “without being explicitly programmed.” Assume that you have a dataset of images of animals such as cats and dogs, and you want to have a software or an application that can recognize and differentiate them. The first thing that you have to do here is to interpret the images as a set of feature sets. For example, does the image show the animal’s eyes? If so, what is their size? Does it have ears? What about a tail? How many legs? Does it have wings?

Before machine learning, each image would be transformed into a vector of features. Then, traditionally, we had to write down some rules or methods to get computers to be intelligent and detect animals. But, it was a failure. Why? Well, it needed a lot of rules, highly dependent on the current dataset, and not generalized enough to detect out-of-sample cases.

![GitHub3](https://user-images.githubusercontent.com/55942773/67642252-d3944700-f92f-11e9-9fc8-c768fc5cdde3.JPG)

This is when machine learning entered the scene. Using machine learning allows us to build a model that looks at all the feature sets and their corresponding types of animals, and then it learns the pattern of each animal. It is a model built by machine learning algorithms. It detects without explicitly being programmed to do so. In essence, machine learning follows the same process that a 4-year-old child uses to learn, understand, and differentiate animals. So, machine learning algorithms, inspired by the human learning process, iteratively learn from data and allow computers to find hidden insights. These models help us in a variety of tasks, such as object recognition, summarization, recommendation, and so on.

![GitHub4](https://user-images.githubusercontent.com/55942773/67642254-d5f6a100-f92f-11e9-9c64-049ac3c50494.JPG)

#### Examples of Machine Learning

Machine Learning impacts society in a very influential way. Here are some real-life examples. First, how do you think Netflix and Amazon recommend videos, movies, and TV shows to its users? They use Machine Learning to produce suggestions that you might enjoy! This is similar to how your friends might recommend a television show to you, based on their knowledge of the types of shows you like to watch.

![GitHub5](https://user-images.githubusercontent.com/55942773/67642424-bceeef80-f931-11e9-9290-e2de459dc9ac.JPG)

There are many other applications of machine learning that we see every day in our daily life, such as chatbots, logging into our phones or even computer games using face recognition. Each of these uses different machine learning techniques and algorithms. So, let’s quickly examine a few of the more popular techniques.

#### Major Machine Learning techniques

1) Regression/Estimation (Predicting continuous values): The Regression/Estimation technique is used for predicting a continuous value, for example, predicting things like the price of a house based on its characteristics.

2) Classification (Predicting the item's class/category): A Classification technique is used for predicting the class or category of a case, for example, if a cell is benign or malignant, or whether an email is a spam or not spam.

3) Clustering (Finding the structure of data; summarization):	Clustering groups of similar cases, for example, can find similar patients, or can be used for customer segmentation in the banking field.

4) Association (Associating frequent co-occurring items/events):  Association technique is used for finding items or events that often co-occur, for example, grocery items that are usually bought together by a particular customer.

5) Anomaly Detection (Discovering abnormal and unusual cases): Anomaly detection is used to discover abnormal and unusual cases, for example, it is used for credit fraud detection.

6) Sequence Mining (Predicting next events; click-stream): Sequence mining is used for predicting the next event, for instance, the click-stream in websites.

7) Dimension Reduction (Reducing the size of the data): Dimension reduction is used to reduce the size of data.

8) Recommendation Systems (Recommending items): Recommendation systems; this associate's people's preferences with others who have similar tastes, and recommends new items to them, such as books or movies.

#### Difference between Artificial Intelligence, Machine Learning, Deep Learning

By this point, I’m quite sure this question has crossed your mind, “What is the difference between these buzzwords that we keep hearing these days, such as Artificial intelligence (or AI), Machine Learning and Deep Learning?” Well, let me explain what is different between them.

In brief, AI tries to make computers intelligent to mimic the cognitive functions of humans. So, Artificial Intelligence is a general field with a broad scope including Computer Vision, Language Processing, Creativity, etc.

Machine Learning is the branch of AI that covers the statistical part of artificial intelligence. It teaches the computer to solve problems by looking at hundreds or thousands of examples, learning from them, and then using that experience to solve the same problem in new situations.

Deep Learning is a very special field of Machine Learning where computers can learn and make intelligent decisions on their own. Deep learning involves a deeper level of automation in comparison with most machine learning algorithms.

![GitHub6](https://user-images.githubusercontent.com/55942773/67642811-ad71a580-f935-11e9-8157-52738f5d7ca2.JPG)

The repository is the result from the course ['Machine Learning with Python' from Coursera offered by IBM](https://www.coursera.org/learn/machine-learning-with-python).
