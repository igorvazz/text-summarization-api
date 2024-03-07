# Text Summarization API
![Continuous Integration and Delivery](https://github.com/igorvazz/text-summarization-api/workflows/Continuous%20Integration%20and%20Delivery/badge.svg?branch=main)

The Text Summarization API is a Python-based project designed to provide a simple yet effective way to summarize text content. Built with FastAPI, Tortoise ORM, and Pydantic, it offers a robust backend service that can handle text summarization requests efficiently. This project is structured to support Test-Driven Development (TDD) and follows best practices for API development and testing.

## Key Features

- **Text Summarization**: Allows users to submit URLs for text content that needs to be summarized.
- **RESTful API**: Provides a clean interface for interacting with the service, including endpoints for creating and retrieving summaries.
- **Asynchronous Support**: Leverages FastAPI's asynchronous capabilities to handle requests efficiently.
- **Database Integration**: Utilizes Tortoise ORM for database operations, supporting asynchronous interactions with the database.
- **Pydantic Models**: Uses Pydantic for data validation and schema definition, ensuring data integrity throughout the application.
- **Test-Driven Development**: Includes a comprehensive suite of tests, demonstrating how to implement TDD with FastAPI and Tortoise ORM.

## Project Structure

- `app/`: Contains the core application code, including models, schemas, and API routes.
- `tests/`: Houses all test cases, showcasing how to test FastAPI applications with Tortoise ORM.
- `models/tortoise.py`: Defines Tortoise ORM models for the application.
- `config/`: Configuration settings for the application, including database settings.
- `services/`: Service layer for handling business logic, separate from API logic.

## Technologies

- **FastAPI**: A modern, fast (high-performance) web framework for building APIs with Python 3.7+.
- **Tortoise ORM**: An easy-to-use asyncio ORM (Object Relational Mapper) inspired by Django.
- **Pydantic**: Data validation and settings management using Python type annotations.
- **pytest**: A framework for easily building simple and scalable test cases.
- **Docker**: Used for containerizing the application and its dependencies for easy deployment.

## Getting Started

To get started with the Text Summarization API, clone the repository and install the required dependencies. Ensure you have Docker installed if you wish to containerize the application.

```bash
git clone https://github.com/yourgithubusername/text-summarization-api.git

cd text-summarization-api/

docker compose up -d --build
```

### TODO

- [ ] Implement LLM for summarization
- [ ] Deploy the application to AWS
- [ ] Monitor and optimize the application performance
