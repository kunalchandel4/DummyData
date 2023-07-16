# Dummy_Data

### Stock Category

* INSERT INTO stock_category (id, category_name) VALUES (400,'Fruit');
* INSERT INTO stock_category (id, category_name) VALUES (401,'Vegetables');

### Store Location

* INSERT INTO store_location (id,address,city,name,state) VALUES (300,'1037 Sadar Bazar', 'Delhi','T.R.Dmart','Delhi');
* INSERT INTO store_location (id,address,city,name,state) VALUES (301,'1769 Kamla Market', 'Delhi','VijaySolutionDmart','Delhi');
* INSERT INTO store_location (id,address,city,name,state) VALUES (302,'1588 C.P', 'Delhi','V.M.K.Dmart','Delhi');
* INSERT INTO store_location (id,address,city,name,state) VALUES (303,'1405 Karol Bagh', 'Delhi','KantyDmart','Delhi');

### Stock Item

* JSON Data
{
"name":"Tomato",
"quantity":200,
"salePrice":120,
"marketPrice":70,
"category": {
"id": 401
}

### Customer

* JSON Data
{
"name": "Ramesh",
"email": "ramesh@gmail.com",
"password": "141516",
"address": "Pune",
"role": "user"
}

{
"name": "Ram",
"email": "ram@gmail.com",
"password": "141516",
"address": "Delhi",
"role": "admin"
}
