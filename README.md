# LARASHOP

Larashop is a bookstore application. Created using the laravel 8 framework following the tutorial from Mas Azamuddin's book Be Fullstack Developer.

1. Clone this repository:

```
$ git clone https://github.com/ikhfhm/larashop.git
```

2. Go inside folder:

```
$ cd larashop
```

3. Copy file .env

-   For MacOs GNU/Linux:

```
$ cp .env.example
```

-   For Windows OS:

```
$ copy .env.example .env
```

4. Install composer:

```
$ composer install
```

5. Generate key:

```
$ php artisan key:generate
```

6. Configure database

```
DB_CONNECTION=mysql
DB_HOST=mysql
DB_PORT=3306
DB_DATABASE=<DATABASE NAME>
DB_USERNAME=<USERNAME>
DB_PASSWORD=<PASSWORD>
```

7. Migration:

```
$ php artisan migrate
```

8. Dump autoload

```
$ composer dump-autoload
```

9. Seeder migration

```
$ php artisan db:seed
```

11. Serve

```
$ php artisan serve
```

### Open Application

Open http://localhost:8000
|#|Role|email|Password|
|---|---|---|---|
|1|admin|administrator@larashop.test|larashop|

### Screenshot

Login page
![image](public/screenshot/login.png "Fb Ads Fit")
Home page
![image](public/screenshot/home.png "Fb Ads Fit")
Users page
![image](public/screenshot/users.png "Fb Ads Fit")
Categories page
![image](public/screenshot/categories.png "Fb Ads Fit")
Books page
![image](public/screenshot/books.png "Fb Ads Fit")
Orders page
![image](public/screenshot/orders.png "Fb Ads Fit")
