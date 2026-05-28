# Project Specification

This project is from **Python Crash Course** book, from Eric Matthes.

We’ll write a web app called Learning Log that allows users to log the topics they’re interested in and make journal entries as they learn about each topic. The Learning Log home page will describe the site and invite users to either register or log in. Once logged in, a user can create new topics, add new entries, and read and edit existing entries.

# Commands

To activate the virtual environment, use the following command:

```bash
source .venv/bin/activate
```

To stop using the virtual environment, use the following command:

```bash
deactivate
```

Enter the `runserver` command to view the project in its current state. Django should start a server called the development server, so you can view the project on your system to see how well it works.

```
python manage.py runserver
```

# Building a Page

1. Specify a URL pattern. (learning_logs/urls.py)
2. Write a view function. (learning_logs/views.py)
3. Write a template (learning_logs/templates/learning_logs/*.html).