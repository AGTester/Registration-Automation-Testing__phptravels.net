Challenge Requirements:
Go to this URL (https://www.phptravels.net/register) to register new user.
1. Enter "First name"  which must start with capital letter.
2. Enter Last Name which must start with capital letter and can’t be equal "First name" .
3. Enter a valid Mobile Number.
4. Enter a valid E-mail that should be unique for every user.
5. Enter a Password and check that it must have capital letter, small letter, with a limit of 8
characters.
6. After successful registration, verify that the user can login.
Note: All fields are mandatory.

****************************************************************************
How my solution works:
Analysis main required.
Check https://www.phptravels.net/register and learn how to sign up an account manually.
Write test cases valid or invalid for registration page.
Start our automation project  implemented with an object-oriented design to 3 pages and 2 tests
Start writing automation script.
Run our tests.
Test our automation project usability and and check invalid results in console and screenshot folder.
Implement HTTP inspectors and save response in console.
Implement customized reporting screenshots for failures in screenshots folder.

Features:
Automation project can automate all registration process.
 Find bugs and reporting it to console and screenshots
 Check request response in console
We can track our test process visually in chrome.
Read every live step in console by EventReporter.Inserting all values of registration form, use submit button.
check successfully moving to registered profile home page
Limitations:
I think it's better to save the response in external folder I don't have much time for searching about that.
*************************************************
Test cases:
Sending Valid values for all Fields 
Sending Valid values for all Fields except - "First name" Invalid Value: Start with small letter.
Sending Valid values for all Fields except - "First name" Invalid Value: Empty field.
Sending Valid values for all Fields except - "First name" Invalid Value: Numbers.
Sending Valid values for all Fields except - "Last name" Invalid Value: Start with small letter.
Sending Valid values for all Fields except - "Last name" Invalid Value: Empty field.
Sending Valid values for all Fields except - "Last name" Invalid Value: Numbers.
Sending Valid values for all Fields except - "First name" = "Last name"
Sending Valid values for all Fields except -  "Mobile Number" Invalid Value: "123" 
Sending Valid values for all Fields except -  "Mobile Number" Invalid Value: "xyz"
Sending Valid values for all Fields except - "Email" Invalid Value: "asdf"
Sending Valid values for all Fields except - "Email" Invalid Value: Old registered Email.
Sending Valid values for all Fields except - "Password" Invalid Value: with No capital letter
Sending Valid values for all Fields except - "Password" Invalid Value: with No small letter
Sending Valid values for all Fields except - "Password" Invalid Value: short password
Sending Valid values for all Fields except - "Password" = "Confirm Password" 
