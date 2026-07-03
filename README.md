# AI-SQL RAG Chatbot

## Project Overview

AI-SQL RAG Chatbot is an AI-powered application that converts natural language (English) questions into SQL queries using a Large Language Model (LLM) and Retrieval-Augmented Generation (RAG). The chatbot understands the database schema, generates accurate SQL queries, executes them on the connected database, and returns the results in a user-friendly format.

## Project Goal

The main objective of this project is to make database interaction easier for users who do not know SQL. Instead of writing SQL queries manually, users can simply ask questions in plain English.

## Problem Statement

Many users find SQL difficult to learn and write. This project eliminates the need for SQL knowledge by allowing users to communicate with the database using natural language.

## Key Features

* Convert English questions into SQL queries.
* Retrieve database schema using RAG.
* Generate optimized SQL with an LLM.
* Execute SQL queries safely.
* Display query results in an easy-to-understand format.
* Support multiple database tables.
* User-friendly chatbot interface.

## Technology Stack

Frontend:

* React.js (Planned)

Backend:

* Python
* FastAPI

Artificial Intelligence:

* Large Language Model (LLM)
* LangChain
* RAG (Retrieval-Augmented Generation)

Vector Database:

* FAISS or ChromaDB

Database:

* MySQL

Version Control:

* Git
* GitHub

## Project Workflow

1. User enters a question in English.
2. The chatbot retrieves the relevant database schema using RAG.
3. The LLM converts the question into an SQL query.
4. The generated SQL query is validated.
5. The query is executed on the database.
6. The results are returned to the user.

## Example

User Question:
Show all employees whose salary is greater than 50000.

Generated SQL:
SELECT * FROM employees WHERE salary > 50000;

## Future Enhancements

* Support INSERT, UPDATE, and DELETE operations with proper authorization.
* Query history.
* User authentication.
* Dashboard with analytics.
* Support for multiple database engines.
* Voice-based query support.
* Fine-tuned LLM for higher SQL accuracy.

## Project Status

Current Status:
Project Planning and Documentation Phase

## Author

Name: Pavan Kale

## License

This project is created for learning, portfolio development, and educational purposes.
