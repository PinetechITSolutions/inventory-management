# inventory-management
Machine test for php developer candidates
Create a Laravel application(admin panel ) with 2  **user roles** 
- User 
- admin

For Inventory management mechanism 

# Framework
- Php
- Laravel
- MySql

## Requirement
Create an Inventory management application using  Laravel application and Mysql which including the following features.

*USER ROLES*
- Admin
- User

**Admin Role**
- Should able to create different inventories with the following fields - Inventory ID, Product ID, Capacity of product, and active/inactive.
- Should be able to add products with primary details like name, image, description
- Admin should be able to assign products to inventories (single product should be able to add multiple inventories)
- Only admin can do the above actions

**User Role**

- User can perform transfer a certain amount of product from 1 inventory to other
- Should consider the below things on transfer
- - the inventory from which we are going to transfer should have the amount of the product that we are going to transfer
- - On transferring the To Inventory doesn't exceed the capacity of that product
-  - Products can transfer between active inventories and those assigned to the product only 
- User should be the only one able to do this transaction

**Notes**
- All forms and transactions should have proper success/error messages and validation messages
- User can perform only the assigned actions.
- Should follow PSR-4 level of coding standard
