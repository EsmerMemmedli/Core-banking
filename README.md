🏦 Core Banking System (SQL Project)
📌 Project Overview

This project simulates a Core Banking System database designed using SQL.
It covers the essential entities and relationships used in modern banking systems — such as customers, accounts, transactions, and branches.
The main goal is to understand database design, relationships, and query development in a real-world context.

🗂️ Database Structure
Tables:

Customers

customer_id (PK)

first_name

last_name

email

phone

address

date_of_birth

created_at

Accounts

account_id (PK)

customer_id (FK → Customers.customer_id)`

account_type (e.g., Savings, Current)

balance

opened_date

status

Branches

branch_id (PK)

branch_name

city

manager_name

Transactions

transaction_id (PK)

account_id (FK → Accounts.account_id)`

transaction_type (Deposit / Withdrawal / Transfer)

amount

transaction_date

description

Loans

loan_id (PK)

customer_id (FK → Customers.customer_id)`

loan_type

loan_amount

interest_rate

start_date

end_date

⚙️ Key Features

Database normalization up to 3NF

Proper use of Primary Keys, Foreign Keys, and Constraints

Realistic banking data simulation

SQL queries for:

Account balance updates

Transaction history

Loan calculations

Customer reports


💻 Technologies Used

Oracle SQL 
