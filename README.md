# Analyze A/B Test Results

This project will assure you have mastered the subjects covered in the statistics lessons. The hope is to have this project be as comprehensive of these topics as possible. Good luck!

![alt](https://github.com/swadeepsingh/Udacity-Data-Analyst-NanoDegree-A-B-Test/blob/master/download.png)

# Table of Contents

    Introduction
    Part I - Probability
    Part II - A/B Test
    Part III - Regression


# Introduction

A/B tests are very commonly performed by data analysts and data scientists. It is important that you get some practice working with the difficulties of these

For this project, you will be working to understand the results of an A/B test run by an e-commerce website. Your goal is to work through this notebook to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.


# A/B Test

Notice that because of the time stamp associated with each event, you could technically run a hypothesis test continuously as each observation was observed.

![alt](https://github.com/swadeepsingh/Udacity-Data-Analyst-NanoDegree-A-B-Test/blob/master/hypothesis.PNG)

However, then the hard question is do you stop as soon as one page is considered significantly better than another or does it need to happen consistently for a certain amount of time? How long do you run to render a decision that neither page is better than another?

These questions are the difficult parts associated with A/B tests in general.


# Results:

    After analyzing the dataset for e-commerce website it seems that our Null hypothesis is correct.
    From probability we can conclude that:
    Conversion for control group is higher.
    The control group does better but with a small margin.
    From histogram we can see that null hypothesis is true as old and new pages perform almost similarly.
    We have also seen that country alone has little impact on the conversion.
    The test conditions were fairly good as well, because user had a equal chance to receive old and new pages.
    An interaction between page and country has significant effects on conversion.


# Conclusion:

I recommend the e-commerce website company to keep the "old pages" for now $\&amp;$ spend time to improve the new pages before they go for another experiment and then finalize the decision.
