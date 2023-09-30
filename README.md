# Job Application Management Software

Job applicants can apply for certain job posts through a descriptive application form. In form, applicant can provide his/her personal and educational information in detail with payments. After submitting the form successfully, applicant get a personal user dashboard panel where he/she get all information related with the process. Administrator of the entire software system also get a dashboard where he can create job form, manage user and application form informations, verify payments manually and so on.

### **Prerequisites**

-   PHP 7.4+
-   Composer
-   MySQL
-   Node JS

### **Installation**

1. Extract the project
2. `cd extacted_project_dir_name`
3. Open up the terminal / bash and run `composer install`
4. Run `cp .env.example .env` or simply rename the `.env.example` file into `.env` 
5. Create a database in `mysql` and change database connection credentials (host name, database name, user-name, password) in `.env` file according to your local mysql settings
6. Run `php artisan migrate --seed` to migrate all migrations and seed default admin and users data. If anything goes wrong, then re-check the `.env` file and confirm all of `mysql` settings are correct.
7. Run `npm install` to install JavaScript related dependencies
8. Run `npm run dev` to compile js, vue, scss files
9. Run `php artisan serve` to serve the project locally
10. Open up a browser and go to localhost:8000 to access the application front-end

### Screen-shots

📷 Here are some screen-shots from the application:

![](images/Screenshot%20from%202021-02-18%2012-22-37.png)

![](images/Screenshot%20from%202021-02-18%2012-22-41.png)

![](images/Screenshot%20from%202021-02-18%2012-23-05.png)

![](images/Screenshot%20from%202021-02-18%2012-23-10.png)

![](images/Screenshot%20from%202021-02-18%2012-23-14.png)

![](images/Screenshot%20from%202021-02-18%2012-23-18.png)


