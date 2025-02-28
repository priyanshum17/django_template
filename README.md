# Django Template

This is a simple template for a Django project. It contains a basic directory structure and is meant to enforce industry standards.

## Directory Structure

```bash
.
├── CONTRIBUTORS.txt       # List of project contributors
├── LICENSE                # License information for the project
├── README.md              # Project documentation (this file)
├── config
│   ├── __init__.py        # Makes the config directory a Python package
│   └── settings.json      # Project-specific settings (e.g., environment variables, config settings)
├── docs
│   └── CHANGELOG.md       # Logs of project changes and version history
├── manage.py              # Command-line utility for managing Django projects
├── requirements.txt       # List of dependencies required to run the project
└── src
    ├── __init__.py        # Makes the src directory a Python package
    ├── core               # Core functionality of the project (models, views, etc.)
    │   └── __init__.py    # Makes the core directory a Python package
    └── static
        ├── css
        │   └── project.css # Main stylesheet for the project
        ├── fonts
        ├── images
        │   └── favicons
        │       └── favicon.ico # Project favicon
        └── js
            └── project.js  # Main JavaScript file for the project
```

## Key Files & Their Purpose

- **CONTRIBUTORS.txt**: This file contains a list of contributors to the project. It helps acknowledge all contributors to the project, ensuring proper credit.
- **LICENSE**: The LICENSE file contains the licensing terms for the project. It defines how others can use, modify, and distribute the project.
- **README.md**: This file provides a detailed explanation of the project, including setup instructions, requirements, and other documentation.
- **config/settings.json**: This JSON file holds the configuration settings for your Django project. This is where you define environment variables, project settings, or any other global configuration that can be loaded at runtime.
- **docs/CHANGELOG.md**: The changelog keeps track of all the updates, changes, bug fixes, and new features in the project. It's essential for maintaining a history of the project over time.
- **manage.py**: This is a command-line utility that comes with Django. It allows you to interact with the project via the terminal (e.g., running the development server, making migrations, etc.).
- **requirements.txt**: This file contains a list of Python dependencies that are required to run the Django project. You can install all dependencies with `pip install -r requirements.txt`.
- **src/core**: This is where the main application code resides (e.g., models, views, and templates). It's the heart of the Django project.
- **src/static**: Contains static assets (CSS, JS, images, etc.) for the project. This is where you'll add files that don't change dynamically but are used across pages, such as styling, scripts, and images.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/priyanshum17/django_template
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Start the development server (after you put the code in):
   ```bash
   python manage.py runserver
   ```

For more detailed instructions on working with Django, refer to the official documentation: [Django Documentation](https://docs.djangoproject.com/en/stable/)


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
