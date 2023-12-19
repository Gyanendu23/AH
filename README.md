create table blood_bank(     
state varchar(10),     city 
varchar(10),  
blood_bank_id  varchar(10) primary key  
);  

create table donor (     
varchar(20),     
donor_name 
donor_id varchar(10) 
primary key,     
blood_group  
gender varchar(10),     
varchar(10),     
date_of_birth date,  
donation_date_time timestamp,  
city 
varchar(10),     
phone_number varchar(10),     
blood_bank_id  
varchar(10),     
foreign 
key(blood_bank_id) 
references 
blood_bank(blood_bank_id)  
);   
