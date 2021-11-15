# Self_Assessment by Kieran Persaud

## Summary of Project
Team 5's project sought to determine the effect of macroeconomic factors on stock exchange index closing prices. The question we asked is could we determine the stock price of any particular time based on the relationship of inflation, GDP, and working population? We utilized a supervised machine learning model that performed multivariate linear regression. After training our model with historical data, we determined the following equation that would predict closing prices with a 94.57% accuracy.

```Pred Close Price = (0.19632 x Pred Real GDP per Capita) + (2653.9 x Pred Inflation) + (0.000018474 x Pred Working Pop)- 13234.04```

<img width="538" src="https://user-images.githubusercontent.com/84286467/141700316-bb203acb-6b6e-44da-abfb-41f27419c3c8.png"/>

## Self Assessment
For this project, I assumed the role that worked on the machine learning model. I thoroughly enjoyed this lesson during the course and wanted to do more work with the topic. In this project, I identified the type of model that would be used, built the necessary code in a Google Colab notebook, tested and trained the datasets, and determined its accuracy in solving the question the group posed. As previously mentioned, the model was able to achieve a 94.57% accuracy, which exceeded our initial goal of 75% accuracy.

While my main focus was the machine learning model, I was very participatory in the other roles. In the beginning stages, I provided sources for possible datasets that the group could analyze, and that the Database team could process. Throughout the project, I was available to answer questions via Slack, and reviewed the GitHub to clear any discrepancies and issues with merging the branches with the main. After determining the equation used to calculate predicted closing prices, I worked with the Visualization team to graph the historical data vs the predicted data, which they then depicted in Tableau.

The greatest personal challenge that I had to overcome during the project was the forethought and planning that had to go into the Machine Learning Model. I had to critically think about the target and feature sets, how the model would answer the question, and if the data we found served as adequate inputs. I was able to overcome it through time management and breaking up the deliverables into small tasks to accomplish. My personal success was also facilitated by the team structure, which I will discuss in the next section.

## Team Assessment 
Team 5 consisted of 6 members. The group determined that 2 people would work on each aspect of the project, with everyone contributing to the GitHub. My partner for the Machine Learning Model was Caroline Otis, and we worked individually and in tandem to build, train, and assess the model.

The team as a whole communicated primarily through Slack, Google Sheets, and weekly Zoom meetings outside of class time. During these Zoom meeting sessions, we set timelines for deliverables, reviewed our group's work and and provided constructive criticism. We worked together to troubleshoot individual issues with the Machine Learning Code and with Git Hub. One challenge we did face was the deduction of points for Deliverable 2 of the project. We had not clearly outlined the data exploration phase of the project. After speaking to the TA, we created a new workbook and section in the readme to depict it. The next time we met, we thoroughly went through the rubric point by point to ensure we were meeting all requirements. A thorough rubric review would be a technique I would utilize earlier if we could do it differently next time.

Overall, I consider Team 5 to be a strong team. We were communicative on all channels and receptive to help. One of our best strengths was creating a sample joined dataset for the Database, Machine Learning, and Dashboard teams to use and work independently and concurrently. We were certainly more efficient in the use of our time, as we knew what the joined dataset should look like, and each team could use it to fulfill their deliverables. I would suggest that new cohorts kicking off their own project would employ a similar method.
