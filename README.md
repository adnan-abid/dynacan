This is a crude demo app for dynamic roles and permissions. It uses ruby 1.9.2 and rails 3.2.8. 
For sake of simplicity and to show the core functionality, i have created only 2 users, each with different role. User 'superman@superadmin.com' has role "Super Admin" can only he can assign the permissions to other roles ('Staff' in this case). User 'neo@matrix.com' has role "Staff". U can assign using both the above email ids and check the functionality. The password is 'prasad' for both the logins.

https://github.com/prasadsurase/dynacan

For detail explanation read http://blog.joshsoftware.com/2012/10/23/dynamic-roles-and-permissions-using-cancan/
