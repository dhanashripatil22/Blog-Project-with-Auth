# Steps to Run the project:

1) Clone the project from GitHub

2) Create virtual environment:
   ~~~
   python -m venv myenv
   ~~~
   
3) Activate virtual environment:
   ~~~
   myenv\Scripts\activate
   ~~~
   
4) Install django:
   ~~~
   pip install django
   ~~~
   
5) Perform migration:
   ~~~
   python manage.py makemigrations
   python manage.py migrate
   ~~~
   
6) Run server:
   ~~~
   python manage.py runserver
   ~~~
