create table STUDENT(SSN integer primary key,Name varchar(10),Major varchar(10),Bdate date);

create table COURSE(Course_No integer primary key,Cname varchar(10),Dept varchar(10));

create table TEXT(Book_ISBN integer primary key,Book_Title varchar(10),Publisher varchar(10),Author varchar(10));

create table BOOK_ADOPTION(Course_No integer,Quarter integer,Book_ISBN integer,primary key(Course_No,Quarter),foreign key(Course_No) references COURSE(Course_No),foreign key(Book_ISBN) references TEXT1(Book_ISBN));


create table ENROLL(SSN integer,Course_No integer,Quarter integer,Grade varchar(5),primary key(SSN,Course_No,Quarter),foreign key(SSN) references STUDENT(SSN),foreign key(Course_No,Quarter) references BOOK_ADOPTION(Course_No,Quarter));


insert into STUDENT values(111,'AAA','CS','2001-10-19');
insert into STUDENT values(112,'AAB','MT','1999-08-18');
insert into STUDENT values(113,'AAC','IS','1998-02-13');
insert into STUDENT values(114,'AAD','EC','2000-10-11');
insert into STUDENT values(115,'AAE','MECH','2000-08-14');


insert into COURSE values(101,'DBMS','CS');
insert into COURSE values(102,'SE','ISE');
insert into COURSE values(103,'FM','MECH');
insert into COURSE values(104,'CSE','AERO');
insert into COURSE values(105,'CAA','CIVIL');


insert into TEXT1 values(201,'Atc','ZZZZ','AAAA');
insert into TEXT1 values(202,'Maths','YYYY','BBBB');
insert into TEXT1 values(203,'Python','XXXX','CCCC');
insert into TEXT1 values(204,'Unix','WWWW','EEEE');
insert into TEXT1 values(205,'DAA','VVVV','FFFF');


insert into BOOK_ADOPTION values(100,1,201);
insert into BOOK_ADOPTION values(101,2,202);
insert into BOOK_ADOPTION values(102,3,203);
insert into BOOK_ADOPTION values(103,4,204);
insert into BOOK_ADOPTION values(104,5,205);


insert into ENROLL values(111,101,1,'A');
insert into ENROLL values(112,102,2,'B');
insert into ENROLL values(112,103,3,'D');
insert into ENROLL values(113,104,4,'C');
insert into ENROLL values(114,105,5,'E');
