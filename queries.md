```sql
CREATE DATABASE employee_db;

use employee_db;

CREATE TABLE TBL_EMPLOYEE
(
 ID INT PRIMARY KEY AUTO_INCREMENT,
 UID VARCHAR(100) UNIQUE,
 FIRST_NAME VARCHAR(100) NOT NULL,
 LAST_NAME VARCHAR(100) NOT NULL
);

INSERT INTO TBL_EMPLOYEE(
UID, FIRST_NAME,LAST_NAME
)
VALUES('uid-123456','john','doe');

INSERT INTO TBL_EMPLOYEE(
UID, FIRST_NAME,LAST_NAME
)
VALUES('uid-123457','john','doe');

SELECT * FROM TBL_EMPLOYEE;
```