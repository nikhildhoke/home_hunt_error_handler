# Home Hunt Error Handler

The Home Hunt Error Handler is a Python library designed to handles error handling in real estate application Home Hunt, 
This library also handles the Cognito and DynamoDB errors.
This library provides error responses, validations, and AWS-specific error handling to enhance the backend processes of the Home Hunt application.

## Features
AWS Service Error Handling: Captures and handles errors arising from AWS services to ensure robust backend operations.

Cognito Error Handling: Manages authentication and authorization errors related to AWS Cognito, helping maintain secure user sessions.

DynamoDB Error Handling: Provides mechanisms to deal with common and uncommon DynamoDB errors efficiently.

Form Validation Error Handling: Ensures that user input meets application requirements before processing, reducing incorrect data handling.

## Getting Started

### Prerequisites

Before installing the Home Hunt Error Handler, ensure you have Python 3.6 or later installed. This library also depends on `boto3`, the AWS SDK for Python.

### Installation

Install Home Hunt Error Handler using pip:

```bash
pip install home_hunt_error_handler
