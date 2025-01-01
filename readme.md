# Django Project Template

+ Reformats <code>settings.py</code> as a python module with environment.
+ Must install <code>django-environ</code>.
    - <code>pip install -r requirements.txt</code>
    - create <code>.env</code> with:
        - <code>DEBUG=True</code>
        - <code>SECRET_KEY=some_string</code>
        - <code>DATABASE_URL=sqlite:///db.sqlite3</code>
+ Sets template, static, and media urls.
+ Creates apps in project_apps directory.
    - <code>mkdir project_apps/'app_name'</code>
    - <code>python manage.py startapp |app_name| project_apps/|app_name|</code>
    - <code>INSTALLED_APPS += ['project_apps.|app_name|']</code>
+ Includes home screen application.