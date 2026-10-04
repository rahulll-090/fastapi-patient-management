# FastAPI Patient Management System

A REST API-based Patient Management System built using FastAPI and Pydantic.

## Features

- Create patient
- Retrieve all patients
- Retrieve patient by ID
- Filter patients by city
- Update patient details
- Delete patient
- BMI calculation
- BMI health verdict
- Pydantic validation
- JSON file storage

## Technologies

- Python
- FastAPI
- Pydantic
- Uvicorn
- JSON

## Installation

Clone the repository:

git clone https://github.com/rahulll-090/fastapi-patient-management.git

Move into the project:

cd fastapi-patient-management

Install dependencies:

pip install -r requirements.txt

change the file path in the CRUD file

change the file path to the cloned patients.json path 

Run the server:

uvicorn main:app --reload

## API Documentation

After starting the server, open:

http://127.0.0.1:8000/docs
