# Simple Expense Tracker using Flask

This is a simple expense tracker application built using Flask. The application allows users to register, log in, and manage their expenses. Users can add expenses, view a summary of their expenses, and categorize their expenses.

## Features

- User Registration and Authentication
- Add Expenses
- View Expense Summary by Month and Year
- Categorize Expenses

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/MadhankumarA/Simple-Expense-tracker-using-flask.git
    ```
2. Change into the project directory:
    ```bash
    cd Simple-Expense-tracker-using-flask
    ```
3. Create a virtual environment:
    ```bash
    python3 -m venv venv
    ```
4. Activate the virtual environment:
    ```bash
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```
5. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Set up the database:
    ```bash
    flask db init
    flask db migrate
    flask db upgrade
    ```
2. Run the application:
    ```bash
    flask run
    ```
3. Open your web browser and navigate to `http://127.0.0.1:5000`.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request.


## Acknowledgments

- Flask documentation
- GitHub for repository hosting

## Contact

For any questions or feedback, please reach out to [madhanannadurai536@gmail.com](mailto:madhanannadurai536@gmail.com).

