# FunOlympicWebsite
Step 1: Install Visual Studio Code.

Step 2: Install python in the Visual Studio Code Application. 

Step 3: Create virtual environment using -> ‘mkvirtualenv envname’ in python operating  
        system. 

Step 4:  Activate created virtualenv  i.e suppose if  ‘barshaOlympic folder’ the virtual environment 
         that has been created then activate the environment using code : ‘workon barshaOlympic’.

Step 5: Enter into virtual environment (i.e. barshaOlympic).

Step 6: Install all the required server requirements i.e. ‘requirements.txt’ file containing all the 
        important dependencies for running a website properly.

Step 7: Move inside the folder containg ‘manage.py’  using code ‘cd folder name’ . For eg:
        “cd fun_olympic_project - Barsha”.

Step 8: Obtain a domain name i.e. create superuser i.e. admin as Django administratior using code: ‘django-admin createsuperuser’ The username and password that will be used when creating the superuser is the admin’s username and password. (Username: basnet.admin@gmail.com, Password: B@r12345)

Step 9: After obtaining a domain name for the server, register/manage the default server’s IP address using code: ‘python manage.py runserver’ However,if we want to change the port number than we can use the code: ‘python manage.py runserver portnumber’ for opening the website using different port.  For example: let’s suppose if my default port is not working or if  I want to register my IP address in port 8080 than the code to change the port is: ‘python manage.py runserver 8080’. Once this is done, the server/website can be accessed using a URL.
