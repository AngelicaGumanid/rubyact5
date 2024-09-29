# Activity5

Create at least 10 records using the create method
``` ruby=
Product.create(name: 'Laptop', price: 999.99, available: true, quantity: 25, discount: 10, description: 'High-performance laptop', released_at: '2022-05-15', expiry_date: nil)
Product.create(name: 'Smartphone', price: 699.99, available: true, quantity: 50, discount: 5, description: 'Latest model smartphone', released_at: '2023-01-10', expiry_date: nil)
Product.create(name: 'Tablet', price: 299.99, available: true, quantity: 30, discount: 0, description: 'Portable tablet', released_at: '2021-08-20', expiry_date: nil)
Product.create(name: 'Wireless Earbuds', price: 149.99, available: true, quantity: 100, discount: 15, description: 'Noise-canceling earbuds', released_at: '2023-02-15', expiry_date: nil)
Product.create(name: 'Smartwatch', price: 199.99, available: true, quantity: 75, discount: 20, description: 'Fitness tracking smartwatch', released_at: '2022-11-30', expiry_date: nil)
Product.create(name: 'Gaming Monitor', price: 399.99, available: true, quantity: 40, discount: 10, description: 'Ultra HD gaming monitor', released_at: '2022-04-25', expiry_date: nil)
Product.create(name: 'Bluetooth Speaker', price: 89.99, available: true, quantity: 150, discount: 5, description: 'Portable Bluetooth speaker', released_at: '2023-03-10', expiry_date: nil)
Product.create(name: 'External Hard Drive', price: 129.99, available: true, quantity: 60, discount: 10, description: '1TB external hard drive', released_at: '2022-09-15', expiry_date: nil)
Product.create(name: 'VR Headset', price: 299.99, available: true, quantity: 20, discount: 0, description: 'Virtual reality headset', released_at: '2023-05-01', expiry_date: nil)
Product.create(name: 'Camera', price: 499.99, available: true, quantity: 10, discount: 15, description: 'DSLR camera with lens', released_at: '2021-12-12', expiry_date: nil)
```
Create at least 10 records using the save method
Fetch all products where name is "Laptop".
Find products where price is greater than 100.
Retrieve products where available is true.
Fetch products where quantity is less than 50.
Find products where discount is exactly 10%.
Retrieve products where name contains the word "Pro".
Fetch products where description includes the word "portable".
Find products where price is between 50 and 150.
Retrieve products where available is false and quantity is greater than 0.
Fetch products where released_at is after January 1, 2023.
Find products where expiry_date is nil.
Retrieve products where released_at is before January 1, 2022.
Fetch products where quantity is between 10 and 100.
Find products where discount is greater than or equal to 5%.
Retrieve products where price is less than or equal to 200 and available is true.
Fetch products where expiry_date is before today’s date.
Find products where name starts with the letter "A".
Retrieve products where price is not equal to 100.
Fetch products where quantity is nil.
Find products where discount is not nil.
Update the price of a product where name is "Laptop" to 120.
Set the available status to false for products where quantity is 0.
Increase the discount by 5% for products where price is greater than 100.
Update the description to "Out of stock" for products where available is false.
Change the expiry_date to December 31, 2024, for products with a discount greater than 10%.
Update the quantity to 50 for products where name starts with "Pro".
Set the price to 200 for all products where discount is nil.
Mark products as available if their released_at is before January 1, 2023.
Update the price to 80 where the quantity is between 10 and 20.
Remove any discount (set to nil) for products where expiry_date is before today.
Update the name to "Premium Laptop" for products where price is more than 500.
Set the quantity to nil for products where available is false.
Update released_at to the current date for products with a price less than 50.
Reduce the price by 20% for products where quantity is less than 5.
Set the discount to 0% for products with a price greater than or equal to 300.
Change the description to "Limited time offer" where the discount is 15%.
Set available to true for products where the price is between 100 and 200.
Increase the quantity by 10 for products where released_at is after January 1, 2023.
Set the expiry_date to nil for products where discount is less than 5%.
Update the price to 150 where the description contains "sale".
Delete a product where name is "Laptop".
Remove all products where available is false.
Delete products where price is greater than 500.
Remove all products where quantity is 0.
Delete products where discount is greater than 20%.
Remove products where expiry_date is before today’s date.
Delete all products where name starts with "Pro".
Remove products where price is less than 50.
Delete products where released_at is before January 1, 2022.
Remove products where description contains "discontinued".
Delete products where quantity is between 1 and 10.
Remove all products where available is true and price is greater than 300.
Delete products where discount is nil.
Remove products where price is exactly 100.
Delete products where released_at is more than 5 years ago.
Remove products where description includes "obsolete".
Delete products where quantity is nil.
Remove products where expiry_date is within the next month.
Delete products where discount is less than 5%.
Remove all products where available is true but quantity is less than 5.
Print the name of all the products
Write a new migration to rename the description to content
Write a new migration to add a new column image
Write a new migration to remove the column expiry_date
This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
