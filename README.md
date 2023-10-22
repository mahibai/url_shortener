# url_shortener
O(1) Coding Club final Task (URL Shortener Django project)


# Django URL Shortener with View Counts

This is a simple URL shortener web application built with Django that also tracks and displays the view counts for each shortened URL. With this application, you can easily create short URLs for long links and monitor how many times each URL has been accessed.

## Table of Contents

1. [Features](#features)
2. [Requirements](#requirements)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Managing Shortened URLs](#managing-shortened-urls)
6. [Contributing](#contributing)
7. [License](#license)

## Features

- Shorten long URLs to more manageable, concise links.
- Track and display view counts for each shortened URL.
- User authentication for creating and managing shortened URLs.
- An admin panel for superusers to oversee the application.
- Clean and responsive design using Django's built-in templating system.

## Requirements

Before you begin, ensure you have met the following requirements:

- Python 3.x
- Django 3.x or higher
- A compatible database (e.g., PostgreSQL, MySQL, SQLite)

## Installation

1. Clone the repository to your local machine:

```bash
git clone https://github.com/your-username/url-shortener.git
cd url-shortener
```

2. Create a virtual environment (optional but recommended):

```bash
python -m venv venv
```

3. Activate the virtual environment:

   - On Windows:

   ```bash
   venv\Scripts\activate
   ```

   - On macOS and Linux:

   ```bash
   source venv/bin/activate
   ```

4. Install the project dependencies:

```bash
pip install -r requirements.txt
```

5. Set up the database by running migrations:

```bash
python manage.py makemigrations
python manage.py migrate
```

6. Create a superuser account to access the admin panel:

```bash
python manage.py createsuperuser
```

7. Start the development server:

```bash
python manage.py runserver
```

8. Access the application in your web browser at `http://localhost:8000`.

## Usage

1. Register or log in as a user to access the URL shortening functionality.

2. To create a short URL, go to the "Shorten URL" page, enter the long URL, and click "Shorten."

3. You will receive a shortened URL that redirects to the original URL, along with the view count.

## Managing Shortened URLs

- To manage shortened URLs, you can log in as a user and go to the "My URLs" page.
- You can view a list of your shortened URLs, including their view counts.
- Edit or delete your shortened URLs as needed.

## Contributing

We welcome contributions from the community. If you want to contribute to this project, please follow these steps:

1. Fork the repository on GitHub.
2. Clone your forked repository to your local machine.
3. Create a new branch for your feature or bug fix.
4. Make your changes and commit them.
5. Push your branch to your fork on GitHub.
6. Create a pull request from your branch to the main repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Feel free to customize this README file to include more specific information about your Django URL shortener. Happy shortening!
