The “Donation Management System” is a web‑based platform designed to streamline the process of donating excess resources (food, clothes, books, gadgets, etc.) directly from individual donors to needy recipients or organizations, eliminating intermediaries and reducing waste 

Key Objectives and Features

Donor & Seeker Registration: Allows donors to sign up, list available items, and seekers (or volunteers) to register interest or request specific donations.
Search & Matching: Seekers can filter donors by name, location or donation category; donors and volunteers can be managed and hidden or deleted upon request 
Admin Dashboard: Central control for administrators to manage donor/seeker records, approve or remove entries, and edit informational pages (About Us, Contact Us).

System Architecture & Design

Three‑Tier DBMS:
External (view) level for end‑user interaction
Conceptual (logical) level for schema and constraint enforcement
Internal (physical) level for storage organization
Relational Schema: Core tables include Admin, Donor, Requirer, Group, ContactUsInfo, ContactUsQuery, Pages, and Deletion, linked via primary‑key/foreign‑key relationships as depicted in the ER diagram 


Implementation Stack

Backend: PHP running on Apache via XAMPP, interfaced with MySQL for data persistence
Frontend: HTML5, CSS3, JavaScript and Bootstrap for responsive, mobile‑first design
Tools: XAMPP v3.3.0 (PHP ≥5.3, MySQL ≥5.5), latest web browsers 


Outcomes & Future Enhancements

1. Demonstrated robust functionality for donor‑seeker matching and admin oversight
2. Proposed enhancements include automated donation-status updates, temporary vs. permanent donor tracking, donor‑uploaded images, e‑certificates, time‑based deletion for perishable goods, and gamification (badges) to boost engagement.


How to run the Donor Excess Using PHP and MySQL

1. Download the zip file
2. Extract the file and copy bbdms folder
3.Paste inside root directory(for xampp xampp/htdocs, for wamp wamp/www, for lamp var/www/HTML)
4.Open PHPMyAdmin (http://localhost/phpmyadmin)
5. Create a bbdms with the name bbdms
6. Import bbdms.sql file(given inside the zip package in the SQL file folder)
7. Run the script http://localhost/bbdms

Admin Credential
Username: admin
Password: Test@123

Donor Credentials:
Register a new user.
