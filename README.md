# SQL_CASE_to_Python

It is important to be able to perform effective processes, regardless of context. Many data specialists get stuck as the 'SQL SME' (Subject Matter Expert) or the 'Python SME'. But to formally trained databasers, data is data is data is... It matters not what the favored language is, but how we ask the question. This implies the same question can be articulated in more than a single langauge, which is absolutely true.

The technical challenge is, does the syntax support the same level of efficiency? In actual runtimes, no.
Not even close, you should use the best tool for the job because tools should be optimized for their use-cases.
But in terms of O-runtime, this is true.
And here are a few ways to convert the previous SQL CASE answer to Python while retaining the optimized O-runtime.

However, keep in mind databases have rules on how the data is curated, Relational Databases are more explicit than most.
There are change rules protecting data points, there are rules protecting data types, there are rules dictating who can view/change what, there are rules preventing NULL AND duplicate data points in indexed fields, etc. And transparency of the governance of all the rules.
Relational databases are so strict and structured, accountants love them because the transparency and internal controls are 'baked in'.
There's a lot that goes on into maintaining the backend.
