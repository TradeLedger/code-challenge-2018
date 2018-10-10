
# Welcome to the Trade Ledger Code Challenge!

Data is the fuel for modern banking technology. The ultimate goal of this project is to support the bank to automatically process company's invoice data and highlight interesting patterns in the data. You are now part of our awesome global engineering team helping to deliver this new component of our platform for one of the world’s largest banks.

Imagine you are working in a team of Back-End Developers, API Developers, Front-End Developers and Decision Scientists coming together in this sprint to develop the new component. Using your particular skill set we’re hoping you can add significant value to the team.

## The Challenge

The Trade Ledger platform periodically collects invoice data from 3rd party systems, e.g in a JSON format, which is used in other processes. The component you are working on is responsible for scanning the raw data and generating an output to be used by the risk team. This output could be in the form of APIs, Analytics or UI dashboards and looks to identify any interesting data patterns and/or anomalies which could be useful for the team. In this context examples of “risks” are something like:

- Risk of the invoice not being paid at all. 
- Risk of the invoice not being paid on time. 

Feel free to identify any data patterns and risks that you come across. The project can be tackled from different perspectives and there is no right or wrong way to approach it. 


### Back-End / API Developers
Implementation in strongly typed, object oriented programming language such as Java or TypeScript. 
E.g. Create an end-point to help support querying the data
I.e. Java, Node

Quality Engineering!

### Statisticians & Decision Scientists
Implementation of advance statistical models or simple data distributions that look for patterns in the dataset.
E.g. Create a number of distributions to identify trends within the data
I.e. Python, R

Actionable Insights!


### Front-End & UI/UX Developers
Implementation using interactive & configurable dashboards that bring the data to life for the bank.
E.g. Create a dashboard for the risk team to view key metrics on the file
I.e React, Angular, HTML

Beautiful Business!


## Sample data

The example data (invoices.json) contains approx 10,000 invoices. 


## Solution guidelines
- Feel free to use any open source libraries or frameworks which you find helpful. 
- The final code must compile and run without any errors.
- Please provide clear instructions how to execute the code. 
- Any instructions should be provided in a Readme.md file
- Any reports created may be in any format (HTML or PDF is preferred) and should include a list of patterns which you identified based on the dataset. 


## Assessment Criteria
- Quality & Readability of your code 
- Ease of execution of your code
- Clarity of your instructions and supporting documentation
- Creativity of your approach


## Submitting your solution

We like to encourage open collaboration and communities so we’d prefer you to submit your solution within a GitHub repository and send us a link. This way, your hard work is available for everyone to see!

## Data Descriptions

Sample Record

 "number" : "INV0",
 
    "issueDate" : "2015-01-01",
  
    "dueDate" : "2015-03-02",
  
    "paymentDate" : "2015-03-03",
  
    "status" : "PAID",
  
    "industry" : "GOVERNMENT",
  
    "amount" : 10563,
  
    "amountPaid" : 10563,
  
    "company" : "Office of Justice",
  
    "companyId" : 24
  

---------

Number = The invoice number which is the identifier for an invoice due to be paid by the company. Invoice numbers are not unique across companies.

IssueDate = The date at which the company was issued the invoice by a supplier. Suppliers are not listed in the dataset.

DueDate = The expected date of payment (usually between 30-90 days after issue date)

PaymentDate = The date at which the invoice has been paid by the company.

Status = Relates to the payment made by the company.
- “OPEN” - Invoice has not been paid but has not yet past its due date
- “DEFAULTED” - Invoice has not been paid and has gone past the due date
- “PAID” - Full invoice amount has been paid 
- “PARTIALLY_PAID” - Partial invoice amount has been paid 

Industry = The industry sector in which the company operates

Amount = The total value of the invoice owed by the company

Amountpaid = The value of the invoice paid by the company

Company = The company which has made a commitment to repay the invoice.

CompanyID = Numerical identifier for the company. Company can appear multiple times.


 ## BEST OF LUCK FROM ALL THE TRADE LEDGER TEAM!


