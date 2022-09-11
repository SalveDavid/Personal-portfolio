# Portfolio Project

Personal Portfolio that shows the projects that I've been working on.

<br />

## Content
* [Usage Information](#usage-information)
* [Blog](#blog)
* [Projects](#projects)

<br/>

## Usage Information

<details>
<summary>Steps</summary>


* Clone the repository.
* Create project virtual environment inside **personal_portfolio** directory:

```
python3 -m venv env_perport
```

* Activate your virtual enviroment and install required python modules:
```
source env_perport/bin/activate
python -m pip install -r requirements.txt
```

* Go to Django project **personal_portfolio** directory and execute:
```
python manage.py makemigrations
python manage.py migrate
```

* Startup the Django server:
```
python manage.py runserver
```
</details>

<br/>

## Blog
The blog, even though it is a separate project, is part of the Portfolio Project and it has different articles about technology and Python.

<br/>

## Projects
In this part you can see several personal projects, some of them with link to see how it works live in production.
