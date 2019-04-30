# MYSQL Request

1.1.	SELECT * FROM `employee` WHERE `city` LIKE 'А%' ORDER BY `name` ASC
1.2.	SELECT * FROM `employee` WHERE Date_Format(`birthday`,'%d.%m')=Date_Format(NOW(),'%d.%m')
1.3.	select * from `employee` WHERE `salary`=(SELECT MAX(`salary`) FROM `employee`) OR `salary`=(SELECT MIN(`salary`) FROM `employee`)  
