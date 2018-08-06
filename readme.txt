Configuration
===============================================================

1. Edit the "db.php" file to configure the MySQL Database connection. 
	Update the 4 Constants for HOST, USER, DATABASE, PASSWORD. 

2. Place the project folder in the root directory of the Web Server. 

3. Open the Browser - Run setup.php file to create and populate database. 

	Local:    localhost/project-folder/setup.php
	Web:	  http://server.com/setup.php    if placed directly under root
	   		  http://server.com/folder-name/setup.php if placed inside a folder


Testing:
================================================================================

1. Once database has been installed

	Run the application by opening index.php file that is also the default 
	welcome file to render. 

2. Login 

	Admin: UserName: admin, Password: admin
	Owner: First char of first name concatenated with lastname
			all uppercase: same is for the password. 


3. Admin Navbar:
		cats - lists the cats
		dogs - lists the dogs
		exotics - lists the exotics
		owners - lists the owners 

4. Owner Navbar:
		
		pets - lists the pets of the owner in 3 css grids Dogs, Cats and Exotics respectively. 

5. On Cats, Dogs, Exotics
	
	Admin can perform following functions

	a. sort by column
	b. filter by column (startsWith pattern)
	c. click notes button to view the notes of the pet
	d. click owner button to view the owner of the pet. 
