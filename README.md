Blood Bank & Donor Management System

A web-based Blood Bank & Donor Management System developed using PHP and MySQL. This system is designed to streamline the process of blood donation by maintaining a database of donors, managing blood group records, handling donation requests, and facilitating effective communication between donors and recipients. The system offers separate modules for administrators and users (donors), ensuring secure access control and role-based functionality.

⸻

Table of Contents:
	•	Features
	•	Technologies Used
	•	Installation Instructions
	•	Admin Credentials
	•	Donor Credentials
	•	Project Modules
	•	License

⸻

Features

Admin Panel:
	•	Provides a complete dashboard to monitor overall activity such as blood group statistics, total donor count, and user enquiries.
	•	Enables adding or removing blood groups as needed.
	•	Displays a comprehensive donor list with options to hide or delete entries.
	•	Handles user queries submitted via the Contact Us form.
	•	Allows management of static content on pages such as About Us.
	•	Admins can update the official contact information displayed on the site.
	•	Tracks and views all incoming blood donation requests from registered users.
	•	Admins can update their profile, change their password, and reset credentials if needed.

User/Donor Panel:
	•	Users can register as donors and provide their details.
	•	Donors can be searched based on city and blood group.
	•	Displays an updated donor list viewable to all users.
	•	Users can send blood request notifications to specific donors.
	•	Donors can manage their profile, change or recover their password.
	•	Allows users to contact the admin via the Contact Us form.

⸻

Technologies Used
	•	Core PHP (Procedural)
	•	MySQL database
	•	HTML and CSS for structure and styling
	•	Bootstrap for responsive UI design
	•	JavaScript for interactive components

⸻

Installation Instructions
	1.	Download and extract the project ZIP file.
	2.	Copy the folder named bbdms to your web server root directory:
	•	XAMPP: xampp/htdocs
	•	WAMP: wamp/www
	•	LAMP: /var/www/html
	3.	Open your browser and navigate to http://localhost/phpmyadmin
	4.	Create a new database with the name bbdms
	5.	Import the SQL script bbdms.sql located inside the project’s SQL folder.
	6.	Open your browser and run the project at: http://localhost/bbdms

⸻

Admin Credentials
	•	Username: admin
	•	Password: Test@123

⸻

Donor Credentials
	•	Username: amitk@gmail.com
	•	Password: Test@123
	•	Alternatively, users can register a new account from the front-end.

⸻

Project Modules

Admin Module includes:
	•	Dashboard with quick metrics
	•	Blood group management
	•	Full control over donor list (view, hide, delete)
	•	Contact query management
	•	Page content management
	•	Website contact info settings
	•	Viewing requests received by donors
	•	Admin profile and password management

User/Donor Module includes:
	•	Home, About Us, and Contact Us pages
	•	Full donor directory with contact access
	•	Donor search by city and blood group
	•	“My Account” section with:
	•	Profile update
	•	Change/recover password
	•	View requests received
	•	Logout

⸻

License

This project is created for academic and learning purposes only. Commercial use is not permitted without prior permission.
