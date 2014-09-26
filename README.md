[![Stories in Ready](https://badge.waffle.io/quintet-cms/quintet.png?label=ready&title=Ready)](https://waffle.io/quintet-cms/quintet)
# Quintet

## Getting Started

1. `pip install django`
2. `pip install quintet --pre`
3. `django-admin startproject myblog && cd myblog`
4. Add the following to your `settings.py`

        INSTALLED_APPS = (
            ...
            'django.contrib.humanize',
            'django_forms_bootstrap',
            'django_bootstrap_markdown',
            'django_bootstrap_typeahead',
            'django_password_strength',
            'quintet',
            ...
        )

5. `./manage.py migrate`
6. `./manage.py createsuperuser`
7. `./manage.py runserver`
8. <http://127.0.0.1:8000/quintet/>
