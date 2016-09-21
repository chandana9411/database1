# database1
TABLE FOR PRODUCT

CREATE TABLE product
(
ProductID int(20) primary key,
Name varchar2(255),
description varchar2(255),
price int(20),
category varchar2(255),
);

TABLE FOR USER

CREATE TABLE user
(
mailID varchar2(20) ,
username varchar2(255),
password varchar2(255),
contactNo int(12),
role varchar2(25),
);

TABLE FOR CART

CREATE TABLE cart
(
mailID varchar2(20) 
address varchar2(100),
cartitemId varchar2(255),
price int(12),
quantity varchar2(25),
);



