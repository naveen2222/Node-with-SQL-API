# Node.js Rest APIs with Express & MySQL example

## Project setup
```
npm install
```

### Run
```
node server.js
```
### setup MYSQl install 
```

create table name with "testdb"
create with this 
CREATE TABLE IF NOT EXISTS `tutorials` (
  id integer NOT NULL PRIMARY KEY AUTO_INCREMENT,
  title varchar(255) NOT NULL,
  description varchar(255),
  published BOOLEAN DEFAULT false
) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4;

```
### For Rest API URL's

```

POST Call http://localhost:8080/api/tutorials/create " For Create"
GET Call http://localhost:8080/api/tutorials " For All tutorials"
GET Call http://localhost:8080/api/tutorials/published " For Only Published

```


