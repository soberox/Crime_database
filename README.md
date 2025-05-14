# Crime_database
This a crime database that went through the different design phases in database development. This was done as a joint collaboration with Vimal Murugan, and  Jax Fonseca-Folden. Both UNCC students.

# Description
This database is done in MySQL enterprise edition. This database can have an array of uses, for many different kinds of users;
* Private Business
Employers within the private sector have the ability to make assessments of any hired employee within 7 years prior. This would mean they need access to all public information of their employees, like their court       sessions, adjudication status, and offense. This would only apply if an employee has been formally charged
* General Public
Citizens should have the ability to view personal case files, court sessions, and basic records information.
* Government Employees
Government employees need to be able to access all records pertaining to their cases This includes on-going case files or consolidated case, and all information that may be linked to it. Such as court session.
* Government Agencies
Government agencies would have access to the entire crime database in order to ensure potential new hires have not committed egregious crimes. This would include that the agencies would be able to see all case files, offenses, and any government employee that worked on a case.

With a total of 11 table (with 5 bridge tables), and 14 stored and views the database is capable of generating queries for public use, crime analytics, and bureaucratic endevors. 

When it comes to database implementation and design, the hardest challenges comes largely from the design and the different stages from conception to structural design. One particular challenge was deciding on the normality level, and the cardinality that thes tables should have.

#Files
Here I provided a copy of the database, with some insert statments to test the queries, I also added a document that would further document our development process with a ER diagram.
