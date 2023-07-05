# Django-Auth
### Packages
[django-crispy-forms](https://django-crispy-forms.readthedocs.io/en/latest/install.html)
<br/>
[crispy-bootstrap5](https://pypi.org/project/crispy-bootstrap5/)

#### Miscellaneous
[gitignore](https://djangowaves.com/tips-tricks/gitignore-for-a-django-project/)


1. My python version is 3.11.4
```
python --version
```
2. Create virtual environmet.
```
python -m venv env
```
3. Activate virtual environment.
```
env\Scripts\activate.bat
```
4. Create requirements.txt and install the packages with the command.
requirements.txt 
    django
    django-crispy-forms
    crispy-bootstrap5
```
pip3 install -r requirements.txt
```
5. Create django project
```
django-admin startproject website
```
6. To create our main app in website directory
```
cd website
python manage.py startapp main
```
7. Run the project in website directory
```
python manage.py runserver
```