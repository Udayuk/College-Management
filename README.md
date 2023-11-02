
- `pip install -r requirements.txt`

- Create `.env` file inside the root directory and include the following variables
```config
DB_NAME=[YOUR_DB_NAME]
DB_USER=[DB_ADMIN_NAME]
DB_PASSWORD=[DB_PASSWORD]
DB_HOST=localhost
DB_PORT=
USER_EMAIL=[YOUR_EMAIL]
USER_PASSWORD=[EMAIL_PASSWORD]
STRIPE_SECRET_KEY=LEAVE_THIS_BLANK_FOR_NOW
STRIPE_PUBLISHABLE_KEY=LEAVE_THIS_BLANK_FOR_NOW
```

- `python manage.py makemigrations`

- `python manage.py migrate`

- `python manage.py runserver`
