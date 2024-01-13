Introduction
This backend project serves as the foundation for my personal portfolio website. It handles data storage, retrieval, and management for the portfolio content. The API endpoints provided here serve as the backend for the portfolio frontend.

Features
Projects Endpoint: Manage and retrieve information about the projects showcased on the portfolio.
Skills Endpoint: Store and retrieve information about the skills and technologies.
Contact Form Handling: Receive and process contact form submissions from the portfolio frontend.
Getting Started
To set up the project locally, follow the instructions in the Installation section.

Installation
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/portfolio-backend.git


Navigate to the project directory:
bash
cd portfolio-backend


Create and activate a virtual environment:
bash
python -m venv venv
source venv/bin/activate  # On Windows, use 'venv\Scripts\activate'


Install dependencies:
bash
pip install -r requirements.txt


Run database migrations:
bash
python manage.py migrate


Start the development server:
bash
python manage.py runserver
