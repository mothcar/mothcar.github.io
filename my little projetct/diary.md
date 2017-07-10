## 'Tikehau'
## Step 1 :
```dos
$ sails new Tikehau
```

## Step 2 : contiue to new project
copy files and package.json properties from pre project except node module

## Step 3 : install
```dos
$ npm install
```
<br />  
# Orient DB 
## Database
```sql
> create database Tikehau
```

## Configuring connection
/config/connectoins.js
```javascript
password: 'somepassword',
database: 'juigi',
schema : true,
```

## DB Schema
DB Schema는 서버쪽에서만 만들어 놓으면 DB에서 별도로 property를 안 만들어도 된다.
단, Orientdb에서 제공하는 graph 기능의 class를 이용한 schema는 DB에서 만들어야 한다.





