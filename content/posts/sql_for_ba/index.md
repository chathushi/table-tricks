---

title: "What Do Business Analysts Actually Need to Know About SQL?"
date: 2021-10-16T12:40:47Z
draft: false
image: "ba_sql.webp"
author: "Chathushi Thalpage"
theme: "full"

ruby: true
fraction: true
fontawesome: true
linkToMarkdown: true
rssFullText: false

toc:
enable: true
auto: true
code:
copy: true

share:
enable: true
------------

If you are planning to work as a business analyst or if you are a novice to the role of business analyst, you must be having the question of “do I really need to know SQL for my career”. Then this article would be the best place for you to solve your problem. Also, this would help you to identify the most important areas of SQL that you need to aware as a business analyst.

Simply, Structured Query Language (SQL) is used to interact with databases. Most of the time SQL is one of the most commonly requested skill by employers when they looking to hire a business analyst. But this situation may change based on the nature of the company. If you are going to work for an organization that mainly purchases and implements software instead of building themselves, may not going to use SQL for their work. A company that does a lot of custom built applications and builds their own software in house may definitely look for the SQL competency, when they hire a business analyst. So knowing SQL will be a great advantage and a plus point for you to apply to a any kind of company at anytime.

Typically, business analysts don’t use everything that is in SQL. They use only a small subset of SQL. Therefore, business analyst doesn’t need to learn SQL in depth. It is enough to learn the basics of SQL that will help them to do better in their data driven projects .

Let’s consider the areas of SQL that a business analyst is expected to use. DML and DQL are the major categories of broader SQL, which should be concerned by a business analyst . Under DML (Data Manipulation Language), we will be considering the following operators.

1. INSERT : Enter data into a database.

2. UPDATE : Update data.

3. DELETE : Delete data.

DQL (Data Query Language) deals with “SELECT” operator which retrieves data from a database.

We will take an example to understand how the above SQL operators can be used to handle data in a database.

Eg : Let’s say we have a table in our company database named as “CUSTOMER”, including the customer data of our company. Then let’s see how a business analyst needs to use SQL to handle the following scenarios.

*Scenario 1 : Inserting data of a new customer(David Alfred) to the CUSTOMER table.*

**INSERT INTO CUSTOMER(CustomerName, City, Country) VALUES (‘David Alfred’, ‘Melbourne’, ‘Australia’);**

Here customer ID will be automatically updated.

*Scenario 2: Updating the city of the above customer as “Sydney.” (Assume ‘CustomerID’ is 24)*

**UPDATE CUSTOMER SET City = ‘Sydney’ WHERE CustomerID = 24;**

*Scenario 3 : Deleting the data of the customer(David Alfred) from the CUSTOMER table.*

**DELETE FROM CUSTOMER WHERE CustomerName=’David Alfred’;**

You can get a basic idea about how to handle data using SQL by using the above simple example. There are lots of online sources that you can refer to improve your SQL knowledge. So I recommend you to go through on those sources to enhance your experience with SQL.

Hope now you are aware of how to be a better business analyst with SQL. If you enjoyed the article, please hit clap icon.

Thank you for reading…


