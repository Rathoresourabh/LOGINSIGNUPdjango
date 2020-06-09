# Simple Django Login and Registration
Django simple username email login signup page .

## Screenshots

| Log In | Create an account | Authorized page |
| -------|--------------|-----------------|
| <img src="./screenshots/login.png" width="200"> | <img src="./screenshots/create_an_account.png" width="200"> | <img src="./screenshots/authorized_page.png" width="200"> |

| Password reset | Set new password | Password change |
| ---------------|------------------|-----------------|
| <img src="./screenshots/password_reset.png" width="200"> | <img src="./screenshots/set_new_password.png" width="200"> | <img src="./screenshots/password_change.png" width="200"> |


## Installing


### Install dependencies & activate virtualenv

```
pip install pipenv
pipenv install
pipenv shell
```

### Configure the settings (connection to the database, connection to an SMTP server, and other options)

1. Edit `source/app/conf/development/settings.py` if you want to develop the project.

2. Edit `source/app/conf/production/settings.py` if you want to run the project in production.

### Apply migrations

```
python manage.py migrate
```

### Collect static files (only on a production server)

```
python manage.py collectstatic
```

### Running

#### A development server

Just run this command:

```
python manage.py runserver
```
