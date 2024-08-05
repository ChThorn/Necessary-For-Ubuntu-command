# Necessary-For-Ubuntu-command
In Ubuntu, there are three types of divisions for users which are owner, group, and others.

The first user or admin is normally named root

To access this root, you have to write `su root` in the terminal. And its password is written as `sudo passwd your_username`

If you want to clear or delete the password, write `sudo passwd -d your_username`

To create new user name write `sudo adduser username`

Also, in Ubuntu normally use command as `chmod -rwxrwxrwx file_name` for changing permission and `chown username_wanted_to_assign filename`

Fore example, `chmod 777 filename`

## For two users, we can share permission of a folder by this cmd,

`sudo setfacl -R -m u:chickenuser:rwx yourdatafolder` for directory folder permission. 

Also, to verify the permission, we can use `getfacl -R yourdatafolder`.
