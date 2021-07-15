# Deploying the LAMP stack on IBM Cloud Virtual Servers with IBM Cloud Schematics

You must retrieve the following values to run the playbook in IBM Cloud Schematics.​

Input variable	Required / optional	Data type	Description
upassword	Required	String	Enter a password for your MySQL user, according to MySQL password policy. For example, Abc@123abc.
dbname	Optional	String	Enter the name that you want to use for your MySQL database. The default database name is mysqldb.
dbuser	Optional	String	Enter a username that you want to set up for your MySQL database. The default user is root.
mysql_port	Optional	String	Enter the port number that your MySQL database listens on. The default port is 3306.
httpd_port	Optional	String	Enter the port number that your Apache HTTP Webserver listens on. The default port is 80.
