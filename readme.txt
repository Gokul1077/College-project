# ABOUT THIS PROJECT:
# 
# Contact Management System  is created in Python. The data has a python script (index.py).
# In the course of building your program one of the first things that gets created is the contacts.txt file.
# If this file doesn’t exist though, as is the case when the program is run for the very first time, Python will stop 
# execution of the program, and indicate that fact as an error.
# Speaking about the system, it consists of all the called for functions that include adding, viewing, removing and also     upgrading contact lists. 
# While including the call of a person, he/she has to provide given name, address and contact information. 
# 
# PROGRAM SPECIFICATION:
# 
# Program that has functions to:
# a. add an entry into a "list of lists" called contacts (add_contact function).
# b. write the contacts data to the "contacts.txt" data file before quitting the program.
# c. view all the information in contacts (view_all_contacts function).
# d. open the "contacts.txt" data file and place them into the contacts list (the initialize
# function)
# e. let the user to search for a name in contacts, and then prints out that person's information 
# (find_contact function)
# f. let the user delete an entry (delete_contact function)
# 
# Each line of "contacts.txt" will contain the record for a single person, with data fields on that line 
# separated by the delimiter "\t" (Tab), as shown 
# 
# BACKGROUND
# One strategy for keeping track of data, even when a program isn’t running, is by storing it in a database, an
# external file. The simplest type of database is a “flat-file” database, in which information is stored as 
# strings of text.
# In the example contacts.txt file shown below, each of the three lines is a “record” of one person, and 
# each section of a line (separated by a “delimiter”, a tab in this case) stores a data “field”: names, email 
# address, and phone number. The information in this text file will be loaded in to the program. 
# when that program is run, and a menu system will run the contact information as 
# the user desires.
