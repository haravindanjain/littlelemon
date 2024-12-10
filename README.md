# Little Lemon Restaurant Website

A Django-based web application for the Little Lemon restaurant

## Features

### Homepage
- Navigation links to `About`, `Menu`, and `Book` pages.
- Special offers and quick navigation sections.

![Homepage Screenshot](images/home.png)

### About Us Page
- Details about the restaurant's history and inspiration.

![About Us Screenshot](images/about.png)

### Menu Page
- Lists menu items in alphabetical order with names and prices.
- Clickable links for detailed menu item pages.

![Menu Page Screenshot](images/menu.png)

### Reservation Page
- Allows users to fill in a reservation form with fields like name, guest count, and comments.
- Integrated Google Maps for location visualization.

![Reservation Page Screenshot](images/book.png)

---

## Installation & Setup

### Clone the repository and navigate to the project directory:
```bash
git clone https://github.com/haravindanjain/littlelemon.git
cd littlelemon
```

### Create and activate a virtual environment:
```bash
python3 -m venv venv
source venv/bin/activate  
```

### Install dependencies:
```bash
pip3 install -r requirements.txt
```

### Apply migrations:
```bash
python3 manage.py migrate
```

### Run the server:
```bash
python3 manage.py runserver
```
- Access the app in your browser at: http://127.0.0.1:8000