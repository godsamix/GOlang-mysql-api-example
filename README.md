# GOlang-mysql-api-example

This is an example of building REST api with MySQL integration using GOlang.

After creating your project if you do not have gorilla mux and go mysql driver
Please install those packages:
go get -u github.com/gorilla/mux
go get -u github.com/go-sql-driver/mysql

We will be using MySQL to connect to the database.
I have already created a table in my database called "usertest"
with columns "id", "name", "country" and "number"
make sure "id" is auto-increment as i am not going to insert and update the id in the code.

Happy Coding :)