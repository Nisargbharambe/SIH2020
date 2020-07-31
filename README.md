# Instructions
Database: **cns_.sql**
<br>
<br>

Requirements: *** pip install -r requirements.txt *** <br><br>

In path: *SIH2020/admin/settings.py* <br><br>
For ***Windows***:
  Generally, here django doesn't have issues with pointing to mysql socket. 
  <br><br>**Delete**<br><br />
			**'OPTIONS':{
								"unix_socket": "/opt/lampp/var/mysql/mysql.sock",
						}**						          <br>from **DATABASES['default']**
						
For ***Linux***:
	If using Lampp stack, please retain **OPTIONS** in **DATABASES['default']** as mysql is present in /opt/lampp/lampp
