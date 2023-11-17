# ResQ Club Analytics Engineer Assignment

## Problem #1

You have just landed your dream job at ResQ Club, but you need to work with an analyst with poor SQL skills. They’d like to make some queries about ResQ users (people who buy food on the marketplace) but they can only write SELECT statements and don’t know how to join tables. Therefore they’re asking you to provide them the needed data in one presentation table.

The analyst wants to make at least the following queries:

- Query to find the top 10 users by sales who have registered this year (2023).
- Query to identify the users’ favourite provider segments (default offer types). Providers are the companies who sell surplus items on the marketplace.
- Query to find out what is the M1 retention for any given user cohort. A cohort consists of users who made their first order within the same month (M0).

**Deliverable #1:** a simple data pipeline where this kind of presentation table is being created to help the analyst.

## Problem #2

Additionally, the sales team would like to know how public holidays affect the sales numbers and activity on the Finnish market, but the data analyst doesn’t have a clue how to do this. Therefore, you need to make this analysis for the sales team instead:

- Do the sales on public holidays differ from the average daily sales?
- Is the number of selling providers different on public holidays compared to normal days?
- Is the number of purchasing users different on public holidays compared to normal days?

**Deliverable #2:** a simple data pipeline which combines data from relevant sources. Use this pipeline and present the answers to the questions above in a format that’s easily understandable for the sales team.

## Data

- Holiday data from a public API: https://date.nager.at/PublicHoliday/Finland
- Mock database file which can be found from this repository. The database file should contain tables `users`, `orders` and `providers`

## Other instructions

Answer the questions using the above data, save your work in your own Git repository and share it with us within one week from receiving these instructions (different applicants might receive the instructions at different times).

This task should take you 2-4 hours, so don’t overthink it. We might ask you some questions about your solution in an interview later in the process, so be prepared to explain your choices.

There are no strict limitations how you should solve the problems, so you can be creative, but keep in mind that the solution should resemble a “production-level” data pipeline.
