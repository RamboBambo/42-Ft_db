# SQLit
This project is an introduction to learning about Database Management Systems. Students were required to create their
own version of a DBMS. Students are not allowed to use any libraries or standard

Insert:

insert into (file_name) values(fname,lname,age,course_id)

i.e. insert into roster.db values(Bob,Marley,21,42)

Delete:

delete from (file_name) (key)

i.e. delete from roster.db 1

Select:

select * from (filename)
select (col_name) (col_name) from (filename)
select * from (filename) WHERE (col_name)=(value)

i.e. select * from roster.db WHERE key=1

Updating:

update (filename) set (col_name)=[changed value] WHERE (col_name)=[current value]

i.e. update roster.db set fname=Bob WHERE fname=Elvis

# Author
Kenneth Cheung

# Acknowledgment
This project was completed at School 42 in Fremont, California
https://www.42.us.org/
