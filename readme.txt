Simple project showing basic user registration and transactions tracking.

The user registration is as one should expect. You chose a username and two fields for password and password repetition.

When a user is selected from the Users table, his transactions are displayed in the second table ( the one below ).
If needed a the username and password of any user can be edited inline.
A new transaction can be added by editing inline any field ( except the id field ) of the last row of the transaction table.

When a user is selected , the "Save Selected User To File" can save the users transactions to a file.
The file name is the user's ID, if the file already exists the file is overridden.

There is also a 2-3 simple checks
 - 1 - Check if all fields are filled in the user registration
 - 2 - Check if the passwords match
 - 3 - Check if a User is selected to save his transactions to file.

For these checks , if any one of these fails , a proper message is invoked.