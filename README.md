- Inside src/config folder create a folder named as config.json and write the following code:
```
{
  "development": {
    "username": "root",
    "password": null,
    "database": "database_development",
    "host": "127.0.0.1",
    "dialect": "mysql"
  },
  "test": {
    "username": "root",
    "password": null,
    "database": "database_test",
    "host": "127.0.0.1",
    "dialect": "mysql"
  },
  "production": {
    "username": "root",
    "password": null,
    "database": "database_production",
    "host": "127.0.0.1",
    "dialect": "mysql"
  }
}
```
- if you;are setting in development environment, then write the same name of your username of your db, password of your db, and in dialect metion whatever DB you're using eg: mysql, mariadb etc.

- if you're setting up test or prod env, make sure you also replace the host with the hosted db url.




-