# NSCC-YEAR-1-TASK
A simple client-side signup form and user dashboard built with HTML, CSS, and JavaScript. Users can register with a username, email, and password, with basic validation for required fields, duplicate accounts, and password strength.  Registered user data is stored in the browser's localStorage.

Signup & User Dashboard

A simple front-end project built using HTML, CSS, and JavaScript.

This project is a basic signup system where users can create an account by entering their username, email, and password. The entered details are validated and then displayed in a dashboard.

The project also uses localStorage to save the registered users, so the data remains available even after refreshing the page. 

The main idea behind this project was to understand how a signup form works and how JavaScript can be used to manage user data.

It includes a signup form, input validation, local data storage, and a dashboard where registered users can be viewed and deleted.

The project is completely front-end based and does not require any backend or database.

ALGORITHM USED IN THE CODE IS AS FOLLOWS:
1) User Signup — Create an account using a username, email, and password.
2) Form Validation — Checks whether the entered details are valid.
3) Username Validation — Requires at least 3 characters.
4) Email Validation — Checks the email format.
5) Password Validation — Requires at least 8 characters, one uppercase letter, and one number.
6) Duplicate Prevention — Prevents the same username or email from being registered twice.
7) Local Storage — Saves user data in the browser.
8) User Dashboard — Displays all registered users in a table.
9) Registration Time — Shows when each account was created.
10) Delete User — Allows registered users to be removed.
11) Success Message — Displays a confirmation after successful signup.
12) Responsive Design — Works on different screen sizes.
13) Clean UI — Uses a simple card-based layout.
Technologies Used for creating the code:
1) HTML5	Creating the structure of the webpage
2) CSS3	Styling the form, cards, buttons, and dashboard
3) JavaScript	Form validation and user management
4) localStorage	Saving registered users in the browser

1) Signup Form: The signup form allows users to enter their details and create an account.
2) Form Validation: The application displays error messages when the entered information is invalid.
3) User Dashboard:The dashboard displays the registered users along with their email, registration time, and delete option.

how the project Works:
The project uses JavaScript to handle the signup form and manage the registered users.

When a user submits the form, the application checks whether the entered details are valid. If everything is correct, the user is added to the stored list.

The data is saved using localStorage, which allows it to remain available after refreshing the page.

The dashboard then displays the saved users in a table. Each user also has a delete button that removes the account from the stored list.

Data Storage: The project uses the browser's localStorage to store registered users.

const STORAGE_KEY = 'signupUsers';

The stored data includes: Username, Email, Password, Registeration date and time.

Since the data is stored locally, it is only available in the browser where the project is being used.


Code by:-Ishaan Adwitya Puggal
