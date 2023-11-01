create table Bus_transport(Busno number(3) Primary key,Start_point varchar(15),End_point varchar(15),Via varchar(15),Orgin varchar(15));

insert into Bus_transport values(100,'Chennai','Kolkata','Bhuwaneswar','Chennai'));
insert into Bus_transport values(101,'Chennai','Kolkata','Visakpatnam','Chennai'));
insert into Bus_transport values(110,'Chennai','Hyderabad','Renekonda','Chennai'));
insert into Bus_transport values(121,'Chennai','Goa','Bangalore','Chennai'));
insert into Bus_transport values(123,'Chennai','Madurai','Vilupuram','Chennai'));
insert into Bus_transport values(134,'Hyderabad','Kanniyakumari','Chennai','Hyderabad'));
insert into Bus_transport values(135,'Hyderabad','Cochin','Chennai','Hyderabad'));
insert into Bus_transport values(127,'Cochin','Kolkata','Chennai','Kolkata'));
insert into Bus_transport values(139,'Cochin','Chennai','Madurai','Chennai'));
insert into Bus_transport values(140,'Cochin','Visakpatnam','Chennai','Cochin'));
insert into Bus_transport values(141,'Madurai','Hyderabad','Chennai','Madurai'));
insert into Bus_transport values(157,'Madurai','Chennai','Vilupuram','Chennai'));
insert into Bus_transport values(158,'Kanniyakumari','Kolkata','Chennai','Kolkata'));
insert into Bus_transport values(159,'Kanniyakumari','Chennai','Madurai','Chennai'));
insert into Bus_transport values(172,'Bangalore','Chennai','Oosur','Chennai'));
insert into Bus_transport values(182,'Tirupathi','Chennai','Kalahasthi','Chennai'));
insert into Bus_transport values(187,'Tirupathi','Pandicherry','Chennai','Tirupathi'));
insert into Bus_transport values(190,'Tirupathi','Madurai','Chennai','Madurai'));
insert into Bus_transport values(195,'Visakpatnam','Chennai','Renekonda','Chennai'));
insert into Bus_transport values(199,'Visakpatnam','Pandicherry','Chennai','Chennai'));

select * from Bus_transport;

create table Bus_timings(Busno number(3),Start_time varchar(10),End_time varchar(10),Travel_time varchar(10));

insert into Bus_timings values(100,'8:00am','10:30am','26hr30min');
insert into Bus_timings values(101,'8:00am','11:30am','27hr30min');
insert into Bus_timings values(110,'8:00pm','04:00am','8hr00min');
insert into Bus_timings values(121,'8:00pm','04:00pm','16hr00min');
insert into Bus_timings values(123,'10:00pm','07:00am','10hr00min');
insert into Bus_timings values(134,'10:00pm','04:00pm','14hr00min');
insert into Bus_timings values(135,'10:00pm','06:00am','10hr00min');
insert into Bus_timings values(127,'10:00pm','06:00am','32hr00min');
insert into Bus_timings values(139,'11:00pm','08:00am','9hr00min');
insert into Bus_timings values(140,'10:30pm','09:30am','11hr00min');
insert into Bus_timings values(141,'6:00pm','03:00am','9hr00min');
insert into Bus_timings values(157,'11:30pm','07:00am','8hr00min');
insert into Bus_timings values(158,'8:00pm','06:00am','31hr00min');
insert into Bus_timings values(159,'8:00pm','10:00am','14hr00min');
insert into Bus_timings values(172,'8:00pm','2:00am','6hr00min');
insert into Bus_timings values(182,'8:00pm','11:30am','3hr30min');
insert into Bus_timings values(187,'8:00pm','11:00am','3hr00min');
insert into Bus_timings values(190,'8:00pm','9:00am','13hr00min');
insert into Bus_timings values(195,'8:00pm','04:00am','8hr00min');
insert into Bus_timings values(199,'8:30pm','07:00am','9hr30min');

Select * from Bus_timings;

Create table Bus_fair(Busno number(3),Tot_seats number(3),Service varchar(10),Bus_fair number(4));

insert into Bus_Fair values(100,45,'AC SLEEPER',1500);
insert into Bus_Fair values(101,46,'AC SLEEPER',1750);
insert into Bus_Fair values(110,48,'AC',750);
insert into Bus_Fair values(121,49,'DELUXE',1200);
insert into Bus_Fair values(123,50,'AC',1100);
insert into Bus_Fair values(134,52,'AC',1200);
insert into Bus_Fair values(135,42,'DELUXE',1000);
insert into Bus_Fair values(127,45,'AC SLEEPER',900);
insert into Bus_Fair values(139,45,'AC',950);
insert into Bus_Fair values(140,40,'DELUXE',500);
insert into Bus_Fair values(141,48,'AC SLEEPER',600);
insert into Bus_Fair values(157,48,'AC',500);
insert into Bus_Fair values(158,49,'AC SLEEPER',1650);
insert into Bus_Fair values(159,50,'DELUXE',500);
insert into Bus_Fair values(172,50,'AC',600);
insert into Bus_Fair values(182,50,'DELUXE',750);
insert into Bus_Fair values(187,45,'AC',800);
insert into Bus_Fair values(190,46,'AC',900);
insert into Bus_Fair values(195,45,'AC SLEEPER',1000);
insert into Bus_Fair values(199,42,'AC',1250);

Selet * fom Bus_fair;


