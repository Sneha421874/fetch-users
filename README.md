Fetch and Display Data from a Public API Using Fetch API
 Objective
Build a simple webpage that fetches user data from a public API using the JavaScript Fetch API and displays it dynamically on the screen.

 Tools Used
HTML – structure

CSS – styling

JavaScript (Fetch API) – get data from API

VS Code – code editor

Chrome Browser – to test the webpage

 Public API Used
We are using a free fake REST API:

https://jsonplaceholder.typicode.com/users
This API returns sample user details like name, email, phone, and address.

 Project Structure
project-folder/
│
└── index.html   # Contains HTML, CSS, and JS code combined
 How to Run the Project
Create a new folder on your computer.

Create a file named index.html inside it.

Copy-paste the provided full code into the file.

Open the file in your browser (Chrome recommended).

Click the "Fetch Users" button to load user data.

 Features
Fetches live user data from an API

Displays users in a grid layout

Stylish UI with cards

Uses only HTML + CSS + JavaScript (no frameworks)

Beginner-friendly Fetch API example

 How the Fetch API Works in This Project
User clicks the button

JavaScript sends a request to the API using:

fetch("https://jsonplaceholder.typicode.com/users")
API returns a JSON response

Data is displayed dynamically using DOM methods

Cards are created for each user

 Output Preview
A button to fetch users

Below the button, user cards appear with:

Name

Email

Phone

City

 Good For
Fetch API beginners

JavaScript practice

API demo projects

College lab assignments

Web development mini-projects
