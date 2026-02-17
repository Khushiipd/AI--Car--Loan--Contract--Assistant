🚗 Car Loan Contract Review API

This project is a backend API built using FastAPI that analyzes car loan or lease contract documents and extracts important financial details. The goal is to help users understand key terms in their loan agreement before signing it.

Car loan contracts often contain complex financial clauses, penalties, and hidden charges that are difficult to interpret. This system reads the uploaded contract PDF, extracts relevant information such as interest rate, loan term, monthly payment, fees, and penalties, and then evaluates how fair the contract appears.

The API also provides a fairness score and suggests possible negotiation points.

🔍 What the System Does

When a user uploads a contract PDF, the system:

Extracts financial details (APR, loan term, monthly payment, finance amount)

Identifies fees (processing fee, documentation fee, registration fee)

Detects penalties (late payment, early termination, etc.)

Highlights potential risk clauses

Calculates a fairness score

Suggests negotiation strategies

Stores contract data in a database

The output is returned as structured JSON.

🛠️ Technologies Used

Python

FastAPI

SQLite

Uvicorn

Pydantic

PDF text extraction

🎯 Purpose of the Project

This project was built as part of learning backend development and AI-based document analysis. It demonstrates how contract parsing, rule-based evaluation, and API development can be combined into a practical real-world application.