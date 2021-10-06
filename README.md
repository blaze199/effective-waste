# effective-waste-management
PBL Project by Group 7

Group Members :
  
  	Devang Punatar
  
	Aaryan Pimple
  
	Sahil Paranjape
  
	Ganesh Nikam
	

Project Features :

	- User identification and authentication
	- Separate Users' (**ADMIN, CLIENT**) privilegdes
	- perform various crud functionalities e.g manage wastes, clients, gadgets
	- Generate customized reports based on the user's priviledges
	- Added SMS and Payment Gateways
	- Plus more awesome features to be explored and to find by yourself.	
	
		- **Admin functionalities**
			+ Manage System settings
			+ add/edit/delete gadgets.
			+ Approve/Dissaprove e-waste disposes.
			+ Mangae clients.
	
		- **Client functionalities**
			+ Add disposes he/she wants to dispose.
			+ Track the disposes individually.
			

Installation Steps :

	One is required to follow the instruction/or procedures as shown in the installation above for Xampp Server. The installation of the above enables the system to have PHP and MySQL installed in the directory; C:\Xampp directory and all other program files.

i)	Create a local folder named "**e-waste**" in htdocs directory found in Xampp Server. 	This is the default publishing folder i.e. C:\Xampp\htdocs for all systems installed using Xampp Server 3.2.2.

ii)	Open command prompt(cmd) and navigate to the folder "**e-waste**" C:\Xampp\htdocs\e-waste.

iii)	Clone the project by running the following bash command:

``` 
$ git clone https://github.com/blaze199/effective-waste-management.git
```

iv) Open ewaste.sql and copy all the database schemas inside and paste it in your phpmyadmin server under the SQL tab of your mysql server. This action copies all the system tables and queries.

v) You are almost done. Navigate to your browser open this link URL <http://localhost/e-waste/> to view your already set project.


Admin Default Credentials :

username: **admin@gmail.com**

password: **admin123**

You can always change this credentials once you have logged in with this default credentials in the profile section. Admin can also add client once logged in. There is an option for clients to register themselves too.
