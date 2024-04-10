## Django Template

This template streamlines the setup process for Django projects
using [Cookiecutter](https://github.com/cookiecutter/cookiecutter-django), enabling swift creation of projects with
relevant configurations.

### Getting Started

1. **Setup Repository**: Begin by creating a new empty repository on GitHub.

2. **Virtual Environment**: Set up a virtual environment for your project:

```bash
python3 -m venv venv
source venv/bin/activate
```

Install Cookiecutter: Utilize pip to install Cookiecutter:

```pip
pip3 install cookiecutter
```

Project Creation: Execute the following command to create your project based on the template:

```bash
cookiecutter https://github.com/Tmuat/django-template
```

Install Dependencies: Install project dependencies using pip:

```pip
pip3 install -r requirements.txt --no-cache-dir
```

Install Development Dependencies: For development, install additional dependencies:

```pip
pip3 install -r requirements-dev.txt --no-cache-dir
```

With these steps completed, your Django project is ready for development!

### Template Development
This repository contains its own pre-commit configuration and gitignore files, which will also be replicated inside the
Django directory for use in your own repo.

The following correctly configures the pre-commit Github hook.

```bash
pre-commit install
```
