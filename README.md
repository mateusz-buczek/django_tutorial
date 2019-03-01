# django_tutorial 

## Sources 
The following project is/was created based on tutorial at djangoproject.com 

## Settings 
TIME_ZONE is set to 'Europe/Warsaw'. It's recommended to change it accordong to your location, go to mysite/settings.py. Using unmatching timezone may cause problems with filtering results, as well as with adding and viewing records. 

LANGUAGE_CODE is kept 'en-uss' by default, assuming it's the most versatie choice 

## Running 
Copy repository to your python IDLE (pyCharm suggested). Requires installed Django. 
In terminal go to mysite directory and type: 
```
$ python manage.py runserver 
```
Create your own superuser or use existing one (admin, pass: admin123), and feel free to try out /admin panel. 
