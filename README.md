## Installation Steps:

1. `$ git clone git@github.com:tahiryasin/Sr-Full-stack-Developer-Task.git life-ecommerce`
2. `$ cd life-ecommerce`
3. `$ composer install`
4. `$ cp .env.example .env`
5. `$ php artisan key:generate`
6. `$ vi .env` # Configure database credentials
7. `$ php artisan migrate:refresh --seed`
8. `$ php artisan serve`

## Admin Credentials:
Admin URL: http://127.0.0.1:8000/admin/login  
user: admin@admin.com  
pass: admin123  
  
## API Credentials:

You may import the api collection in your postman from storage/postman  
DB Seeder creates a user with below credentials that are used in api auth  
  
user: `customer@example.com`  
pass: `password`