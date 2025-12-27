Attendance Prototype

This repository contains a simple front-end attendance prototype built using HTML and JavaScript.
The purpose of this project is to demonstrate conditional attendance marking logic based on multiple verification checks.

Project Description

The application allows a user to enter a Student ID and simulate verification steps using checkboxes.
Attendance is marked only when all required conditions are satisfied.

All logic is implemented directly inside index.html using basic JavaScript.

Features Implemented

Text input for Student ID

Device verification simulation using a checkbox

GPS / Wi-Fi verification simulation using a checkbox

Button to mark attendance

Result message displayed based on validation outcome

Working Logic

Attendance is marked only if:

Student ID is entered

Device verification is checked

GPS/Wi-Fi verification is checked

If any condition is missing, attendance is not marked and an error message is shown.

Technologies Used

HTML

JavaScript

No external libraries or frameworks are used.

How to Run

Clone or download the repository

Open index.html in any modern web browser

Enter a Student ID

Select the verification checkboxes

Click Mark Attendance to see the result

Limitations

No real QR code scanning

No actual GPS or Wi-Fi validation

No backend or database

Data is not stored permanently

This project is intended only as a prototype/demo.

File Structure
attendance-prototype/
└── index.html

Purpose

This project serves as a basic prototype for understanding how multiple conditions can be checked before allowing attendance to be marked in a web-based system.
