# friendship-zone-html5-capstone
HTML5 Capstone Project for Infosys Springboard: A static web application featuring multi-page navigation, semantic HTML, and built-in form validation.

# Friendship Zone - HTML5 Capstone Project

## Overview
**Friendship Zone** is a static web application built as a capstone project for the **Infosys Springboard HTML5** course. The application allows users to view a list of potential friends and register for the platform. It demonstrates the use of semantic HTML5 elements, table structures, form creation, and client-side form validation.

## Features Implemented
This project consists of 5 interconnected HTML pages:

* **`Homepage.html`**: The landing page featuring semantic sectioning, external social media links, and navigation to the friend list.
* **`FriendList.html`**: Displays a structured data table containing details of available people on the platform, along with a link to the registration page.
* **`RegistrationForm.html`**: The core interactive page containing a user enrollment form. It includes strict HTML5 validations:
    * **Name**: Mandatory field, minimum 3 characters, no numbers allowed.
    * **Email**: Must follow a valid email format.
    * **Age**: Accepts only digits and restricts registration to individuals 18 and older.
    * **Dual Submission**: Features separate buttons to register as a standard User (triggers validation) or an Admin (bypasses validation).
* **`RegistrationConfirmation.html`**: A success page for standard users, with a link to return home.
* **`RegistrationConfirmationforAdmin.html`**: A success page for administrators, with a link to return home.

## Tech Stack
* **HTML5**: Used for structuring content, semantic layout, and native form validation.

## Development Tools
* Visual Studio Code (IDE)
* Live Server (VS Code Extension)
* Google Chrome
