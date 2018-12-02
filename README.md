# Item Catalog - Udacity
### Full Stack Web Development ND
_______________________
## About
This project, we have a restaurant database that has a menu 
that shows items and there is the user table that shows the users.
we want each user with an account in google to Login, the user can add a menu and edit the menu and delete the menu, the same goes for menu items.
each user can only edit and delete what he added.
for those who did not log in, they can only view the restaurants and the menu and items.


## Prerequisites
* [Python ](https://www.python.org/downloads/release/python-271/) 
* [Vagrant](https://www.vagrantup.com/)
* [VirtualBox 3](https://www.virtualbox.org/wiki/Downloads)


## Getting Started 
after installing vagrant you should ```cd``` into vagrant file, then move the ```oauth``` inside it, then in the terminal run ```vagrant up```, after it finished run ```vagrant ssh``` now you are inside the Virtual Machine, you should now ```cd /vagrant/``` then ``` oauth ```  
* fisrt set the data base by runing ```database_setup.py ```
* then seed the database by running ```lotsofmenus.py```
* then  run ```project.py```
 



