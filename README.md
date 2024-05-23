
# Full Backend Django REST Template

This repository serves as a template for developing backend applications using Django REST Framework. It provides a foundation for building scalable and maintainable APIs.

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Technologies Used](#technologies-used)
4. [Contributing](#contributing)
5. [License](#license)

## Installation

To install and run the backend application locally, follow these steps:

1. Clone this repository to your local machine:

   ```
   git clone <repository-url>
   ```

2. Navigate into the project directory:

   ```
   cd full_backend_django_rest_template
   ```

3. Install dependencies:

   ```
   pip install -r requirements.txt
   ```

4. Set up the database (MariaDB in this case):

   ```
   python manage.py migrate
   ```

## Usage

To start the Django server, run the following command:

```
python manage.py runserver
```

Access the application in your web browser at `http://localhost:8000`.

## Technologies Used

- Django REST Framework
- MariaDB (or any other database of your choice)
- Python

## Contributing

Contributions are welcome! If you'd like to contribute, please fork the repository and create a pull request with your changes. Ensure to follow the existing code style and conventions.

## License

This project is licensed under the [MIT License](LICENSE).
