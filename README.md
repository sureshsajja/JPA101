JPA101
======

JPA example with hibernate provider


### SQL to create table
use test;
 

create table Employee (  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;id INT NOT NULL,  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;fistName VARCHAR(20) default NULL,  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;lastName VARCHAR(20) default NULL,  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dept VARCHAR(20) default NULL,  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;PRIMARY KEY (id)  
);  