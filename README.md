# Invoice Generator API

## 1. Overview
Invoice Generator API is an app that generates PDF invoices for paid services.
It is designed for paid service providers such as sellers or individual entrepreneurs. 
A seller enters their own and the client's contact info, services provided and their prices while the app generates a PDF invoice containing all the provided information.

## 2. Features
- Invoice creation
- Adding services
- Viewing all invoices
- Viewing an individual invoice
- Generating a PDF file with the invoice's info
- Changing the invoice's status (Paid | Unpaid)

## 3. Tech stack

- Python - used for building Backend logic and managing data
- PostgreSQL - stores project data in tables and maintains relationships between them
- SQLAlchemy - manages the database using Python code
- FastAPI - creates and manages API endpoints
- Pydantic - validates API input and output
- Pytest - tests application behavior
- Docker - containerizes the application
- Alembic - manages database migrations

## 4. Architecture

The application is developed using a layered architecture.
Its main structure looks like this: API → Service → Repository

Repository - sends queries to the database.
Service - manages business logic before sharing data with the repository
API - passes validated input to the service and sends the result.

## 5. Getting Started




