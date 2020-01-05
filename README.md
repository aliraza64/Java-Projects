# Java-Projects
Netbeans 8.2 IDE Office Management System

Clone this project and add 2 Jar files in library
#1 mysql-connector            (for database connection)
#2 rs2xml                     (for getting values on table)

# DATABASE
Create 7 tables in Data Base

	addemployee	 	
	application	 	
	project	 	
	project description
	reminder
	signup
	task detail
  
 
# IN ADDEMPLOYEE TABLE

	1	Employee IDPrimary	        varchar(255)	      latin1_swedish_ci
	2	NamePrimary	                varchar(255)	      latin1_swedish_ci
	3	EmailPrimary	                varchar(255)	      latin1_swedish_ci
	4	National IDPrimary	        varchar(255)	      latin1_swedish_ci
	5	ContactPrimary	                int(255)			                 
	6	QualificationPrimary	        varchar(255)	      latin1_swedish_ci
	7	SalaryPrimary	                int(255)
	8	ExperiencePrimary	        varchar(255)	      latin1_swedish_ci
	9	AddressPrimary	                varchar(255)	      latin1_swedish_ci

# IN APPLICATION TABLE

	1	ID	                         varchar(255)     	latin1_swedish_ci
	2	Application	                 varchar(500)     	latin1_swedish_ci
  
# IN PROJECT TABLE

	1	Project Name	                 varchar(255)     	latin1_swedish_ci
	2	Employee ID	                 varchar(255)	        latin1_swedish_ci
	3	Task	                         varchar(255)	        latin1_swedish_ci
	4	Description	                 varchar(255)     	latin1_swedish_ci
	5	Start Date	                 varchar(255)     	latin1_swedish_ci
	6	End Date	                 varchar(250)	        latin1_swedish_ci	
  
# IN PROJECT DESCRIPTION TABLE

	1	Description	                 varchar(1000)    	latin1_swedish_ci
  
# IN REMINDER TABLE

	1	Reminder Type	                 varchar(255)	        latin1_swedish_ci
	2	Description	                 varchar(255)     	latin1_swedish_ci
  
# IN SIGNUP TABLE

 	1	Name	                        varchar(255)	      latin1_swedish_ci
	2	EmailIndex                      varchar(255)	      latin1_swedish_ci
	3	Password	                varchar(255)          latin1_swedish_ci
	4	Confirm Password	        varchar(255)	      latin1_swedish_ci
	5	Designation                     varchar(255)	      latin1_swedish_ci
  
# IN TASK DETAIL TABLE

	1	Task Name                 	 varchar(255)           latin1_swedish_ci
	2	Description	                 varchar(255)	        latin1_swedish_ci
	3	Start Date	                 varchar(255)     	latin1_swedish_ci
	4	End Date	                 varchar(255)     	latin1_swedish_ci
	5	Employee ID	                 varchar(255)     	latin1_swedish_ci
  
  Create these tabe and and set the SQL Queries according to the Project.
