### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

There are no libraries necessary to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

The goal of this project was to analyze how people make purchasing decisions and how those decisions are influenced by promotional offers. The basic idea was to use customer data to identify which groups of people are most responsive to each type of offer, and how best to present each type of offer. Ultimately, the results of this study can be used to help Starbucks determine which customers to send offers to, which kind of offers to send, and through which channels. I used a 2018 Starbuck's dataset to answer the following questions:

1. Which offers were most effective for which people?
2. Which people spent money whether or not they received offers?

## File Descriptions <a name="files"></a>

There is one notebook in the repository, Starbucks_Capstone_notebook.ipynb, that goes through analysis related to the above questions.  The notebook is exploratory in searching through the data pertaining to the questions.  Markdown cells were used to assist in walking through the thought process for individual steps.

The 3 datasets used for the analysis can be found in the \data folder. They give the offers portfolio, customer profile, and transcript of events.

## Results<a name="results"></a>

The main findings of the analysis are below. A full post about the project can be found on Medium at https://dagmara-namasivayam.medium.com/an-analysis-of-starbucks-customer-demographics-and-promotional-offers-24d6ff8acce2.

1. Most often by far, offers were viewed and completed, suggesting that they are generally effective.
2. Young adults, those with lowest incomes, and males have a higher rate of not viewing offers and not completing them. The most-recently joined members (2018) are most likely to view and not complete an offer and least likely to complete it deliberately.
3. The most prominent factor for unviewed offers is that the channel of delivery does not include social means. This surprisingly holds true across age groups; however, the effect is strongest with younger adults.
4. If viewed, discount offers are most likely to be completed and BOGO offers the least likely. This holds true across age groups as well.
5. Most transactions and most money spent, in general, are not related to viewing or trying to complete an offer (whether successful or not).
6. In general, earliest (2013 and 2014) and most recent members (2018) spend less than others. Females spend more than males. Youngest members spend the least, with seniors slightly higher than middle-aged members. The largest difference, however is between income groups, where, unsurprisingly, the higher the income, the more spent.
7. The higher the income, the higher percentage of transactions are not offer-influenced, and the lower the percentage of transactions due to BOGO and discount offers. This is true for percent of transactional value as well.
8. Females spend more and are more often uninfluenced by offers than males.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Credit to Starbucks for the data. Also, Udacity's Data Science Nanodegree program provided the starting point for this project.
