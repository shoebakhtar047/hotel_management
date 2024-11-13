create database hotel_db;
use hotel_db;
create table reservations(reservation_id int auto_increment primary key,
guest_name varchar(250) not null,room_number int not null,
contact_number varchar(12) not null,
reservation_date timestamp default current_timestamp);

this is query for databse and change or write   username and password in src file what you ave in your system. 
and also dont forget to connect mysql j coonector.
