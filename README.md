#  Simple Banking System
##  Project Overview
The Simple Banking System project is an SQL-based database solution that models essential banking operations such as customer management, account handling, and transaction tracking. It focuses on logical database design, data integrity, and the practical use of SQL for managing financial data. The project is intended for learning, skill demonstration, and portfolio presentation, with a modular structure that reflects real-world database development practices.

## Objectives


📍Design a normalized relational database for a banking system

📍Implement core banking entities using SQL scripts

📍Demonstrate CRUD operations

📍Track customer transactions and balances

📍Provide analytical and reporting queries

## System Scope

The system supports:

📍Customer registration and management

📍Multiple accounts per customer

📍Deposit and withdrawal transactions

📍Transaction history tracking

📍Balance reporting

This is a logical database model only; no application-layer logic is included.

## Database Design Summary
Core Tables

📍Customers – stores customer information

📍Accounts – stores bank account details

📍Transactions – records all financial transactions


## Relationships

One customer → many accounts

One account → many transactions

## SQL Scripts Description
 📍create_tables.sql

Contains all CREATE TABLE statements and foreign key relationships.

📍insert_sample_data.sql

Contains sample records for customers and accounts to test the system.

📍transactions.sql

Contains SQL statements for:

Deposits

Withdrawals

Balance updates

## Reporting_queries.sql

Contains queries for:

📍Customer account balances

📍Transaction history

## Basic summaries for decision-makingCustomer registration and management

📍Multiple accounts per customer

📍Deposit and withdrawal transactions

📍Transaction history tracking

📍Balance reporting

