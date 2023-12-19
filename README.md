# palm_sql_llama_index

# Streamlit Chat Pack

This repository contains code for a Streamlit Chat Pack that allows users to input natural language queries about a database and receive the corresponding SQL queries in response. The code is compatible with databases stored in SQLite.

The chat pack utilizes the following libraries: 
- streamlit
- sqlalchemy
- typing
- llama_index
- pandas
- sqlite3
- openai

The main file `app.py` contains the code for initializing the chat pack, creating a sidebar for the database schema viewer, handling user input and returning SQL queries, and displaying the chat history.

## Getting Started

1. Clone this repository to your local machine.
2. Set up the required libraries (`pip install` or `conda install`) listed in the `requirements.txt` file.
3. Launch the chat pack by running `StreamlitChatPack(run_from_main=True).run()` in the command line.

## Usage

1. In the sidebar, select a table to view the data for that table.
2. In the main window, enter a natural language query about the database in the chat input box, and then press "Enter".
3. View the SQL query generated in response in the main window.
