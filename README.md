# Loducode utils

Basic components for the development of loducode s.a.s.

### install

`pip install loducode_utils==0.0.15`

## functionalities

- **Admin**
    - AuditAdmin
    - AuditStackedInline
    - AuditTabularInline
- **Models**
    - Audit
    - City  
- **Tasks**
    - send_mail_task(email, subject, message)
- **Urls Api**
    - /api/token/
    - /api/logout/
    - /api/forget/
- **Utils**
    - PaginatedListView
- **Views api**
    - ObtainCustomAuthToken
    - LogoutView
    - ForgetPasswordView

## Commands

- python setup.py sdist bdist_wheel
- twine upload --repository pypi dist/loducode_utils-0.0.15*

entrar a la carpeta loducode_utils y correr
- django-admin makemessages
- django-admin compilemessages

####Version 0.0.15
- Migration 0002

####Version 0.0.14
- Import export cities

####Version 0.0.13
- Change translate state for departament

####Version 0.0.11
- bug save user in save model audit

####Version 0.0.10
- add locale es-en
- bug _ translate apps.py

####Version 0.0.9
- add apps.py

####Version 0.0.8
- change translation model payment record
- new view data epayco

####Version 0.0.7
new model payment record

####Version 0.0.6
model city in admin fixxed register

####Version 0.0.5

- model city in admin
- migrations initials city
