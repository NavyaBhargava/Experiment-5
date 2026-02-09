# AIM: Study of Dictionaries in Python

# THEORY:
 Dictionaries are used to store data values in key:value pairs. A dictionary is a collection which is ordered*, changeable and does not allow duplicates. Dictionary takes latest value given for key.

# ALGORITHM:

 i.A dictionary stores product names and their prices. Write a python program to update the price of a given product.
   1. Start
   2. Define dictionary products = {Pen: 10, Book: 50, Scale: 20}
   3. Display the original product list
   4. Update the price of the given product (Book = 55)
   5. Display the updated product list
   6. Stop
      
ii.A dictionary stores student names and marks. Write a Python program to search for a student's mark. If the student is not found, display a suitable message.
 1. Start
 2. Create a dictionary containing student names as keys and marks as values
 3. Read the student name from the user
 4. Check whether the entered name exists in the dictionary
 5. If the name exists, display the corresponding mark
 6. Otherwise, display “Student not found”
 7. Stop

iii. A dictionary stores username and passwords. Write a Python program to validate user login.
 1. Start
 2. Create a dictionary storing usernames as keys and passwords as values
 3. Read the username from the user
 4. Check if the username exists in the dictionary
 5. If the username exists:
     a. Read the password from the user
     b. Compare the entered password with the stored password
     c. If both match, display “Login Successful”
     d. Otherwise, display “Invalid Credentials”
6. If the username does not exist, display “User not found”
7. Stop

iv.  A dictionary stores students names and marks. Write a Python to find the student who scored the higest marks.
  1. Start
  2. Create a dictionary with student names as keys and marks as values
  3. Use the max() function with dictionary values to find the key having the highest marks
  4. Store the result as the topper
  5. Display the topper’s name and their marks
  6. Stop
