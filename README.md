# Django Mailersend backend

Email backend for Django which sends email via the Mailersend API

## Installation

Install the package

```
pip install django-mailersend-backend
```

## Configuration

In your `settings.py`:

1. Set the email backend
```py
EMAIL_BACKEND = 'mailersend_backend.MailersendBackend'
```

2. Define the configuration parameters as per [the mailersend python sdk](https://github.com/mailersend/mailersend-python#authentication)
```py
MAILERSEND_API_KEY = 'api_key'
```
