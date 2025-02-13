# FastAPI Book Project

An API service for managing books, built with FastAPI

## Project Overview

This project implements a book management API with the following features:
- Endpoints for book operations
- Automated testing and deployment pipeline and workflow
- Nginx reverse proxy configuration


## Technical Stack

- **Backend Framework**: FastAPI
- **Web Server**: Nginx
- **Testing**: pytest


## Local Development Setup

1. Clone the repository:
```bash
git clone https://github.com/Noah-V/fastapi-book-project-noah.git
cd fastapi-book-project-noah
```

2. Set up a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: .\venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the application:
```bash
uvicorn app.main:app --reload
```

5. Access the API documentation:
- Swagger UI: http://localhost:8000/docs
- ReDoc: http://localhost:8000/redoc

## Testing

Run the test suite:
```bash
pytest
```

## CI/CD Pipeline

### Continuous Integration
The CI pipeline runs automatically on pull requests to the main branch:

### Continuous Deployment
The CD pipeline activates when changes are merged to main:


## Deployment

1. Set up your production server
2. Configure environment variables
3. Install dependencies
4. Run the application with a production server (optional)
5. Set up Nginx reverse proxy
6. Enable HTTPS (optional but recommended)

## Tech Stack
[HNG Python Developers](https://hng.tech/hire/python-developers)
