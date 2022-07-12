# SQL-dev8

-- 1

create table employee(
id integer,
name varchar(50),
birthday date,
email varchar(100)	
);


-- 3
update  employee 
set name = 'XXX YYY'
where id < 6
returning * ;

-- 4

delete from employee 
where id < 6
returning * ;

