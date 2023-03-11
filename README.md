

### Project Description
This is Complete Blog Build with Laravel, It has full control panel functionality where you can add, edit, update or delete post, pages and users and writers.


### What I use it this project
- Laravel Framework 10,
- Tailwind for front and admin,
- Laravel Policies,
- Laravel Gates,
- Custom Validation Rule,
- Applied ( One to many and Many to many ) relationships betwen models,
- Faker & Database Seeder,
- jQuery
- SEO friendly slug URLS,

### Project Functionality
#### Admin Panel
- Edit General Blog informations,
- Create/ Update / Delete ( Categories, Posts, Tags and Custom Pages)
- Manage Roles

### Writer Panel
- Create, Update and Delete it own Posts
- Create, Update and Delete Tags.

### Roles
                    
Role Name  | Role_ID
------------- | -------------
Admin  | 1
Writer | 2 
User | 3
                

### Gate Function
There is a gate filter login when the user login to the admin panel if the user is Admin it will have full functions to manage the blog and if a Writer it will have few functions.

## Requirements
- PHP >= 8.1
- MySQL or other database server
- Composer
- NodeJS

### How to Install
1. Clone the project
2. Go to the project root directory and run `composer install` and `npm install`
3. Create `.env` file and copy content from `.env.example`
4. Run `php artisan key:generate` from terminal
5. Change database information in `.env`
6. Run migrations by executing `php artisan migrate` , Then Run  `php artisan db:seed` if you want use faker database records,
7. Start the project by running `php artisan serve`


### Database
I have added database file so that you can simply login to admin panel
-> localhost:8000/admin (For admin panel)
-> localhost:8000/register (To register user)

