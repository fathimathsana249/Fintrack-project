# Fintrack-project
FinTrack Pro is a command-line based personal finance management system developed using Python, SQLite, and SQLAlchemy ORM.
This project helps users efficiently manage their daily expenses, categories, monthly budgets, and spending analytics through a simple and interactive CLI interface.

The system allows users to add, update, delete, and search expenses, organize them using categories, set monthly budget limits, and receive alerts when expenses exceed the budget. It also provides category-wise spending analysis using SQL queries.

This project demonstrates the practical implementation of Object Relational Mapping (ORM), database relationships, CRUD operations, and real-world finance tracking logic.

Key Features
	•	Add and manage expense categories
	•	Add, update, and delete expenses
	•	Search expenses by date
	•	Category-wise expense analytics
	•	Set monthly budget
	•	Budget exceeded alert system
	•	SQLite database with SQLAlchemy ORM
	•	Simple and interactive CLI menu

 Technologies Used
	•	Python
	•	SQLite
	•	SQLAlchemy ORM
	•	Command Line Interface (CLI)

 Database Structure

The project uses 4 tables:
	•	categories – Stores expense categories
	•	expenses – Stores expense records
	•	subscriptions – Stores subscription details
	•	budgets – Stores monthly budget limits

A one-to-many relationship exists between Category and Expense tables

 Learning Outcomes
	•	Understanding ORM concepts using SQLAlchemy
	•	Implementing database relationships and foreign keys
	•	Performing CRUD operations
	•	Writing raw SQL queries for analytics
	•	Building real-world CLI-based applications
