## Prerequisites
- Java 11
- Maven 3.9
- MySQL 5.6 or later

## Technologies 
- Tomcat
- RabbitMQ
- Memcached
- Maven
- MySQL
## Database
Here,we used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu 22.04:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Then look for the file :
- /src/main/resources/accountsdb
- accountsdb.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < accountsdb.sql


