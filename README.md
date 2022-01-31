# Stock-analysis
----------------------------------

##Overview of Project: 

This core deliverable of this project is a table that pulls for a select list of tickers the Total Daily Volume as well as the Return in a visually appealing manor that is easy to understand. This was then taking a few steps further by giving options such as pulling different years - 2017 or 2018. 

From here an analysis was done to see if refactoring the origional code could result in a faster responding project.

##Results: 

When we compare the results they are as follows: 

Difference of 0.96 seconds in favor of the refactored code.
![2017_Origional](https://github.com/ethomas33/Stock-analysis/blob/8f2a657b4abc4180cffc5d5b8bc452884608aa3a/Resources/2017_O.png)
![2017_Refactored](https://github.com/ethomas33/Stock-analysis/blob/8f2a657b4abc4180cffc5d5b8bc452884608aa3a/Resources/2017_R.png)

Difference of 0.77 seconds in favor of the refactored code.
![2018_Origional](https://github.com/ethomas33/Stock-analysis/blob/8f2a657b4abc4180cffc5d5b8bc452884608aa3a/Resources/2018_O.png)
![2018_Refactored](https://github.com/ethomas33/Stock-analysis/blob/8f2a657b4abc4180cffc5d5b8bc452884608aa3a/Resources/2018_R.png)

##Summary: In a summary statement, address the following questions.

What are the advantages or disadvantages of refactoring code?

Particularly when you are coding for big data every second counts when pulling, processing and outputting the final format. By refactoring this code we were able to shave a considerable chunk of time off the analysis. I believe this can have two disadvantages first it can make a piece of code that is maybe needing to be short and simple for a single use case and turning into something more complicated just for the sake of "it might be reused some day" and second can introduce errors which can cause the code to break. 

How do these pros and cons apply to refactoring the original VBA script?

 I see the advantage here of storing the results in an arrary as we did in the refactored code. It made the return time considerably faster and would allow for an expanced dataset which I would venture to guess could be common with a stock dataset. While refactoring this code I definetly introduced an error that after a few hours of sitting with the code I decided to just start over and seemably with the same code in front of me suddently it was working. Obviously something changed but I couldn't identify what it was so another oppertunity for human error to be introduced. 
