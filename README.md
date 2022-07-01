Welcome to the Data Scientist take home exercise repo!

It contains few files:

- **dummy_data.csv** depicting our app’s backend live data. It has permits’ statuses such as user requests, closures once the work has been completed etc…
- **schema_def.yml**: permit table column names' definitions

### Few guidelines

You can use any programing language (our preferred one at siteAssist being **Python**).

The purpose of this exercise is to understand how you approach and think through a given task. 

Explain why you are using a certain method to answer a question? What was your thought process to arrive there? What are the pros/cons with your answers?

Also, if you were given more time what would be the logical next steps to make your answers more robust?

### First Task
> **Your first task is to infer at which state within the permit cycle a record is.**

***What we expect?***
1. Analyse the dataset to the best of your capacity. Don’t be afraid to challenge it if you feel it is not complete. 
2. Create some quick insights and potential visualisation of the data (EDA).
3. Define and implement an approach to solve the question above.

### Second Task
> **Your second task is to define a permit cycle funnel along with some success metrics to measure it.**

***What we expect?***
1. Task 1 helped you understand a permit's "life cycle". With those states:
   - you will now construct a "golden" path where success can be measured with your metrics.
   - each path's "milestones" can be a collections of states. Try to think of a holistic view first before going into more details.
2. We should be able to label our data with you funnel. It can then be used for some DS projects as well as for internal reporting.
3. From your derived metrics, what would you recommend as a first DS project?

### Additional question

At siteAssist, we deal with a lot of text data (answers to permit questions, reason for cancelling/amending/rejecting a permit).
> **How would you pre-process this data to be used for both modelling and observational analysis?**
