## https://github.com/gauravdhiman/sailsjs-angularjs-orientdb-poc


1. install express project

2. create DB
~~~~
  $ ~/dev/orientdb-community-2.2.20/bin » ./server.sh
  $ ~/dev/orientdb-community-2.2.20/bin » ./console.sh
  // CREATE DATABASE <database-url> [<user> <password> <storage-type> [<db-type>]]
  $ create database /databases/blog admin admin local graph
  orientdb> CREATE DATABASE REMOTE:localhost/blog root xxxxxxx PLOCAL GRAPH        // not work
  orientdb> CREATE DATABASE PLOCAL:/Users/paul/dev/orientdb/databases/blog
~~~~

결과 : 
~~~~
orientdb> CREATE DATABASE PLOCAL:/Users/paul/dev/orientdb/databases/blog

Creating database [PLOCAL:/Users/paul/dev/orientdb/databses/blog] using the storage type [plocal]...
Database created successfully.

Current database is: PLOCAL:/Users/paul/dev/orientdb/databases/blog
~~~~
