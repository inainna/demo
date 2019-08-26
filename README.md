If you want to run the app, you must have next tools installed:
1. gradle
2. mysql
3. postman

and follow the next steps:
1. import the project in your IDE, specifying import from gradle
2. run mysql commnad line
3. create new database with the name "test"
4. credentials for database must be:
username : root
password : root
5. run the project.

In order to check the endpoint results, open postman and type next http requests:
for transactions
1. (get) localhost:8080/transactions - get all transactions
2. (post) localhost:8080/transactions - create a new transaction
3. (get) localhost:8080/transactions/{id} - get a single transaction
4. (put) localhost:8080/transactions/{id} - update a transaction
5. (delete) localhost:8080/transactions/{id} - delete a transaction
for customers
1. (get) localhost:8080/customers - get all customers
2. (post) localhost:8080/customers - create a new customer
3. (get) localhost:8080/customers/{id} - get a single customer
4. (put) localhost:8080/customers/{id} - update a customer
5. (delete) localhost:8080/customers/{id} - delete a customer

