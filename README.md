# django-rest-framework-sample

# install
```
pip install -r requirements.txt
```

# Run migrate
```
python manage.py migrate
```

# Create super user
```
python manage.py createsuperuser --email admin@example.com --username admin
```

# Test api
Use bash in curl command.
```
curl -H 'Accept: application/json; indent=4' -u admin:password123 http://127.0.0.1:8000/users/
```

You also can see result from broswer.
```
http://127.0.0.1:8000/users/
```

# Reference
https://www.django-rest-framework.org/tutorial/quickstart/