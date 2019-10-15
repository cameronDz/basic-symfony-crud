# Basic Symfony Crud #
Project is a basic CRUD (Create, Retrieve, Update, Delete) project using PHP Symfony framework.

### Tutorial Source ###
- https://medium.com/@votanlean/create-a-basic-crud-website-with-symfony-4-2-and-some-command-line-helpers-3719677d0e

#### Issues ####
When running ```bin/console doctrine:database:create```

```
In AbstractMySQLDriver.php line 106:

  An exception occurred in driver: SQLSTATE[HY000] [2054] The server requested authentication method unknown to the client
```
- https://stackoverflow.com/questions/52364415/php-with-mysql-8-0-error-the-server-requested-authentication-method-unknown-to
