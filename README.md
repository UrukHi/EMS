# EMS
Employee Management System
Employee Management System:

The purpose of the software requirements document is to systematically capture requirements for the project and the “Employee Management System” to be developed. Both functional and non-functional requirements are captured in this document. It also serves as the input for project scoping. 
The scope of this document is limited to addressing the requirements from a user, quality, and non-functional perspective. 
Purpose	
In the current system, Admin adds new regulations and assigns them to the department manually. Department Head sends these regulations to the individual users through mail to get their consent. Users send their comments through the courier service after reading regulations. Department head has to collect the user inputs and pass them on to Admin. Since a lot of manual workflow is involved, it is time consuming for Admin to close each regulation.
So, a new system is required to automate this regulation creation and closure process.
In Scope
Employee information creation and maintenance
Department creation and maintenance
Regulation creation and maintenance
Mapping each employee to the respective department
Updating/viewing user comments on the assigned regulations
Out Scope
Loading the employee list into the application
Notifications on the status 




docker run --name some-mysql -e MYSQL_ROOT_PASSWORD=password -e MYSQL_DATABASE=ems -e MYSQL_USER=ems  -p 3306:3306 -d mysql
