# Necessary-For-Ubuntu-command
In Ubuntu, there are three types of divisions for users which are owner, group, and others.

The first user or admin is normally named root

To access this root, you have to write _**su root**_ in the terminal. And its password is written as _**sudo passwd your_username**_

If you want to clear or delete the password, write _**sudo passwd -d your_username**_

To create new user name write _**sudo adduser username**_

Also, in Ubuntu normally use command as _**chmod -rwxrwxrwx file_name**_ for changing permission and _**chown username_wanted_to_assign filename**_

Fore example, _**chmod 777 filename**_

** For two users, we can share permission of a folder by this cmd, _**sudo setfacl -R -m u:chickenuser:rwx yourdatafolder**_ for directory folder permission. Also, to verify the permission, we can use _**getfacl -R yourdatafolder**_
