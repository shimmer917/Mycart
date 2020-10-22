# Python-Group-Project
ML Based Ecommerce site 

Set Virtual Environment directory **venv**
```
deactivate //if your terminal start it with : (base)

python -m venv venv
echo venv/ >> .gitignore
cd venv
cd Scripts
activate
```
which should show result like this
```
(venv) ...\Mycart\venv\Scripts>
```
Now come back to our top most level directory in \Mycart
```
cd..
cd..
pip install -r requirements.txt
```
---
To Run Server:
```
python manage.py runserver
```
To create a new app, run
```
python manage.py startapp <projectapp>
```
For other management, run
```
python manage.py
```


Packages | Version
--------- | -------
Python  | 3.7.6
pip | 20.0.2
Django | 3.1.2
djangorestframework | 3.12.1
Wagtail | 2.10.2
Pillow | 7.2.0 


Contributed By:
>Astha Gupta
>
>Yamini Vijayvargiya
>
>Karuna Yadav
>
>Anurag Dhadse
