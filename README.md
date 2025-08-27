🕵️‍♂️ Lost & Found Web Application

A simple Lost & Found web application to report, search, and track lost or found items, built with HTML, CSS, JavaScript, JSP, and Oracle SQL.

📌 Table of Contents

Overview

Features

Technology Stack

Installation & Setup

Database Schema

Usage

Contributing

License

🔍 Overview

The Lost & Found Web Application allows users to report lost or found items and connect with others to recover them. It offers a user-friendly interface and admin management for verifying submissions.

✨ Features

User Authentication: Secure login and registration.

Report Lost Item: Submit lost items with details and images.

Report Found Item: Submit found items to help owners recover them.

Search & Filter: Quickly find items by category, name, or date.

Admin Panel: Manage, verify, or delete items.

Database Integration: All data stored in Oracle SQL.

🛠 Technology Stack

Frontend: HTML, CSS, JavaScript

Backend: JSP (Java Server Pages)

Database: Oracle SQL

Web Server: Apache Tomcat

🚀 Installation & Setup

Clone the repository:

git clone https://github.com/your-username/your-repo-name.git


Open in IDE: Import project into a Java IDE like Eclipse.

Database Setup:

Create an Oracle SQL database.

Run the provided SQL scripts to create tables (database.sql).

Configure Connection: Update database credentials in your JSP files.

Deploy: Run on Apache Tomcat server.

Access: Open http://localhost:8080/your-app-name in a browser.

💾 Database Schema

Users: Stores user credentials and profiles.

LostItems: Stores reported lost items.

FoundItems: Stores reported found items.

Admin: Stores admin credentials for item verification

🖱 Usage

Register or log in.

Submit lost or found item details.

Search for items by keywords or categories.

Admin reviews and manages submissions.
