# Stock Market Portfolio Management System

This system is designed to help **traders, investors, analysts, government agencies, and executives** efficiently manage and analyze stock market data. It provides a robust database solution optimized for handling large volumes of financial data and facilitates data retrieval and analysis.

## Features

- **Portfolio Management**: Allows users to manage stock portfolios, track stock performance, and analyze historical data.
- **Data Management**: Efficiently stores and organizes stock market data for quick retrieval.
- **Data Analysis**: Provides features for generating insights and reports based on market trends and stock performance.
  
## Tech Stack

- **Programming Language**: Python
- **Database**: SQL
- **User Interface**: Command-Line Interface (CLI)

## Folder Structure

The relevant code is located in the following directory structure:

Phase 4/
│
└── 38/               # Team folder
    └── Source Code/   # Source code folder
        ├── CLI.py     # Python script for the command-line interface
        └── DB_Script.sql  # SQL script for setting up the database
## Prerequisites

Before running the system, ensure that you have the following installed:

- Python 3.x
- A SQL-compatible database (e.g., MySQL, PostgreSQL, SQLite)
- Necessary Python libraries (can be installed via `requirements.txt` or manually)
## Installation Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Snowy02/portfolio-management.git
   cd portfolio-management/Phase 4/38/Source Code
2.**Run the DB_Script.sql file to initialize the database schema**:

    mysql -u [username] -p [password] [database_name] < DB_Script.sql
3.Run the CLI interface:

    python3 CLI.py
  
**USAGE**
Portfolio Management:

Use the CLI interface to add, update, and manage stock portfolios.
View stock performance, historical data, and real-time trends.
Data Analysis:

Perform analysis using built-in functions within the CLI to generate insights and reports.

Database Management:

Manage and query the stock market database using SQL queries or within the CLI interface for customized operations.
Future Improvements
Implementing a graphical user interface (GUI) for easier portfolio management.
Adding support for real-time stock market data through API integration.
Advanced analytics with machine learning models for stock trend predictions.

