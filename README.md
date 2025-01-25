# ecommerce-django-website

# django project steps 
    1. env creation
    2. pip install django 
    3. django-admin startproject <project name>
    4. cd <project name>
    5. python manage.py startapp <app name>
    6. update setting.py <appname.apps.functionname>
    7. python manage.py runserver


1. static folder creation
        STATICFILES_DIRS = [
            os.path.join(BASE_DIR, 'static')
        ]

# create super user
    python manage.py createsuperuser

    (env) mahendrayadav@Mahendras-MacBook-Air ecommerce % python manage.py createsuperuser
    Username (leave blank to use 'mahendrayadav'): project_1_ecommerce
    Email address: yadavitmahendra@gmail.com
    Password: 1234 
    Password (again): 1234
    This password is too short. It must contain at least 8 characters.
    This password is too common.
    This password is entirely numeric.
    Bypass password validation and create user anyway? [y/N]: y
    Superuser created successfully.


# git imp notes

    1. git init 
    2. git remote add origin <url>
    3. git pull
    4. git push
    5. git checkout -b <new branch name>
    6. git push
    7. git checkout main
    8. git merge <branch name>
    9. git branch -d <branch name>  (delete locally)
    10. git push origin --delete <branch name>  (delete on remote)
    11. git branch (to verify locally)
    12. git branch -r (to verify on remote)




# paypal 
I dont hai business account so I cant make th'e credential live 