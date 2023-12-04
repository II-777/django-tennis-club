---
title: django-manage-commands
date: 2023-12-04 18:03
author: II-777
tags: #django
---

# Django `manage.py` Commands
```bash
# Initiate Django Shell
py manage.py shell
```
### `auth` Commands:
1. `changepassword`: Allows changing the password of a user.
2. `createsuperuser`: Interactively creates a superuser account with administrative privileges.

### `contenttypes` Command:
1. `remove_stale_contenttypes`: Removes stale content types from the database. Useful when models or apps are removed.

### `django` Commands:
1. `check`: Checks for common issues and errors in the project's code and configuration.
2. `compilemessages`: Compiles message files for use with internationalization.
3. `createcachetable`: Creates the cache table in the database for caching.
4. `dbshell`: Runs the command-line database shell.
5. `diffsettings`: Displays differences between the current settings and the default Django settings.
6. `dumpdata`: Outputs the contents of the database as a fixture (data snapshot).
7. `flush`: Resets the database by removing all data from it.
8. `inspectdb`: Introspects the database and creates Django model classes.
9. `loaddata`: Loads data from a fixture into the database.
10. `makemessages`: Creates message files for translation from the source code.
11. `makemigrations`: Creates new database migration files based on model changes.
12. `migrate`: Applies database migrations to synchronize the database schema.
13. `optimizemigration`: Optimizes migration by combining similar operations.
14. `sendtestemail`: Sends a test email to the email addresses specified in the settings.
15. `shell`: Launches the interactive Python shell with Django environment loaded.
16. `showmigrations`: Lists all migrations and their status.
17. `sqlflush`: Outputs the SQL statements to flush the database.
18. `sqlmigrate`: Displays the SQL for a specific migration.
19. `sqlsequencereset`: Prints the SQL statements for resetting database sequences.
20. `squashmigrations`: Combines multiple migrations into one.
21. `startapp`: Creates a new Django app within the project.
22. `startproject`: Creates a new Django project.
23. `test`: Runs tests for the entire project or specified apps.
24. `testserver`: Runs a development server preloaded with test data.

### `sessions` Command:
1. `clearsessions`: Removes expired sessions from the session database.

### `staticfiles` Commands:
1. `collectstatic`: Collects static files from each app and places them in a single location.
2. `findstatic`: Finds the absolute path to the specified static file.
3. `runserver`: Starts the development server for serving static and media files during development.
