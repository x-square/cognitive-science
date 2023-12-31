---
title: "Notes on data analytics"
author: "Chiawei Wang"
date: "January 2024"
date-format: "MMMM YYYY"
format: html
toc: true
toc-location: left
number-sections: true
---

`This document compiles information from Google Data Analytics`[^1]

[^1]: [Google Data Analytics](https://www.coursera.org/professional-certificates/google-data-analytics) includes over 180 hours of instruction and hundreds of practice-based assessments, which will help you simulate real-world data analytics scenarios that are critical for success in the workplace. The content is highly interactive and exclusively developed by Google employees with decades of experience in data analytics. Through a mix of videos, assessments, and hands-on labs, you’ll get introduced to analysis tools and platforms and key analytical skills required for an entry-level job.

Data analytics is the collection, transformation and organization of data in order to draw conclusions, make predictions and drive informed decision making.

## Foundations: Data, data, everywhere

### Six data analysis phases

Analysts use data-driven decision-making and follow a step-by-step process:

1.  **Ask** questions and define the problem
2.  **Prepare** data by collecting and storing the information
3.  **Process** data by cleaning and checking the information
4.  **Analyze** data to find patterns, relationships and trends
5.  **Share** data with your audience
6.  **Act** on the data and use the analysis results

![Data analysis process](https://github.com/x-square/images/blob/main/data-analysis-process.png?raw=true)

### SQL (structured query language)

SQL is designed for managing and manipulating relational databases. It is used for tasks such as querying data, updating records, inserting new data and deleting information from databases.

-   **SELECT** to choose the columns you want to return
-   **FROM** to choose the tables where the columns you want are located
-   **WHERE** to filter for certain information

![Example of SQL syntax](https://github.com/x-square/images/blob/main/sql-syntax.png?raw=true)

BigQuery is Google's fully managed, serverless data warehouse that works across clouds and enables scalable analysis. It supports querying using a dialect of SQL.

## Ask questions to make data-driven decisions

### Six problem types

Data analytics is so much more than just plugging information into a platform to find insights. It is about solving problems. To get to the root of these problems and find practical solutions, there are lots of opportunities for creative thinking. No matter the problem, the first and most important step is understanding it.

![Analysts typically work with six problem types](https://github.com/x-square/images/blob/main/six-problem-types.png?raw=true)

Examples are summarized below for review:

#### Making predictions

A company that wants to know the best advertising method to bring in new customers is an example of a problem requiring analysts to make predictions. Analysts with data on location, type of media, and number of new customers acquired as a result of past ads can't guarantee future results, but they can help predict the best placement of advertising to reach the target audience.

#### Categorising things

An example of a problem requiring analysts to categorize things is a company's goal to improve customer satisfaction. Analysts might classify customer service calls based on certain keywords or scores. This could help identify top-performing customer service representatives or help correlate certain actions taken with higher customer satisfaction scores.

#### Spotting something unusual

A company that sells smart watches that help people monitor their health would be interested in designing their software to spot something unusual. Analysts who have analyzed aggregated health data can help product developers determine the right algorithms to spot and set off alarms when certain data doesn't trend normally.

#### Identifying themes

Designers often collaborate with analysts to analyze user interaction data. Analysts play a crucial role in categorising and identifying themes within the data, particularly in usability improvement projects. Themes, such as user beliefs, practices and needs, help researchers delve into specific aspects of the data, offering valuable insights for prioritising product features. While categorising involves assigning items to categories, identifying themes goes a step further, grouping categories into broader themes.

#### Discovering connections

A third-party logistics company working with another company to get shipments delivered to customers on time is a problem requiring analysts to discover connections. By analyzing the wait times at shipping hubs, analysts can determine the appropriate schedule changes to increase the number of on-time deliveries.

#### Finding patterns

Minimising downtime caused by machine failure is an example of a problem requiring analysts to find patterns in data. For example, by analyzing maintenance data, they might discover that most failures happen if regular maintenance is delayed by more than a 15-day window.

### SMART questions

Companies in lots of industries today are dealing with rapid change and rising uncertainty. Even well-established businesses are under pressure to keep up with what is new and figure out what is next. To do that, they need to ask questions. Asking the right questions can help spark the innovative ideas that so many businesses are hungry for these days.

No matter how much information you have or how advanced your tools are, your data won't tell you much if you don't start with the right questions. Think of it like a detective with tons of evidence who doesn't ask a key suspect about it.

![Examples of SMART questions](https://github.com/x-square/images/blob/main/smart-questions.png?raw=true)

### Qualitative and quantitative data in business

We can take a closer look at the data types and data collection tools. Imagine that you are a data analyst for a chain of movie theaters. Your manager wants you to track trends in:

-   Movie attendance over time
-   Profitability of the concession stand
-   Evening audience preferences

In our scenario, we assume quantitative data already exists to monitor all three trends. Since we know that the movie theater is planning to raise ticket prices for evening showtimes in a few months, we will also include a question in the survey to get an idea of customers' price sensitivity.

Your final online survey might include these questions for qualitative data:

-   What went into your decision to see a movie in our theater today? (movie attendance)
-   What do you think about the quality and value of your purchases at the concession stand? (concession stand profitability)
-   Which showtime do you prefer, 8:00 PM or 8:30 PM, and why do you prefer that time? (evening movie-goer preferences)
-   Under what circumstances would you choose a matinee over a night time showing? (ticket price increase)

Data analysts will generally use both types of data in their work. Usually, qualitative data can help analysts better understand their quantitative data by providing a reason or more thorough explanation. In other words, quantitative data generally gives you the what, and qualitative data generally gives you the why. By using both quantitative and qualitative data, you can learn when people like to go to the movies and why they chose the theater. Maybe they really like the reclining chairs, so your manager can purchase more recliners. Maybe the theater is the only one that serves root beer. Maybe a later show time gives them more time to drive to the theater from where popular restaurants are located. Maybe they go to matinees because they have kids and want to save money. You wouldn't have discovered this information by analyzing only the quantitative data for attendance, profit, and showtimes.

### Importance of context

Context is the condition in which something exists or happens. Context is important in data analytics because it helps us sift through huge amounts of disorganized data and turn it into something meaningful. The fact is, data has little value if it is not paired with context.

Context can turn raw data into meaningful information. It is very important for data analysts to contextualize their data. This means giving the data perspective by defining it. To do this, you need to identify:

-   **Who** the person or organization that created, collected and or funded the data collection
-   **What** the things in the world that data could have an impact on
-   **Where** the origin of the data
-   **When** the time when the data was created or collected
-   **Why** the motivation behind the creation or collection
-   **How** the method used to create or collect it

### Data scenarios and responses

When you communicate your analysis and recommendations as a data analyst, it's vital to keep your audience in mind. :

-   Who is our audience?
-   What do they already know?
-   What do they need to know?
-   How can we best communicate what they need to know?

### Limitations of data

Data is powerful, but it has its limitations. Has someone's personal opinion found its way into the numbers? Is your data telling the whole story? Part of being a great data analyst is knowing the limits of data and planning for them.

-   Case of incomplete or non-existent data
-   Don't miss misaligned data
-   Deal with dirty data
-   Tell a clear story
-   Be the judge

### Leading great meetings

![Example of meeting agenda](https://github.com/x-square/images/blob/main/meeting-agenda.png?raw=true)

## Prepare data for exploration

### Selecting the right data

![How to collect the right data?](https://github.com/x-square/images/blob/main/data-collection-considerations.png?raw=true)

### Data modelling levels and techniques

Data modelling is the process of creating diagrams that visually represent how data is organized and structured. These visual representations are called data models. You can think of data modelling as a blueprint of a house. At any point, there might be electricians, carpenters, and plumbers using that blueprint. Each one of these builders has a different relationship to the blueprint, but they all need it to understand the overall structure of the house. Data models are similar. Different users might have different data needs, but the data model gives them an understanding of the structure as a whole.

There are a lot of approaches when it comes to developing data models, but two common methods are the **Entity Relationship Diagram** (ERD) and the **Unified Modelling Language** (UML) diagram. ERDs are a visual way to understand the relationship between entities in the data model. UML diagrams are very detailed diagrams that describe the structure of a system by showing the system's entities, attributes, operations, and their relationships. As a junior data analyst, you will need to understand that there are different data modelling techniques, but in practice, you will probably be using your organization's existing technique.

![Example of ERD](https://github.com/x-square/images/blob/main/erd-diagram.png?raw=true)

![Example of UML](https://github.com/x-square/images/blob/main/uml-diagram.png?raw=true)

### Understanding Boolean logic

Data analysts use Boolean statements to do a wide range of data analysis tasks, such as creating queries for searches and checking for conditions when writing programming code.

Imagine you are shopping for shoes, and are considering certain preferences:

-   You will buy the shoes only if they are pink **and** grey
-   You will buy the shoes if they are entirely pink **or** entirely grey, **or** if they are pink and grey
-   You will buy the shoes if they are grey, but **not** if they have any pink

### Databases in data analytics

Databases enable analysts to manipulate, store, and process data. This helps them search through data a lot more efficiently to get the best insights.

#### Relational databases

A **relational** database is a database that contains a series of tables that can be connected to show relationships. Basically, they allow data analysts to organize and link data based on what the data has in common.

In a **non-relational** table, you will find all of the possible variables you might be interested in analyzing all grouped together. This can make it really hard to sort through. This is one reason why relational databases are so common in data analysis. They simplify a lot of analysis processes and make data easier to find and use across an entire database.

#### Key to relational databases

Tables in a relational database are connected by the fields they have in common. You might remember learning about primary and foreign keys before. As a quick refresher, a **primary key** is an identifier that references a column in which each value is unique. In other words, it's a column of a table that is used to uniquely identify each record within that table. The value assigned to the primary key in a particular row must be unique within the entire table. For example, if customer_id is the primary key for the customer table, no two customers will ever have the same customer_id.

By contrast, a **foreign key** is a field within a table that is a primary key in another table. A table can have only one primary key, but it can have multiple foreign keys. These keys are what create the relationships between tables in a relational database, which helps organize and connect data across multiple tables in the database.

Some tables don't require a primary key. For example, a revenue table can have multiple foreign keys and not have a primary key. A primary key may also be constructed using multiple columns of a table. This type of primary key is called a composite key. For example, if customer_id and location_id are two columns of a **composite key** for a customer table, the values assigned to those fields in any given row must be unique within the entire table.

![Example of database keys](https://github.com/x-square/images/blob/main/database-keys.png?raw=true)

## Process data from dirty to clean

### Well-aligned objectives and data

You can gain powerful insights and make accurate conclusions when data is well-aligned to business objectives. As a data analyst, alignment is something you will need to judge. Good alignment means that the data is relevant and can help you solve a business problem or determine a course of action to achieve a given business objective.

#### Business case A

Imagine account managers at Impress Me, an online content subscription service, want to know how soon users view content after their subscriptions are activated.

To start off, the data analyst verifies that the data exported to spreadsheets is clean and confirms that the data needed (when users access content) is available. Knowing this, the analyst decides there is good alignment of the data to the business objective. All that is missing is figuring out exactly how long it takes each user to view content after their subscription has been activated.

![Example of relevant data in spreadsheet](https://github.com/x-square/images/blob/main/data-spreadsheet.png?raw=true)

#### Business case B

Imagine Cloud Gate, a software company, recently hosted a series of public webinars as free product introductions. The data analyst and webinar program manager want to identify companies that had five or more people attend these sessions. They want to give this list of companies to sales managers who can follow up for potential sales.

| **Name**          | **Research methods** | **Additional information**                   |
|-------------------|-------------------|----------------------------------|
| **Email Address** | `xxxxx\@company.com` | Required information attendees had to submit |
| **Company**       | \<company name\>     | Optional information attendees could provide |

: Webinar attendance data includes the fields

The webinar attendance data seems to align with the business objective. But the data analyst and program manager decide that some **data cleaning** is needed before the analysis. They think data cleaning is required because:

-   The company name wasn't a mandatory field. If the company name is blank, it might be found from the email address. For example, if the email address is `username\@google.com`, the company field could be filled in with Google for the data analysis. This data cleaning step assumes that people with company-assigned email addresses attended a webinar for business purposes.
-   Attendees could enter any name. Since attendance across a series of webinars is being looked at, they need to validate names against unique email addresses. For example, if Joe Cox attended two webinars but signed in as Joe Cox for one and Joseph Cox for the other, he would be counted as two different people. To prevent this, they need to check his unique email address to determine that he was the same person. After the validation, Joseph Cox could be changed to Joe Cox to match the other instance.

#### Business case C

Imagine an after-school tutoring company, A+ Education, wants to know if there is a minimum number of tutoring hours needed before students have at least a 10% improvement in their assessment scores.

The data analyst thinks there is good alignment between the data available and the business objective because:

-   Students log in and out of a system for each tutoring session, and the number of hours is tracked
-   Assessment scores are regularly recorded

After looking at the data, the data analyst discovers that there are **other variables** to consider. Some students had consistent weekly sessions while other students had scheduled sessions more randomly even though their total number of tutoring hours was the same. The data doesn't align as well with the original business objective as first thought, so the analyst adds a **data constraint** to focus only on the students with consistent weekly sessions. This modification helps to get a more accurate picture about the enrolment time needed to achieve a 10% improvement in assessment scores.

### What to do when you find an issue with your data

When you are getting ready for data analysis, you might realize you don't have the data you need or you don't have enough of it. In some cases, you can use what is known as proxy data in place of the real data. Think of it like substituting oil for butter in a recipe when you don't have butter. In other cases, there is no reasonable substitute and your only option is to collect more data.

![Decision tree of how to deal with data errors or not enough data](https://github.com/x-square/images/blob/main/data-errors-not-enough.png?raw=true)

### Calculating sample size

| **Terminology**              | **Definitions**                                                                                                                                                                                                                                                                                                                                                                      |
|--------------------------|----------------------------------------------|
| **Population**               | The entire group that you are interested in for your study. For example, if you are surveying people in your company, the population would be all the employees in your company.                                                                                                                                                                                                     |
| **Sample**                   | A subset of your population. Just like a food sample, it is called a sample because it is only a taste. So if your company is too large to survey every individual, you can survey a representative sample of your population.                                                                                                                                                       |
| **Margin of error**          | Since a sample is used to represent a population, the sample’s results are expected to differ from what the result would have been if you had surveyed the entire population. This difference is called the margin of error. The smaller the margin of error, the closer the results of the sample are to what the result would have been if you had surveyed the entire population. |
| **Confidence level**         | How confident you are in the survey results. For example, a 95% confidence level means that if you were to run the same survey 100 times, you would get similar results 95 of those 100 times. Confidence level is targeted before you start your study because it will affect how big your margin of error is at the end of your study.                                             |
| **Confidence interval**      | The range of possible values that the population’s result would be at the confidence level of the study. This range is the sample result +/- the margin of error. To be brief, **confidence interval = sample mean ± margin of error**.                                                                                                                                              |
| **Statistical significance** | The determination of whether your result could be due to random chance or not. The greater the significance, the less due to chance.                                                                                                                                                                                                                                                 |

: Statistical terms and definitions

When figuring out a sample size, here are things to keep in mind:

-   Don't use a sample size less than 30. It has been statistically proven that 30 is the smallest sample size where an average result of a sample starts to represent the average result of a population.
    -   This recommendation is based on the **Central Limit Theorem** (CLT) in the field of probability and statistics. As sample size increases, the results more closely resemble the normal (bell-shaped) distribution from a large number of samples.
    -   A sample of 30 is the smallest sample size for which the CLT is still valid. Researchers who rely on **regression analysis** – statistical methods to determine the relationships between controlled and dependent variables – also prefer a minimum sample of 30.
-   The confidence level most commonly used is 95%, but 90% can work in some cases.
-   Increase the sample size to meet specific needs of your project
    -   For a higher confidence level, use a larger sample size
    -   To decrease the margin of error, use a larger sample size
    -   For greater statistical significance, use a larger sample size

### All about margin of error

#### Margin of error in baseball

Imagine you are playing baseball and that you are up at bat. The crowd is roaring, and you are getting ready to try to hit the ball. The pitcher delivers a fast ball travelling about 90-95mph, which takes about 400 milliseconds (ms) to reach the catcher's glove. You swing and miss the first pitch because your timing was a little off. You wonder if you should have swung slightly earlier or slightly later to hit a home run. That time difference can be considered the margin of error, and it tells us how close or far your timing was from the average home run swing.

#### Margin of error in marketing

For example, suppose you are conducting an A/B test to compare the effectiveness of two different email subject lines to entice people to open the email. You find that subject line A: **Special offer just for you** resulted in a 5% open rate compared to subject line B: **Don't miss this opportunity** at 3%.

Does that mean subject line A is better than subject line B? It depends on your margin of error. If the margin of error was 2%, then subject line A's actual open rate or confidence interval is somewhere between 3% and 7%. Since the lower end of the interval overlaps with subject line B's results at 3%, you can't conclude that there is a statistically significant difference between subject line A and B. Examining the margin of error is important when making conclusions based on your test results.

### What is dirty data?

![Types of dirty data](https://github.com/x-square/images/blob/main/dirty-data.png?raw=true)

#### Business impact of dirty data

Here are a few impacts cited for certain industries from a previous search:

-   [Banking](https://sloanreview.mit.edu/article/seizing-opportunity-in-data-quality): Inaccuracies cost companies between 15% and 25% of revenue
-   [Digital commerce](https://www.demandgen.com/dirty-data-what-is-it-costing-you): Up to 25% of B2B database contacts contain inaccuracies
-   [Marketing and sales](https://www.dqglobal.com/blog/why-bad-data-is-wasting-your-marketing-efforts): 99% of companies are actively tackling data quality in some way
-   [Healthcare](https://www.techtarget.com/searchhealthit): Duplicate records can be 10% and even up to 20% of a hospital’s electronic health records

### [Common data-cleaning pitfalls](https://www.coursera.org/learn/process-data/supplement/m3iWu/common-data-cleaning-pitfalls)

![Errors you might come across while cleaning your data](https://github.com/x-square/images/blob/main/data-cleaning-errors.png?raw=true)

### Workflow automation

| **Task**                                      | **Can it be automated?** | **Why?**                                                                                                                                                                                                                                                                                                          |
|-------------------|-------------------|----------------------------------|
| Communicating with your team and stakeholders | No                       | Communication is key to understanding the needs of your team and stakeholders as you complete the tasks you are working on. There is no replacement for person-to-person communications.                                                                                                                          |
| Presenting your findings                      | No                       | Presenting your data is a big part of your job as a data analyst. Making data accessible and understandable to stakeholders and creating data visualizations can’t be automated for the same reasons that communications can’t be automated.                                                                      |
| Preparing and cleaning data                   | Partially                | Some tasks in data preparation and cleaning can be automated by setting up specific processes, like using a programming script to automatically detect missing values.                                                                                                                                            |
| Data exploration                              | Partially                | Sometimes the best way to understand data is to see it. Luckily, there are plenty of tools available that can help automate the process of visualising data. These tools can speed up the process of visualizing and understanding the data, but the exploration itself still needs to be done by a data analyst. |
| Modelling the data                            | Yes                      | Data modelling is a difficult process that involves lots of different factors Luckily there are tools that can completely automate the different stages.                                                                                                                                                          |

: What can be automated?

### Workflow automation

Engineers use **engineering change orders** to keep track of new product design details and proposed changes to existing products. Writers use document revision histories to keep track of changes to document flow and edits. And data analysts use changelogs to keep track of data transformation and cleaning.

![Example of changelogs](https://github.com/x-square/images/blob/main/changelogs.png?raw=true)

### [Adding softs skills to your resume](https://www.coursera.org/learn/process-data/supplement/U8xZj/adding-softs-skills-to-your-resume)

![Common soft skills you will find in an entry-level data analyst resume](https://github.com/x-square/images/blob/main/data-analyst-soft-skills.png?raw=true)

## Analyze data to answer questions

### [Keeping data organized with sorting and filters](https://www.coursera.org/learn/analyze-data/supplement/RSNx9/keeping-data-organized-with-sorting-and-filters)

The organization of datasets is really important for data analysts. Most of the datasets you will use will be organized as tables. Tables are helpful because they let you manipulate your data and categorize it. Having distinct categories and classifications lets you focus on, and differentiate between, your data quickly and easily.

Data analysts also need to format and adjust data when performing an analysis. **Sorting** and **filtering** are two ways you can keep things organized when you format and adjust data to work with it. For example, a filter can help you find errors or outliers so you can fix or flag them before your analysis. **Outliers** are data points that are very different from similarly collected data and might not be reliable values. The benefit of filtering the data is that after you fix errors or identify outliers, you can remove the filter and return the data to its original organization.

### [Converting data in spreadsheets](https://www.coursera.org/learn/analyze-data/supplement/H7GTe/converting-data-in-spreadsheets)

As a data analyst, there are lots of scenarios when you might need to convert data in a spreadsheet:

-   String to date
-   String to numbers
-   Combining columns
-   Number to percentage

#### Pro tip

Keep in mind that you may have lots of columns of data that require different formats. Consistency is key, and best practice is to make sure an entire column has the same format.

### [Types of data validation](https://www.coursera.org/learn/analyze-data/supplement/tQAED/types-of-data-validation)

As a junior data analyst, you might not perform all of these validations. But you could ask if and how the data was validated before you begin working with a dataset. Data validation helps to ensure the integrity of data. It also gives you confidence that the data you are using is clean.

-   Data type
-   Data range
-   Data constraints
-   Data consistency
-   Data structure
-   Code validation

## Share data through the art of visualization

### [Effective data visualizations](https://www.coursera.org/learn/visualize-data/supplement/9xEjx/effective-data-visualizations)

A data visualization, sometimes referred to as a data viz, allows analysts to properly interpret data. A good way to think of data visualization is that it can be the difference between utter confusion and really grasping an issue. Creating effective data visualizations is a complex task; there is a lot of advice out there, and it can be difficult to grasp it all. In this reading, you are going to learn some tips and tricks for creating effective data visualizations. First, you'll review two frameworks that are useful for thinking about how you can organize the information in your visualization. Second, you'll explore pre-attentive attributes and how they can be used to affect the way people think about your visualizations. From there, you'll do a quick review of the design principles that you should keep in mind when creating your visualization. You will end the reading by reviewing some practices that you can use to avoid creating misleading or inaccurate visualizations.

### [Correlation and causation](https://www.coursera.org/learn/visualize-data/supplement/PPdt5/correlation-and-causation)

Correlation in statistics is the measure of the degree to which two variables move in relationship to each other. An example of correlation is the idea that “As the temperature goes up, ice cream sales also go up.” It is important to remember that correlation doesn’t mean that one event causes another. But, it does indicate that they have a pattern with or a relationship to each other. If one variable goes up and the other variable also goes up, it is a positive correlation. If one variable goes up and the other variable goes down, it is a negative or inverse correlation. If one variable goes up and the other variable stays about the same, there is no correlation.

Causation refers to the idea that an event leads to a specific outcome. For example, when lightning strikes, we hear the thunder (sound wave) caused by the air heating and cooling from the lightning strike. Lightning causes thunder.

![Examples of correlation and causation](https://github.com/x-square/images/blob/main/correlation-causation.png?raw=true)

### [The wonderful world of visualizations](https://www.coursera.org/learn/visualize-data/supplement/j9Wdl/the-wonderful-world-of-visualizations)

Meaningful patterns can take many forms, such as:

-   **Change** is a trend or instance of observations that become different over time. A great way to measure change in data is through a line or column chart.
-   **Clustering** is a collection of data points with similar or different values. This is best represented through a distribution graph.
-   **Relativity** is an observation considered in relation or in proportion to something else. You have probably seen examples of relativity data in a pie chart.
-   **Ranking** is a position in a scale of achievement or status. Data that requires ranking is best represented by a column chart.
-   **Correlation** shows a mutual relationship or connection between two or more things. A scatter plot is an excellent way to represent this type of data pattern.

### [Data grows on decision trees](https://www.coursera.org/learn/visualize-data/supplement/XvN2U/data-grows-on-decision-trees)

A decision tree is a decision-making tool that allows you, the data analyst, to make decisions based on key questions that you can ask yourself. Each question in the visualization decision tree will help you make a decision about critical features for your visualization. Below is an example of a basic decision tree to guide you towards making a data-driven decision about which visualization is the best way to tell your story. Please note that there are many different types of decision trees that vary in complexity, and can provide more in-depth decisions.

![Best way to represent data](https://github.com/x-square/images/blob/main/data-dicision-tree.png?raw=true)

### [Principles of design](https://www.coursera.org/learn/visualize-data/supplement/Ijxn6/principles-of-design)

![Nine principles of design](https://github.com/x-square/images/blob/main/nine-design-principles.png?raw=true)

## Foundations of data science[^2]

[^2]: This part of notes is compiled from [Google Advanced Data Analytics](https://www.coursera.org/professional-certificates/google-advanced-data-analytics). This program includes over 200 hours of instruction and hundreds of practice-based assessments, which will help you simulate real-world advanced data analytics scenarios that are critical for success in the workplace. The content is highly interactive and exclusively developed by Google employees with decades of experience in advanced data analytics and data science. Through a mix of videos, assessments, and hands-on labs, you’ll get introduced to advanced data analytics tools and platforms and key technical skills required for an advanced role.

### PACE stages

As a general rule, data professionals rely on workflow structures to guide them through the duration of data projects. Within a large-scale project, there can be a number of tasks that require a certain order of operations. Identifying complexities and finding consistent ways to work together can make projects more efficient and enable more productive communication. Identifying these and other types of potential blockers early can help you plan and prepare resources in advance before they can negatively affect a project.

Data professionals at Google developed PACE as a flexible model. Through PACE, you will identify areas of action and contexts for when they will need to be considered. All in all, PACE offers professionals a customizable scaffold that can support their efforts while working through every stage of a data project.

![Pace model](https://github.com/x-square/images/blob/main/pace-model.png?raw=true)

Let’s take a closer look at each stage of the PACE model.

#### Plan

At the beginning of a project, it is important to establish a solid foundation for success. Here you will define the scope of your project. This is when you will begin by identifying the informational needs of the organization. During the planning stage, you will have the widest viewpoint of a project. By assessing all of the factors and processes involved, you are mapping a path to completion, using your creativity to conceptualize a course of action. Here you will also take special note of tasks that may require an innovative approach within your workflow.

The planning stage is where you conceptualize the scope of the project and develop the steps that will guide you through the process of completing a project. Here are a few examples of the types of planning stage tasks:

-   Research business data
-   Define the project scope
-   Develop a workflow
-   Assess project and or stakeholder needs

#### Analyze

In the analyzing stage, you will interact with the data for the first time. Here you will acquire all of the data you will need for the project. Some datasets could come from primary sources within your organization. Others may need to be collected from secondary sources outside your company. You may even find that you need governmental or open source data. The analyzing stage is also where you will engage in exploratory data analysis or EDA. This involves cleaning, reorganizing and analyzing all of the necessary data for the project.

The analyzing stage is where you will collect, prepare, and analyze all of the data for your project. Here are a few examples of the types of analyzing stage tasks:

-   Format database
-   Scrub data
-   Convert data into usable formats

#### Construct

Just as the name suggests, the construction stage is all about building. In this stage of PACE, you will be building, interpreting, and revising models. Some projects will require machine learning algorithms to uncover correlations within your data. You will use these correlations to uncover information from the data that would otherwise go unused. These relationships can help your organization make informed decisions about the future.

In the construction stage you will build models that will allow you access to hidden relationships locked within data. Here are a few examples of the types of construction stage tasks:

-   Select modeling approach
-   Build models
-   Build machine learning algorithms

#### Execute

In the execution stage, you will put your analysis and construction into action. Here you will deliver your findings to the internal (inside of your organization) and external (outside of your organization) stakeholders. Quite often, this will involve stakeholders from the business-side of the companies you are working with. Presenting your findings is only a part of the execution stage. Stakeholders will provide feedback, ask questions, and make recommendations that you will collect and incorporate.

In the execution stage you will present the finding of your analysis, receive feedback, and make revisions as necessary. Here are a few examples of the types of execution stage tasks:

-   Share results
-   Present findings to other stakeholders
-   Address feedback

### Communicate objectives with a project proposal

A project proposal can provide the structure and communication needed for tracking tasks. In addition, project proposals are beneficial for teams when facing challenges that require a high degree of flexibility. As projects progress, the expectations, resources, or even team members can change. This will require adjustments within a project that can impact the overall workflow and delivery date.

Each project proposal contains important information that a team will need to consider before work begins. Below is a brief explanation of some common sections you will find in project proposals. Note that the format of project proposals will vary, so not every section described here will be included in every project proposal.

#### Project title

The title of the project is prominent, usually placed near the top of a document. Effective titles are brief and purposeful. Depending on the context and circumstances surrounding a project, the title can change over time.

#### Project objective

The objective statement is a one to three sentence explanation of what the project is trying to achieve.

#### Milestones

Milestones are groupings of tasks within a project, breaking the work needed into smaller, manageable goals. Milestones assist in the delegation and scheduling of work that needs to be completed within projects. The milestones in the provided example are representative of future end-of-course projects.

#### Tasks

Tasks detail the work that needs to be completed within a milestone. The tasks in the provided example parallel some of the work you will complete in upcoming end-of-course projects.

#### Outcomes

Outcomes are the completed actions or results that allow a project to continue.

#### Deliverables

Deliverables are items that can be shared amongst team members or with stakeholders. These are the end products of work undertaken for a project.

#### Stakeholders

The individuals or groups who are directly involved and have a vested interest in the success of a project. Input from stakeholders can serve as a basis for making decisions throughout a project.

#### Estimated time

At the beginning of a project, the time needed to complete milestones is estimated. As a project develops, these estimates will often need to be updated to account for adjustments to timelines or changes in team members.

### Connect PACE with executive summaries

Executive summaries are documents that summarize the most important points about a project, giving decision makers a brief overview of the most relevant information. They can also be used to help new team members quickly become acquainted with a project. The format is designed to respect the responsibilities of decision makers and or executives who may not have time to read and understand an entire report.

Executive summaries are used across numerous industries and organizations. There are many ways to present information within an executive summary, including software options built specifically for that purpose. In this program, you will primarily consider a one-page format within a presentation slide. Although the design and layout of executive summaries can vary, there are key elements that are common among them.

Executive summaries are used across a wide variety of businesses and typically include the following elements:

#### Project title

A project's theme is incorporated into the executive summary title to create an immediate connection with the target audience.

#### Problem

A statement that focuses on the need or concern being targeted or addressed by the project. Note that the problem can also be referred to as the hypothesis that you’re trying to prove through data analysis.

#### Solution

This statement summarizes a project’s main goal. In this section, actions are described that address the concerns outlined in the problem statement.

#### Details or key insights

The purpose of this section is to provide any additional background information that may assist the target audience in understanding the project's objectives. Determining what details to include depends on the intended audience.

#### Next steps or recommendations

Information that supports the actions the team plans to take. This can also include recommendations for decision makers based on the insights gained over the course of the project. In this section, a data professional may also include general project reflections. When you are adding to this section, include at least one point for recommendations and one for the suggested next steps.

`Any questions, please reach out`

Chiawei Wang, PhD\
Behavioural Data Scientist\
[chw.wng\@outlook.com](mailto:ch.wng@outlook.com)