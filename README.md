# full-blogging-site-in-laravel-with-CMS
This is a full blogging site created in laravel along with CMS (admin panel ) 

 NOTE: SWITCH TO MASTER BRANCH TO SEE THE FULL PROJECT



### Project Description
This is Complete Blog Build with Laravel, It has full control panel functionality where you can add, edit, update or delete post, pages and users and writers.

![1](https://user-images.githubusercontent.com/59476727/224474178-52201e24-99cd-4a21-8f97-e70eb66e6215.png)


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

Admin username: admin1@gmail.com
Admin Password: 12345678


![2](https://user-images.githubusercontent.com/59476727/224474195-ae6ee953-ed65-40df-9b1a-ad9ae6a44b7a.png)
![3](https://user-images.githubusercontent.com/59476727/224474201-f8129e47-0208-48ec-887f-1795824d08ff.png)
![4](https://user-images.githubusercontent.com/59476727/224474203-a289b5b4-b455-4f0a-b03c-53b1b9ed2ad4.png)
![5](https://user-images.githubusercontent.com/59476727/224474204-24ee3ad5-4c5c-43a4-a61e-9a5a573d77e9.png)
![6](https://user-images.githubusercontent.com/59476727/224474206-485b47ed-977d-454f-adea-87ce662dd772.png)
![7](https://user-images.githubusercontent.com/59476727/224474207-176bc03a-f043-4c77-b389-536f6cd68ea8.png)
