# SQLite

SQLite component can be used to interface with the Android device built-in SQLite Relational Database Management System \(RDMBS\). Using this component, you'll be able to create complex data structures and create parent-child tables \(e.g. employer, employees\) and query data from 1 or multiple tables by joining tables together.

In this tutorial, we'll show you simple steps to perform basic CRUD \(Create, Read, Update, Delete\) functions. For full functionality of SQLLite SQL commands, please refer to document [HERE](https://sqlite.org/lang.html).

SQLite component is a non-visible component that has blocks that you see in image blow:.

* RunQuery - can be used to run any valid[ SQL-92](https://en.wikipedia.org/wiki/SQL-92) statements; such as creating tables, executing queries
* DropTable - used to drop an existing table
* DisplayTables - displays all table names within the current database

![](/assets/book-sqlite1.png)

In our sample app, we will add ability to create table, insert data, read data, drop table. First, we will create a table that has 4 columns of type varchar:

![](/assets/book-sqlite3.png)

Next, we will insert some test-data into this table. Notice from image below:

![](/assets/book-sqlite4.png)





