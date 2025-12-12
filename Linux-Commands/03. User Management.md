User Management

1.	How do you create a new user in Linux?
● adduser username

2.	How do you delete a user?
● userdel username

3.	How do you lock a user account?
● passwd -l username

4.	How do you unlock a user account?
● passwd -u username

5.	How do you switch to another user?
● su - username

6.	How do you view currently logged-in users?
● who or w

7.	How do you check user account information?
● id username

8.	How do you list all users on the system?
● cat /etc/passwd

9.	How do you create a group in Linux?
● groupadd group_name

10.	How do you add a user to a group?
● usermod -aG group_name username

11.	How do you change a user’s default shell?
● chsh -s /bin/bash username

12.	How do you change a user’s home directory?
● usermod -d /new/home/dir username

13.	How do you create a system user without a home directory?
● adduser --system --no-create-home username

14.	How do you set or reset a user’s password?
● passwd username

15.	How do you check group memberships of a user?
● groups username