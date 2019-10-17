# Fields control
This is a simple list of controls to do when registrate or login an user in you application or website.

## User registration
* Check for empty fields.
* Check if the email is valid.
* Check for the password length.
* Check if the password has numbers and special chars.
* Check if the confirmation password matches.
* Check if the inserted birth date has a valid pattern.
* Check user age.
* Check if the email already exists into the database.
* Data formatting:
  - Capitalize first letter of name and surname and strlower the other letters.
  - Lower case email.
* Hash password and save user into the database.

## User login
* Check for empty fields.
* Check if the email is valid.
* Data formatting:
  - Lower case email.
* Check if credentials are valid.
* If credentials are valid:
  - Update database user last access.
  - Create user session or cookie.
