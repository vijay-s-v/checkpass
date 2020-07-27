# checkpass

This program checks the provided password against a file of passwords (passwords.txt). All passwords in the file are stored in their own line. They are put into a hash table upon execution of the program. If the password is valid, is not already in the passwords file, and its reverse is not already in the passwords file, the program stores this new password in the file, prints VALID, and exits. If not, the program prints INVALID and exits. 

Password criteria:
- Alphanumeric without special characters
- 6 to 12 characters long

