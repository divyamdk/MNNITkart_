
## Running the project

```
npm install
nodemon app.js

npm install express
npm install mysql
npm install bycrypt

For connecting the MySql database , command  = "mysql -u root -p command"
```

sell_table  SCHEMA =
+-------------+-----------+
| COLUMN_NAME | DATA_TYPE |
+-------------+-----------+
| name        | varchar   |
| product     | varchar   |
| mob_no      | bigint    |
| price       | int       |
| old         | int       |
| image       | longblob  |
| year        | int       |
| descript    | varchar   |
| currentdate | varchar   |
| current_id  | varchar   |
| user_id     | varchar   |
+-------------+-----------+
             

donate_table SCHEMA =
+-------------+-----------+
| COLUMN_NAME | DATA_TYPE |
+-------------+-----------+
| name        | varchar   |
| product     | varchar   |
| mob_no      | int       |
| old         | int       |
| image       | longblob  |
| descript    | varchar   |
| user_id     | varchar   |
| current_id  | varchar   |





cart_products table
+-------------+-----------+
| COLUMN_NAME | DATA_TYPE |
+-------------+-----------+
| user_id     | varchar   |
| current_id  | varchar   |
| is_active   | int       |
+-------------+-----------+

users

+-------------------------------+-----------+
| COLUMN_NAME                   | DATA_TYPE |
+-------------------------------+-----------+
| USER                          | char      |
| CURRENT_CONNECTIONS           | bigint    |
| TOTAL_CONNECTIONS             | bigint    |
| MAX_SESSION_CONTROLLED_MEMORY | bigint    |
| MAX_SESSION_TOTAL_MEMORY      | bigint    |
| email                         | varchar   |
| psw                           | varchar   |
+-------------------------------+-----------+

customers

+-------------+-----------+
| COLUMN_NAME | DATA_TYPE |
+-------------+-----------+
| user_id     | varchar   |
| fname       | varchar   |
| lname       | varchar   |
| gender      | varchar   |
| phone       | varchar   |
| country     | varchar   |
| state       | varchar   |
| city        | varchar   |
| address     | varchar   |
| pincode     | varchar   |
+-------------+-----------+

user_sell_products

+-------------+-----------+
| COLUMN_NAME | DATA_TYPE |
+-------------+-----------+
| user_id     | varchar   |
| sell        | varchar   |
+-------------+-----------+