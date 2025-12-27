## Attendance Prototype

## Overview
This repository contains a simple front-end attendance prototype developed using HTML and JavaScript.  
The project demonstrates how attendance can be marked only after certain validation conditions are met.

## Project Description
The application provides a basic interface where a user can enter a Student ID and simulate verification steps using checkboxes.  
Attendance is marked only when all required checks are completed successfully.

All logic is implemented directly inside a single HTML file without using any backend services.

## Objective
The objective of this project is to understand and demonstrate basic conditional logic in a web-based attendance system.

## Features
Student ID input field  
Device verification simulation using a checkbox  
GPS / Wi-Fi verification simulation using a checkbox  
Attendance validation using JavaScript  
Result message displayed based on validation outcome  

## Working Logic
The attendance marking process follows these rules:  
Student ID must be entered  
Device verification must be checked  
GPS / Wi-Fi verification must be checked  

If all the above conditions are satisfied, attendance is marked successfully.  
If any condition is missing, attendance is not marked.

## Technologies Used
HTML for structure  
JavaScript for logic and validation  

No external libraries, frameworks, or APIs are used.

## How to Run
Download or clone the repository.  
Open the index.html file in any modern web browser.  
Enter a valid Student ID.  
Select both verification checkboxes.  
Click the Mark Attendance button to view the result.

## File Structure
attendance-prototype/  
index.html  

## Limitations
This project does not include real QR code scanning.  
GPS and Wi-Fi verification are simulated using checkboxes.  
There is no backend or database integration.  
Attendance data is not stored permanently.

## Use Case
This prototype can be used as a learning example for beginners to understand how multiple conditions can be validated before performing an action in a web application.

## Future Scope
Integration of real QR code scanning.  
Actual GPS or network-based verification.  
Backend support for storing attendance records.  
User authentication and role-based access.

## Status
Completed – Prototype version.

## Note
This project is intended for learning and demonstration purposes only.
