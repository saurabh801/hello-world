# hello-world
Mysql command to create company database
create database company;
show databases;
use company;
create table employee(eid int primary key not null,ename varchar(20) not null,edept int,salary int);
desc employee;
insert employee values(31,"AAA",110,20000);
insert employee values(32,"BBB",111,25000);
insert employee values(33,"CCC",112,30000);
