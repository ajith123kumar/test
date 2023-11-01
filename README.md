/*Create Table for the Bus Route Details*/

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

/*Show Table for the Bus Route Details*/

select * from Bus_transport;

/*Create Table for the Bus Timing Details*/

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

/*Show Table for the Bus Timing Details*/

Select * from Bus_timings;

/*Create Table for the Bus Fair Details*/

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

/* Show the Table for the Bus fair*/

Selet * fom Bus_fair;

/*Create Table for Bus Status */

Create table Bus_status(Busno number(3),Available_Day varchar(25),Availability varchar(15),Bus_count Varchar(10),Ticket_status varchar(15));

insert into Bus_Status values(100,'Weekly All Days','7/day',120,'Available');
insert into Bus_Status values(101,'Mon to Fri','10/day',120,'Available');
insert into Bus_Status values(110,'Mon to Fri','12/day',100,'Available');
insert into Bus_Status values(121,'Mon to Fri','1,Hour',200,'Available');
insert into Bus_Status values(123,'Weekly All Days','1,Hour',300,'Available');
insert into Bus_Status values(134,'Weekly All Days','7/day',250,'Available');
insert into Bus_Status values(135,'Weekly All Days','12/day',100,'Available');
insert into Bus_Status values(127,'Weekly All Days','12/day',152,'Available');
insert into Bus_Status values(139,'Weekly All Days','7/day',120,'Available');
insert into Bus_Status values(140,'Weekly All Days','1,Hour',100,'Available');
insert into Bus_Status values(141,'Weekly All Days','1,Hour',300,'Available');
insert into Bus_Status values(157,'Mon to Fri','1,Hour',100,'Available');
insert into Bus_Status values(158,'Mon to Fri','7/day',200,'Available');
insert into Bus_Status values(159,'Mon to Fri','1,Hour',160,'Available');
insert into Bus_Status values(172,'Mon to Fri','7/day',200,'Available');
insert into Bus_Status values(182,'Sun to Fri','7/day',320,'Available');
insert into Bus_Status values(187,'Weekly All Days','1,Hour',250,'Available');
insert into Bus_Status values(190,'Weekly All Days','7/day',200,'Available');
insert into Bus_Status values(195,'Weekly All Days','7/day',200,'Available');
insert into Bus_Status values(199,'Weekly All Days','12/day',200,'Available');

/*Show Table for the Bus Status*/

select * from Bus_status;

/Set Page Size for the Tables*/

set pagesize 300
set linesize 500

/*Please show Disple the Bus Route details if Bus is going to cochin and coming from cochin*/

select * from Bus_transport where End_point='Cochin' or Start_point='Cochin';

/*Please show the Bus Route details if Bus Reach Cochin at any point*/

select * from Bus_transport where End_point='Cochin' or Start_point='Cochin' or via='Cochin';

/*Please show the Bus Route details if Bus Reach Kolkata at any point*/

select * from Bus_transport where End_point='Kolkata' or Start_point='Kolkata' or via='Kolkata';

/*Please show me the Bus timings with Route*/

select a.Busno,a.Start_point,a.End_point,a.via,b.Start_time,b.End_time,b.Travel_time from Bus_transport a inner join Bus_timings b on a.Busno=b.busno;

/*Please show me the Bus timings for the Bus Going to Madurai and timings*/

select a.Busno,a.Start_point as Startfrom,a.End_point as Goingto,a.via,b.Start_time,b.End_time,b.Travel_time from Bus_transport a inner join Bus_timings b on a.Busno=b.busno where a.Start_point='Madurai' or a.End_point='Madurai' or a.via='Madurai';





