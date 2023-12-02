<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

মডিউল ১০ এর এসাইনমেন্ট </p>
Laravel Practice Assignment </p> And What I have done step by step.

                         Let's Start 
                     
Tasks:</P>
Task 1:
Create a new Laravel project named "MigrationAssignment" using the Laravel command-line interface.

Task 2:
Within the project, create a new migration file named "create_products_table" that will be responsible for creating a table called "products" in the database. The "products" table should have the following columns:
id: an auto-incrementing integer and primary key.
name: a string column to store the product name.
price: a decimal column to store the product price.
description: a text column to store the product description.
created_at: a timestamp column to store the creation date and time.
updated_at: a timestamp column to store the last update date and time.

Task 3:
After creating the migration file, run the migration to create the "products" table in the database.

Task 4:
Modify the existing migration file "create_products_table" to add a new column called "quantity" to the "products" table. The "quantity" column should be an integer column and allow null values.

Task 5:
Create a new migration file named "add_category_to_products_table" that will be responsible for adding a new column called "category" to the "products" table. The "category" column should be a string column with a maximum length of 50 characters.

Task 6:
After creating the new migration file, run the migration to add the "category" column to the "products" table.

Task 7:
Create a new migration file named "create_orders_table" that will be responsible for creating a table called "orders" in the database. The "orders" table should have the following columns:
id: an auto-incrementing integer and primary key.
product_id: an unsigned integer column to establish a foreign key relationship with the "id" column of the "products" table.
quantity: an integer column to store the quantity of products ordered.
created_at: a timestamp column to store the creation date and time.
updated_at: a timestamp column to store the last update date and time.

Task 8:
After creating the migration file for the "orders" table, run the migration to create the "orders" table in the database
