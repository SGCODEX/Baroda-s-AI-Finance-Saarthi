# Baroda's AI Finance Saarthi
 a platform that personalizes financial advice, prioritizes data security and privacy, and caters to a diverse range of users, from young adults to retirees. The platform will empower users to gain personalized financial advice on any topic through simulation, while keeping their financial background in mind.
 Team - CodeCrusaders


# FinWise: Personal Finance AI Advisor

## Overview

FinWise is a web application designed to help users effectively manage their finances. Users can input their expenses, incomes, and financial goals. The integrated AI provides insights, predictions, and financial advice based on user data.

## Features

- **Expense Tracking**: Record and categorize your daily expenses.
- **Income Management**: Keep track of your various income sources.
- **Financial Goals**: Set and monitor your financial goals.
- **AI Insights**: Receive AI-driven feedback on spending habits, saving strategies, and investment opportunities.

## Prerequisites

- Python (>= 3.6)
- Django
- PostgreSQL (or another database of your choice, but instructions may vary)
- Other dependencies listed in `requirements.txt`

## Setup

### Clone the Repository:

```bash
git clone https://github.com/yourusername/FinWise.git
cd FinWise
```

### Setup Virtual Environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### Install Dependencies:

```bash
pip install -r requirements.txt
```

### Database Setup:

Update DATABASES setting in settings.py with your database credentials.

Then, apply migrations:

```bash
python manage.py migrate
```

### Run Development Server:

```bash
python manage.py runserver
```

Navigate to http://127.0.0.1:8000/ in your browser.

### Create Superuser (Optional):

To access the admin interface, create a superuser:

```bash
python manage.py createsuperuser
```

Access the admin site at http://127.0.0.1:8000/admin/.

### git Contributions

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
