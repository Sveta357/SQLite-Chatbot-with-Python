# SQLite-Chatbot-with-Python
This project provides a Python interface to interact with a SQLite database using natural language queries processed by OpenAI's GPT models. It leverages the power of OpenAI's GPT to parse natural language queries into SQL, execute them against a SQLite database, and return the results in a human-friendly format.

Features
SQLite Database Connection: Easily connect to a SQLite database to perform operations.
Natural Language Queries: Utilize OpenAI's GPT models to interpret natural language and run corresponding SQL queries.
Error Handling: Gracefully handles operational errors by catching exceptions and returning user-friendly messages.

Getting Started
Prerequisites
Python 3.x
SQLite3
OpenAI API key

Installation
Clone the repository:
git clone https://github.com/yourusername/sqlite-chatbot-interface.git
cd sqlite-chatbot-interface

Install dependencies:
Ensure you have Python 3 installed. 
This project requires the sqlite3 module (included with Python standard library) and pydantic for data validation.
pip install pydantic openai

Set up your OpenAI API key:
You need an API key from OpenAI to use GPT models. Once you have your key, you can set it as an environment variable or directly in your code (not recommended for production).
export OPENAI_API_KEY='your_openai_api_key_here'

Contributing
Contributions are welcome! If you have suggestions for improving this project, feel free to fork the repo, make changes, and submit a pull request.

