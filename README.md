# All You Need to Type as `Command` in `Terminal`

> Required commands to execute a `Django` project

## Check `Python` existence

```
python
print("Hello World!")
```

## File `Directory`

```
AcademicDjango
    |-django_env (for virtual environment)
    |   |-Scripts
    |       |-activate
    |       |-deactivate.bat
    |-preparation_project (for actual as project)
```

## Create `Virtual Environment`

> Execute all tasks by enabling `virtual environment`

```
python -m venv django_env
```

### `Activate` Virtual Environment

```
django_env\Scripts\activate
```

### `Deactivate` Virtual Environment

```
django_env\Scripts\deactivate.bat
```

## Install `Django`

```
pip install django
python -m django --version
```

## Create Django `First Project`

```
django-admin startproject preparation_project
```

## `Run` Existing Project

```
cd preparation_project
python manage.py runserver
```
