# Meta-Back-End-Developer-Capstone-Project-Final

## Introduction 
▷ This is the final assignment of the Meta Backend Developer Professional Certificate on Coursera

Throughout this project, I've explored various aspects of back-end development, including database management, API design, authentication, and optimization. By tackling real-world challenges and implementing industry best practices, I've honed my abilities to architect and deploy back-end solutions that meet the needs of modern applications.

Thanks for taking the time to review this project! My hope is that it sparks inspiration and provides helpful guidance for other aspiring back-end developers as they navigate their own paths in the exciting world of software development.

## Content Guide 🗺️

This web application utilizes Django + DRF + djoser + MySql
There is a simple static page with url: http://localhost:8000/restaurant/

## APIs
```restaurant/api/menu```
Allow all authenticated users to view the menu items
Only admin user could post new item

Fields needed to post:
>**title**: str

>**price**: decimal

>**featured**: (opt.) boolean, default = 0

```restaurant/api/menu/<int:pk>```
Allow all authenticated users to view single menu item
Only admin user could update or delete single item

```restaurant/api/book```
Allow authenticated users to post new book, please use the same username of the user as the name of book

User could obtain all the books that has the same book name with the current username

Fields needed to post:
>**name**: str, the same as username

>**guest_number**: (opt.) int, default = 1

>**date**: date, in the form of "YYYY-MM-DD"

>**comment**: (opt.) text

```restaurant/api/book/<int:pk>```
Only admin user could view or delete single book

### Current users
Superuser/admin:
>**Username**: admin
>**Password**: 123

Customer:
>**Username**: customer1
>**Password**: lemon@123!

>**Username**: customer2
>**Password**: lemon@123!
