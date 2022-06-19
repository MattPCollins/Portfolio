Portfolio Projects

# [Project #1: Japanese Kanji Revision Analysis](https://github.com/MattPCollins/Japanese-Revision)

As part of an effort to increase my efficiency in my Japanese studies, I created my own revision program in Python, as an avenue of my self-development. Within this I used a spaced-repetition algorithm to handle the frequency of my practice attempts for each words in my personal dictionary.

This project looks to analyse the findings of my studies and tune my learning algorithm to reduce my speed of learning characters/words while retaining retention of the word in my memory.

![](/images/kanji_practiced_over_time.png)

# [Project #2: Azure data and analytics trends in 2021](https://github.com/MattPCollins/StackOverflowAnalysis)

This mini-project involved reviewing Stack Overflow questions regarding Azure technologies in the data world and what trends and behaviours were like in 2021.
The blog post can be found [here.](https://blog.coeo.com/azure-data-and-analytics-trends-in-2021-what-does-stack-overflow-have-to-say)

![](/images/azure_comparative_plot.png)

# [Project #3: String generalisation tool for Natural Language Processing](https://github.com/MattPCollins/Classification)

As part of a classification machine learning project I was looking for a way to improve feature importance of one dimension in my data set. The feature itself was descriptive of a target parameter I was trying to classify but, due to high variation in the strings, it was hard to use as a feature for prediction. Within this, however, there were similarities in the strings and some data cleansing would improve the usefulness of this parameter. 

With ReGex being an expensive and calculated method within Natural Language Processing (NLP), this laborious approach inspired me to consider automating this string manipulation process, allowing unsupervised categorisation of the data and deliver analysis and modelling quicker – the value we’re undoubtedly looking for!

![](/images/string_similarity_matrix.png)

# [Project #4: Parallelising workloads in Pyspark: Pandas UDFs vs concurrent.futures ](https://github.com/MattPCollins/ConcurrentModelTraining)

I've recently been working on an internal project to predict future disk space usage for our customers across thousands of disks. Each disk is subject to its own usage patterns and this means we need a separate machine learning model for each disk which takes historical data to predict future usage on a disk-by-disk basis. While performing this prediction and choosing the correct algorithm for the job is a challenge in itself, performing this at scale has its own problems.

In order to take advantage of more sophisticated infrastructure, we can look to move away sequential predictions to parallel and speed up the operation of the forecasting. This project compares Pandas UDFs and the concurrent.futures module, two approaches of concurrent processing, and determine use cases for each using sequential processing via a for loop as a baseline.

![](/images/linear_regression.png)

![](/images/fbprophet.png)

![](/images/combined_model.png)


