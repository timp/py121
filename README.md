# py121


## Security

The data held in the register, whilst it does contain 
Personally Identifiable Information (PII) is all publicly available 
information within the school. 

Requiring the user to login with a password before accessing the 
data held in the system is an attempt to provide protection for this 
data however as the data is not encrypted we must be attempting to 
protect it by ensuring that a potential data thief has no other route 
to the data store. 

The system is envisaged as being run upon a normal personal computer 
running a unix operating system. If the attacker has complete access 
to the system then she can read the data file directly: 
calling the data file Students.csv sabotages the protection afforded 
by the password, as the attacker need only click upon the data file for 
it to be automatically opened by the system's spreadsheet reading 
application.

If the system is deployed upon a website hosted upon a remote machine 
accessed over the internet then there is less chance that the datafile 
could be accessed by other methods. 

For a locally run application with a password the datafile should 
either be encrypted. An unencrypted file could be given a meaningless 
name and file extension, but this is just security through obscurity.

!References
https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world
