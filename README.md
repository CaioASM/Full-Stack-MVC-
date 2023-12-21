# Full-Stack MVC Application

## Overview
This Full-Stack MVC application is designed for managing and tracking expenses. It utilizes a Model-View-Controller (MVC) architecture, incorporating Node.js and Express for the backend, and React for the frontend.

## Key Features
- Track and manage expenses
- Perform Create, Read, Update, and Delete (CRUD) operations on expense data
- User-friendly interface for seamless interaction

## Technology Stack
- **Frontend**: React
- **Backend**: Node.js, Express
- **Database**: PostgreSQL

## Database Schema
The application employs a PostgreSQL database with the following schema:

### Table: `expenses`
- `expense_id`: SERIAL PRIMARY KEY
- `title`: VARCHAR(30) NOT NULL
- `price`: DECIMAL(10, 2) NOT NULL
- `category`: VARCHAR(30) NOT NULL
- `essential`: BOOLEAN NOT NULL
- `created_at`: TIMESTAMPTZ NOT NULL

[View Database Schema](https://github.com/CaioASM/Full-Stack-MVC/blob/main/models/expense.sql)

## Installation and Setup
1. Clone the repository:
git clone https://github.com/CaioASM/Full-Stack-MVC.git

2. Navigate to the project directory:
cd Full-Stack-MVC

3. Install dependencies:
npm install

4. Set up the environment variables in a `.env` file based on your database configuration.

5. Start the server:
npm run server


6. Navigate to the `view` directory and start the React application:
cd view
npm start


7. The application should now be running on `http://localhost:3000`.

## Usage
- Add, view, update, and delete expenses through the web interface.
- Filter and sort expenses based on categories and dates.

## Contributing
Contributions are welcome. Please adhere to the standard fork-and-pull request workflow for contributions.

## License
This project is licensed under the MIT License.
