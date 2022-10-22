# Django Mailersend backend

Email backend for Django which sends email via the Mailersend API

## Installation

Install the package

```
pip install django-mailersend-backend
```

## Configuration

In your `settings.py`:

1. Add the module into the `INSTALLED_APPS`
```py
INSTALLED_APPS = [
   ...,
   'mailersend_backend',
   ...
]   
```

2. Set the email backend
```py
EMAIL_BACKEND = 'mailersend_backend.MailersendBackend'
```

3. Define the configuration parameters as per [the mailersend python sdk](https://github.com/mailersend/mailersend-python#authentication)
```py
MAILERSEND_API_KEY = 'api_key'
```
