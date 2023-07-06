# Sign-in-Sign-up
Welcome to the Project Sign-in / Sign-up repository! This project is a web application built using PHP and MySQL for user registration and authentication.

## The About
This project is a simple web application that allows users to register an account, log in, and view a home page with personalized content. It demonstrates basic user authentication and session management using PHP and MySQL.

### The project consists of the following files:

<ul><li><code>index.php</code>: The main page of the application where users can log in, view their personalized content, and log out.</li><li><code>register.php</code>: The registration page where new users can create an account.</li><li><code>server.php</code>: Contains the server-side logic for user registration and authentication.</li><li><code>errors.php</code>: A reusable file that displays any error messages encountered during registration or login.</li><li><code>style.css</code>: The CSS file for styling the application.</li></ul>

## Features
<ul><li>User registration: Users can create a new account by providing a unique username, email, and password.</li><li>User login: Registered users can log in using their username and password.</li><li>Session management: User sessions are maintained using PHP's session management functions.</li><li>Personalized content: After logging in, users are greeted with a personalized welcome message and can view the main content of the application.</li><li>Logout: Users can log out to end their session.</li></ul>

## Installation
To run this project locally, you need to have PHP and MySQL installed on your machine. Follow these steps:

<ol><li>Clone this repository: <code>git clone &lt;repository-url&gt;</code></li><li>Import the database: Create a new database in MySQL and import the provided SQL code (<code>database.sql</code>) to set up the required <code>users</code> table.</li><li>Configure database connection: Open <code>server.php</code> and modify the database connection details (host, username, password, database) as per your MySQL configuration.</li><li>Start the PHP development server: In the project directory, run <code>php -S localhost</code> in the command line.</li><li>Open your web browser and visit <code>http://localhost</code> to access the application.</li></ol>

## Usage
<ol><li>Register: On the homepage, click the "Register" link to navigate to the registration page. Fill in the required details and submit the form.</li><li>Login: After registering, you will be redirected to the homepage. Enter your username and password and click "Login" to log in.</li><li>Personalized content: Once logged in, you will see a welcome message with your username. Below that, you can view the main content of the application.</li><li>Logout: To end your session, click the "logout" link at the top of the page.</li></ol>

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
