# Contributing to the Review App API

Thank you for your interest in contributing to the Review App API! We appreciate your support and welcome your contributions to help enhance and improve the project. Please read through the following guidelines to get started.

Table of Contents
Prerequisites
Contributing Guidelines
Setting Up the Development Environment
Submitting a Pull Request (PR)
Code of Conduct
Prerequisites
Before you begin contributing to the backend of the Review App, please ensure you have the following prerequisites installed and configured on your local machine:

Docker: To set up and manage the development environment.
Git: To clone and manage the project repository.
Node.js and npm: To install project dependencies.
Yarn: To manage Node.js packages effectively.
Contributing Guidelines
We follow these guidelines for contributing:

Fork the backend repository to your GitHub account.

Clone your forked repository to your local machine:

bash
Copy code
git clone https://github.com/yourusername/review-app-api.git
Navigate to the backend project directory:

bash
Copy code
cd review-app-api
Create a new branch for your contribution:

bash
Copy code
git checkout -b feature-name
Make your changes and ensure your code follows our coding standards and practices.

Test your changes locally to ensure they work as expected.

Commit your changes with clear and concise commit messages:

bash
Copy code
git commit -m "Add feature: your feature description"
Push your changes to your GitHub fork:

bash
Copy code
git push origin feature-name
Create a pull request (PR) to the main repository's main branch.

Setting Up the Development Environment
To set up the development environment locally, follow these steps:

Clone the backend repository:

bash
Copy code
git clone https://github.com/yourusername/review-app-api.git
cd review-app-api
Run Docker Compose to set up the development environment:

bash
Copy code
docker-compose up -d
Install project dependencies using Yarn:

bash
Copy code
yarn
Copy the .env.example file to .env.local and configure the following environment variables in the .env.local file:

env
Copy code
DATABASE_URL=postgresql://postgres:password@localhost:5432/review
JWT_SECRET=superman123
You can replace superman123 with any secret of your choice.

Run database migrations to set up the database:

bash
Copy code
yarn migrate:latest
Start the local development server:

bash
Copy code
yarn local
The backend will be up and running on port 8000.

Submitting a Pull Request (PR)
When you're ready to submit your changes, create a pull request (PR) to the main repository's main branch following our guidelines. Be sure to provide a clear description of your changes in the PR, and one of our maintainers will review it.

Code of Conduct
Please be aware that we have a Code of Conduct that all contributors are expected to follow. Please read and adhere to it throughout your contribution journey.

We appreciate your contributions and look forward to collaborating with you to improve the Review App API!
