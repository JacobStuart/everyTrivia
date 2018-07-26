Jacob Stuart 811313024
Austin Priest 810639132
Kyle Aig-Imoukhuede 811019681

To get working:
	SET UP DATABASE
		A self contained .sql file is included.  This has the schema, tables, and tuples contained in it.
		Import it into your local MySQL server.

	Connection to database
		Go into the source files and find application.properties.  Change the username and password to what
		the root username and password are for the local MySQL server.
			-If you are looking in the zip file everything is located in the target folder


	Running the program
		Our program uses springboot.  We have included both a jar file (again you will need to change
		application.properties) and an alternative zip file containing the source code.  Start the internal springboot
		server, go into a browser and connect to localhost:8080.