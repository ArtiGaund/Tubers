# Tubers Project

Tubers is a Django-based web application designed to facilitate the hiring of YouTubers. The project includes features for managing YouTubers, teams, and services, as well as providing a user-friendly interface for visitors to explore and contact YouTubers.

## Table of Contents

- [Features](#features)
- [Project Structure](#project-structure)
- [Setup and Installation](#setup-and-installation)
- [Running the Project](#running-the-project)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

---

## Features

- **User Authentication**: Register, login, and manage user accounts.
- **YouTuber Management**: Add, edit, and display YouTubers with details like city, age, height, and more.
- **Team Management**: Showcase team members with roles and social media links.
- **Contact Form**: Allow users to reach out via a contact form.
- **Admin Panel**: Manage content using Django's admin interface.
- **Responsive Design**: Mobile-friendly UI using Bootstrap.

---

## Setup and Installation

### Prerequisites

- Python 3.8 or higher
- Django 4.1
- SQLite (default database)
- Node.js (for managing frontend assets, optional)

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/tubers.git
   cd tubers```

2. Create a virtual environment:
```python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate```

3. Install dependencies:
```pip install -r requirements.txt```

4. Run migrations:
```python manage.py migrate```

5. Create a superuser:
```python manage.py createsuperuser```

6. Collect static files:
```python manage.py collectstatic```

Running the Project
1. Start the development server:
```python manage.py runserver```

2.Open your browser and navigate to:

    * Frontend: http://127.0.0.1:8000/
    * Admin Panel: http://127.0.0.1:8000/admin/
