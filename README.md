# improved-BBMS
A course based project using Database Management system and Java implementation
            AIM
   
The aim of a Blood Bank Management System is to provide an efficient and organized platform for managing the collection, storage, testing, and distribution of blood and its components. This digital system streamlines the processes associated with blood donation, inventory management, donor and recipient information, and helps ensure the availability of safe and compatible blood products when needed.


PROBLEM STATEMENT

The problem statement of a Blood Bank Management System revolves around addressing the challenges faced by blood banks and healthcare institutions in managing their blood inventory and donation processes. Key issues include:

•	Scarcity of rare blood group
•	Unavailability of blood during emergency.
•	Less awareness among people about blood donation and blood transfusion.
•	Deaths due to lack of blood during operations.

•	Inventory Management: Manual tracking of blood donations, expiration dates, and blood types can lead to inefficiencies and errors in maintaining an adequate supply of blood.

•	Donor and Recipient Information: Keeping accurate records of donor information, medical history, and recipient needs is crucial for safe and successful blood transfusions.

•	Blood Type Matching: Ensuring that the right blood type is available for recipients and that cross-matching is accurate is vital to prevent adverse reactions.

•	Communication and Coordination: Coordinating with hospitals, donors, and recipients for timely blood transfusions can be challenging without an organized system.

•	Reporting and Analytics: Lack of proper reporting and analytics can hinder decision-making regarding blood supply and demand.


The Blood Bank Management System aims to address these challenges by providing a digital solution that optimizes blood donation processes, ensures accurate donor and recipient records, supports efficient inventory management, and facilitates effective communication and coordination.








                                                          CHAPTER-1

1.0 INTRODUCTION

A Blood Bank Management System is a digital platform that revolutionizes the way blood banks operate by providing a comprehensive solution for managing blood donation and distribution processes. It leverages technology to ensure the availability of safe blood products, streamline donor interactions, and enhance communication with healthcare institutions.

The population of the world is multiplying with each coming year and so are the diseases and health issues. With an increase in the population there is an increase in the need of blood. The growing population of the world results in a lot of potential blood donors. But in spite of this not more than 10% of the total world population participates in blood donation. With the growing population and the advancement in medical science the demand for blood has also increased. Due to the lack of communication between the blood donors and the blood recipients, most of the patients in need of blood do not get blood on time and hence lose their lives. There is a dire need of synchronization between the blood donors and hospitals and the blood banks. This improper management of blood leads to wastage of the available blood inventory. Improper communication and synchronization between the blood banks and hospitals leads to wastage of the blood available. These problems can be dealt with by automating the existing manual blood bank management system. A high-end, efficient, highly available and scalable system has to be developed to bridge the gap between the donors and the recipients and to reduce the efforts required to search for blood donors.


1.1 PURPOSE

The main purpose of the project is to develop a web application for blood banks to manage
information about their donors and blood stock. The main objectives of this website development can be defined as follows:

1.	To develop a system that provides functions to support donors to view and manage their information conveniently.

2.	To maintain records of blood donors, blood donation information and blood stocks in a centralized database system.

3.	To inform donors of their blood result after their donation.

4.	To support searching, matching and requesting for blood convenient for administrators.

5.	To provide a function to send an e-mail directly to the donor for their user account and the         hospital, the availability of the blood bag.                








          1.3 SCOPE

This system makes conveniently available good quality, safe blood and other blood components, which can be provided in a sound, ethical and acceptable manner, consistent with the long-term well -being of the community. It actively encourages voluntary blood donation, motivates and maintains a well-indexed record of blood donors and educates the community on the benefits of blood donation. This will also serve as the site for interaction of best practices in reducing unnecessary utilization of blood and help the state work more efficiently towards self-sufficiency in blood. The system will provide the user the option to look at the details of the existing Donor List, Blood Group and to add a new Donor. It also allows the user to modify the record. The administrator can alter all the system data. The system is able to generate a report to summarize all records including blood donation, blood requests and blood stock for the administrator.


          1.4 ACRONYMS

        BBMS: Blood Bank Management System (itself an acronym)
        ABO: Blood group system (A, B, AB, O)
        CRM: Customer Relationship Management
        EMR: Electronic Medical Record
                    API: Application Programming Interface
                    SMS: Short Message Service
                    GDPR: General Data Protection Regulation
                    HIPAA: Health Insurance Portability and Accountability Act

These acronyms represent the various components and concepts within the Blood Bank Management System, contributing to its functionality and efficiency.
   

              

                           


            

          

                    







          
                           CHAPTER-2

          2.1 OVERALL DESCRIPTION

A Blood Bank Management System is a digital platform designed to streamline and optimize the various processes associated with blood donation, storage, testing, and distribution within blood banks and healthcare institutions. Through internet access and mobile applications, this system offers a user-friendly interface that simplifies blood management tasks, enhances communication, and ensures the availability of safe and compatible blood products.

The BBMS allows us to keep track of quality of blood and also keeps track of available blood when requested by the acceptor. The existing systems are Manual systems which are time consuming and not so effective. BBMS automates the distribution of blood. This database consists of thousands of records of each blood bank.

By using this system searching the available blood becomes easy and saves lot of time than the manual system. It will hoard, operate, recover and analyze information concerned with the administrative and inventory management within a blood bank. This system is developed in a manner that it is manageable, time effective, cost effective, flexible and much man power is not required. This System revolutionizes the blood banking process by digitizing and optimizing its various components. This digital platform empowers stakeholders with tools to ensure blood safety, efficient operations, and improved patient care, marking a significant advancement in the healthcare sector.

2.2 SOFTWARE INTERFACES

The software interfaces of a Blood Bank Management System encompass crucial components that facilitate efficient blood management. These interfaces ensure seamless interactions and effective management for various stakeholders involved.

Database Interface: The BBMS software needs to interact with a database management system (DBMS) to store and retrieve data related to donors, recipients, blood units, inventory, and transactions.

APIs (Application Programming Interfaces):

•	External Hospital System APIs: If the BBMS needs to integrate with hospital systems for patient data or blood requests, APIs would facilitate this data exchange.

•	SMS/Email Gateway APIs: To send notifications and alerts to donors, recipients, and staff members via SMS or email.

•	Authentication and Authorization Interfaces: Interfaces for integrating authentication services, such as LDAP or OAuth, for secure user access and role-based permissions.

•	Reporting Interfaces: Integration with reporting tools or libraries to generate various types of reports for donors, recipients, inventory, and other data.

•	Notification Interfaces: Integration with email, SMS, or push notification services for sending reminders, alerts, and updates to users.


2.3 HARDWARE INTERFACES

The hardware interfaces of a Blood Bank Management System cater to the devices used by various stakeholders involved.

•	Donor Devices: Donors primarily use personal devices such as smartphones or computers to access the donor interface for registration and appointment scheduling.

•	Blood Bank Devices: Blood bank staff use computers or tablets with internet connectivity to access the inventory management, records, and communication interfaces.

•	Medical Devices: Blood testing and processing equipment may be integrated with the system for real-time tracking of blood units during these stages.

•	Delivery Partner Devices: If external services are involved, delivery partners utilize smartphones or specialized devices with GPS capabilities to access delivery information.

•	Healthcare Provider Devices: Hospital staff use computers or tablets to interact with the communication interface, accessing real-time blood availability and expected delivery times.

Overall, the hardware interfaces of the BBMS are designed to accommodate the devices used by donors, blood banks, healthcare providers, and delivery partners, ensuring smooth communication, accurate records, and safe blood transfusion processes.

























                                                         CHAPTER-3

3.0 FUNCTIONAL REQUIREMENTS

Donor facility: 
1.	A donor can register himself as a donor 
2.	Adding his ability of donating the blood 
3.	Can see the request for blood
4.	Change personal, contact details by the donors himself. 

User facility: 
1.	Can see all the donors and blood bank 
2.	Can filter donor and blood bank according to the blood group and city 
3.	Sending the request for the blood to donor and blood bank 
4.	Send blood donation details to the relevant donors.

 Admin facilities: 
1.	Can see donors 
2.	Update, delete and verify donor


  3.1 NON-FUNCTIONAL REQUIREMENTS
   	 
•	Performance: The system should be able to handle a high volume of concurrent users during peak times (e.g., blood donation events) without significant performance degradation.

•	Reliability: The system should have a high level of availability, aiming for minimal downtime for essential operations.

•	Usability: The user interface should be intuitive and user-friendly, requiring minimal training for users to navigate and perform tasks.

•	Compatibility: The system should be compatible with various web browsers, devices (desktops, tablets, smartphones), and operating systems to ensure broad user accessibility.

•	Backup and Recovery: Regular data backups should be performed to prevent data loss in case of system failures.

•	Security: The system should ensure the privacy and confidentiality of donor and recipient information, adhering to relevant data protection regulations




 
3.2 SCHEMA
Patient Table -


Column name	
Datatype	
width	
Constraint

id	INT	
10	
Primary Key

name	
VARCHAR	
50	
NOT NULL

blood_type	
VARCHAR	
3	
NOT NULL

last_transfusion_date	
DATE	
7	
NOT NULL



Blood_bank Table-


Col Name	
datatype	
Width	
Constraint

blood_bank_id	
INT	
10	
Primary Key

name	
VARCHAR	
50	
NOT NULL

address	
VARCHAR	
100	
NOT NULL
 
Donor Table –


Column Name	
Datatype	
Width	
Constraint

id	
INT	
10	
Primary Key

name	
VARCHAR	
50	
NOT NULL

age	
INT	
10	
NOT NULL

blood_type	
VARCHAR	
3	
NOT NULL

phone_number	
VARCHAR	
15	
NOT NULL

is_eligible	
BOOLEAN	
1	
NOT NULL

donation_count	
INT	
10	
NOT NULL
 
Donation Table


Col Name	
Datatype	
Width	
Constraint

id	
INT	
10	
Primary Key

donor_id	
INT	
10	
Foreign key

blood_bank_id	
INT	
10	
Foreign key

date	
DATE	
7	
NOT NULL


Transfusion Table



Col Name	
Datatype	
Width	
Constraint

id	
INT	
10	
Primary Key

patient_id	
INT	
10	
Foreign key

donation_id	
INT	
10	
Foreign key

date	
DATE	
7	
NOT NULL
 
3.3 DATA
Patient Table:

id	name	blood_type	last_transfusion_date
1	Alice	A+	2022-12-01
2	Bob	B+	2023-01-15
3	Charlie	AB-	2022-11-23
4	Dave	O-	2023-02-18
5	Emily	A-	2022-12-30

Blood bank TABLE :

Blood_bank_id	name	address
1	Blood Bank A	123 Main St, Anytown
2	Blood Bank B	456 Maple Ave, Otherville
3	Blood Bank C	789 Oak Rd, Smalltown

Donor TABLE :

id	name	age	blood_type	is_eligible	donation_count	phone_number
1	Frank	23	A+	1	3	555-1234
2	Gina	30	O+	1	8	555-5678
3	Henry	42	B+	1	2	555-1111
4	Irene	29	AB-	0	5	555-2222
5	Jack	37	O-	1	6	555-3333
 
Donation TABLE :

id	donor_id	blood_bank_id	date
1	1	1	2022-11-01
2	2	1	2023-01-01
3	3	2	2022-12-01'
4	4	3	2023-02-01
5	5	2	2022-10-01
1	1	3	2022-11-15
2	2	3	2023-01-15
3	3	1	2022-12-15
4	4	2	2023-02-15
5	5	1	2022-10-15
Transfusion Table:


id	patient_id	donation_id	transfusion_date
1	1	2	2023-01-16
2	2	1	2022-11-16
3	3	3	2022-12-16
4	4	4	2023-02-16
5	5	5	2022-10-16
		 
CHAPTER-4

4.0 USECASE DIAGRAM         


 




































4.1 E-R DIAGRAM







 
                                                 CHAPTER-5
                                                          
5.0 DDL AND DML QUERIES 

Patients Table:
DDL-
 

DML-




Donor Table:

DDL-
 

DML-
 

 
Blood bank Table-

DDL-
 

 

DML-
 

Donations Table-

DDL-
 
DML-

 
Transfusion Table-

DDL-
 

 
DML-

 
5.1 QUERIES

1.	Retrieve the names of all patients along with their blood types.


 

2.	Retrieve the names and phone numbers of all donors who have A+ blood type.

3.	Retrieve the names of all donors who have donated blood more than 5 times.


4.	Retrieve the names and blood types of all donors who are eligible to donate blood.


 
5.	Retrieve the names and addresses of all blood banks.


6.	Retrieve the names and phone numbers of all donors who have donated blood to a specific blood bank.






7.	Retrieve the total number of donations made by each donor.


 
8.	Retrieve the total number of transfusions received by each patient.




9.	Retrieve all donations made on a specific date of day 15.


10.	Show the total number of donations made by each donor, sorted in descending order. 

IMPLEMENTATION

1.	Retrieve the names of all patients along with their blood types.

 
 

2.	Retrieve the names and phone numbers of all donors who have A+ blood type.

 
 


3.	Retrieve the names of all donors who have donated blood more than 5 times.

 
 

4.	Retrieve the names and blood types of all donors who are eligible to donate blood.

 
 





5.	Retrieve the names and phone numbers of all donors who have donated blood to a specific blood bank.

 
 

6.	Retrieve all donations made on a specific date of day 15.

 
 






7.	Show the total number of donations made by each donor, sorted in descending order.

 
 

8.	Show the total number of donations made by each blood bank, sorted in ascending order of banks id

 
 





9.	 Display the max amount of blood donated by each donor sorted in descending order

 
 

10.	Retrieve the names of all patients wo have received a blood from donor with specific name

 
 



11.	Display the average age of donors who have made the donation sorted by age


					CHAPTER-6
   
    6.0 CONCLUSION

Prior to this project, a general study of blood bank management system was conducted from recent researches of various authors and facts were gathered in which helped to uncover the misfits that the system was facing. After proper analyzation of these problems, a solution was then developed in order to meet up the needs of a more advanced system. This system is known as the centralized blood bank repository which helped in eliminating all the problems that the previous systems were facing. With this system, Blood banks/ Centers, Hospitals, Patients and Blood donors will be brought together to enjoy a large number of functionalities and access a vast amount of information, thereby making blood donation and reception a lot easier and faster.

Before implementing the database, in the design phase, We have explored various features, operations of a blood bank to figure out required entities, attributes and the relationship among entities to make an efficient Entity Relationship Diagram(ERD). After analyzing all the requirements, we have created our ERD and then converted the ERD to relational model and normalized the tables.

In our project Blood bank management system we have stored all the information about the donors, patients, blood banks etc. This data base is helpful for the applications which facilitate users to check the details of different blood groups available and their donors from their place itself it avoids inconvenience of going to blood banks for each and every query they get.

We had considered the most important requirements only, many more features and details cand be added to our project in order to obtain even more user friendly applications. These applications are already in progress and in future they can be upgraded and may become part of amazing technology.
