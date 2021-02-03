## Laravel Test


###Getting Started
To setup the following application please run the following command on your command line:

```

composer install
php artisan passport:install
php artisan passport:keys
php artisan migrate
php artisan serve

```

The routes for the following application:

```

POST http://127.0.0.1:8000/api/send

```


1. Send the following json using postman on http://127.0.0.1:8000/api/send the method is [POST] for the json format
```json

{
    "name":"",
    "email":"nevored01@gmail.com",
    "subject": "Test Mailer123",
    "message":"This is a sample test mail run",
    "attachment": ""
}

```

2. Open Horizon using `php artisan horizon` make sure the Redis is open.