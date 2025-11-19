# Project 2

Project 2 is an open-ended assignment. You will identify one or more datasets out in the world, read and clean them, and tackle the three objectives of data science: exploration, prediction, and inference. It is meant to give you experience (1) working in an open-ended manner and (2) applying the full stack of the data science workflow. In other words, you will work in a way that will be expected of you as a practicing data scientist. Real-world datasets present their own, idiosyncratic challenges to work with, their own opportunities to learn from, and their own limitations. 

This project will challenge you creatively. You are meant to let your curiosity and interests guide your analyses. We will not tell you what to do, but we will give you advice or guidance as needed. Accordingly, you will be graded based on an earnest effort to address the three objectives specified. While the project itself is independent, you will be in a group of 3-4 students with similar interests who are there to help you with ideas, code, analyses etc... Comfort working in these setting is essential as AI replaces much of the busy work Data Scientists were once responsible for. 

## Part 1: Data

Due date: Tuesday, Oct 28th (Week 5)

Identify one or more datasets of interest. You might find a dataset that encompasses all the information you might want, in which case one dataset is fine. Alternatively, if a specific question of interest isn’t answerable with just the data you found then you may want to incorporate another, related dataset. Ultimately, we will evaluate whether your proposed data is sufficient for the scope of the project, but it should have some of the following properties:

•	Properly sourced. You should be able to identify where the data has come from and that it’s real.
•	Multivariate. Higher dimensional data will give you much more opportunity and flexibility for your analyses. 
•	Relatively high large sample size. There larger the data, the better confidence in your effect estimates and other statistics. What constitutes a large sample size will be influenced by your topic e.g. sports data will typically have smaller sample sizes.

You must propose your dataset or datasets before the due date for us to review. There are two requirements for submission:

1.	You have successfully read the data into as notebook. A screenshot of a notebook is sufficient for this.
2.	You have written a one-paragraph description of your proposed data and some possible objectives you would like to address using them. 

There’s an enormous amount of publicly available data on the internet. Below I list just a handful of great data sources, but I encourage you to search for datasets tailored to your specific interests. Unstructured databases (common in sports data) are available to you if you’re willing to experiment with some data scraping.

### Sources for data:
•	Data.gov
o	Warning: Much governmental data has been recently removed or altered without notice or documentation. This applies to the following three data sources as well. Most of these data are completely valid, but you should be mindful that variables in some datasets (largely related to sex, sexuality and gender identification) has been removed.
•	US Census Bureau
•	Federal Reserve Economic Data
•	National Bureau of Economic Research
•	Kaggle
o	Warning: Much Kaggle data is simulated or unsourced. If you’re using Kaggle data, it must be real and you must be able to identify its source.
•	World Health Organization (WHO) Data
•	World Bank Open Data	
•	UN Data
•	IBM Datasets
•	Azure Datasets
•	Harvard Dataverse
•	IEEE Dataport
•	Awesome Public Datasets
•	Many more….


The descriptions of the following parts are currently incomplete but exist to give you an idea of what to expect.

## Part 2: Exploration

Due Date: Monday Nov 17th . 

This will be the first section of your project notebook. In it, you will clean your data and perform exploratory data analysis (EDA). Your goal here is to develop a comprehensive understanding of the data. There is no specific length for this section, but for full credit you will need to demonstrate some or all of the following. This is not a template but a jumping off point – the specifics of your data and objectives will guide your EDA. For example, you don’t need to assess the distribution of every single variable in the data, but you should for those most relevant to your objectives.

Your code should be well-commented and you should have markdown cells documented your thought processes and learned insights as you go. 

1.	A clear attempt to understand the essential qualities and faithfulness of your data. You’re evaluating qualities such as:
a.	Dimensionality
b.	Missing values
c.	Obvious issues in the data

2.	Thorough description of your data, possibly including:
a.	Summaries statistics of key variables
b.	Identification of outliers
c.	Evaluation of data types

3.	Necessary cleaning of any issues identified in the previous steps
a.	Necessary data formatting to ensure analysis-ready data

4.	Exploratory visualization and statistics to deepen intuition for the data
a.	Individual or joint distributions of key variables
b.	Evaluate associations visually or with correlations
c.	Cross-tabulations for categorical variables
d.	Unsupervised learning if deemed interesting

## Part 3: Inference

Due Date: Thursday Dec 4th. This is the due date of the project. 

In the second section of your project notebook, you will use your data to try and learn something about the world. What could you argue is true about the world that you didn’t necessarily know before? Does your data support an existing narrative, or does it counter a narrative? Was there anything surprising that you learned? Your analyses must be oriented toward these objectives and you will therefore value analyses that facilitate interpretation, evaluation of confidence in observed effects, and assumptions.

1.	Develop one or more hypotheses about your data (null and alternative) 
2.	Perform some analysis that helps you evaluate your hypotheses. Examples include comparisons of means, comparisons of distributions, linear regression, etc…
3.	Quantify your confidence in the results. 
4.	Evaluate your hypotheses in the context of your results + confidence. 
5.	Consider assumptions built into your results and critique your analyses. Are there potential biases in the data? Did the data meet the assumptions of your analysis?

## Part 4: Prediction

Due Date: Thursday Dec 4th. This is the due date of the project. 

In the final section, you will model your data to predict unobserved values of one or more variables of interest. You are trying to create the highest fidelity model of your data possible i.e. the least wrong model. You should expect to try multiple different models, and potentially even different modeling frameworks if your data is amenable to them. In other words, model selection will be a significant part of this section. 

1.	Decide on a variable or variables that you’d like to model
2.	Decide on one or more modeling approaches e.g. multiple regression generalized linear regression, random forests, or many more whether we’ve covered them or not. Consider using ISL as a reference when thinking about your modeling options.
3.	Divide your data into train-test-validation sets and begin fitting models. Perform variable selection.
4.	Using an appropriate loss function, arrive at high quality model of your data. Evaluate the overall performance of your predictive model. 
5.	Describe its utility. Is the model useful? If so, what kinds of decisions could you make with it? If not, why not and why do you think your target was challenging to model?


