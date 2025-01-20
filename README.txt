0-  You should run yml files on python virtual environment and install pyvmomi on it. 
1-	Check v-center configuration from hosts.ini file.
2-	Open create_vm_from_template.yml file
3-	Customize vm configuration
4-	Edit windows server ip from hosts.ini
5-	Run create_vm_from_template.yml to implement windows server core machine.
6-	Run ad_pre_install.yml file to implement active directory prerequisites.
7-	Open active_directory_conf.yml file.
8-	Customize domain name and safemode administrator password.
9-	Run active_directory_conf.yml to install active directory on windows server.
10-	After running active_directory_conf.yml you should change login information on hosts.ini file to administrator@DOMAINNAME.LOCAL
11-	For create ou and users you should import csv file like users.csv and edit createfromcsv.yml csv file path and also domain names.
12-	Run createfromcsv.yml file to create ou and users.
13-	End
