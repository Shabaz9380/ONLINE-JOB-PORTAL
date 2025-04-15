# ONLINE JOB PORTAL

## Overview

This project is a web-based online job portal designed to connect job seekers (candidates) with employers (recruiters). It provides a platform where candidates can create profiles, search for job openings, and apply for suitable positions. Simultaneously, recruiters can register their companies, post job vacancies, and manage applications received. The system also likely includes an administrative panel for overall platform management.

## Key Features

* **User Authentication:** Secure registration and login functionality for both candidates and recruiters.
* **Candidate Profiles:** Candidates can create and manage their profiles, including personal details, education, work experience, skills, and resume uploads.
* **Recruiter/Company Profiles:** Recruiters can register their companies and manage company profiles.
* **Job Posting:** Recruiters can easily post new job openings with detailed descriptions, required skills, salary information, location, and company details.
* **Advanced Job Search:** Candidates can search for jobs using various criteria such as keywords, location, job category, and salary range.
* **Job Application System:** Candidates can apply for jobs directly through the portal.
* **Application Management:** Recruiters can efficiently view, track, and manage the applications received for their posted jobs.
* **Administrative Panel:** A dedicated section for administrators to manage users, job postings, and potentially other platform settings.
* **Role-Based Access Control:** Distinct user roles (candidate, recruiter, admin) with tailored functionalities and access privileges.
* **Email Integration:** Likely includes email functionalities for user registration confirmations, application notifications, and other system-related communications.

## Technologies Used

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** PHP
* **Database:** MySQL
* **Email Handling:** PHPMailer library

## Project Structure

The repository is organized as follows:
ONLINE-JOB-PORTAL/
├── admin/             # Files for the administrative panel
├── applyjob/          # Scripts for handling job applications
├── candidate/         # Files related to candidate functionalities
├── company/           # Files related to recruiter/company functionalities
├── config/            # Configuration files (e.g., database connection)
├── css/               # CSS stylesheets for styling
├── images/            # Image assets
├── index.php          # Main entry point of the website
├── js/                # JavaScript files for client-side interactions
├── logout.php         # Script for user logout
├── phpmailer/         # PHPMailer library for email sending
├── searchjob/         # Scripts for job searching functionality
├── scss/              # SASS/SCSS files (may require compilation to CSS)
├── single_job.php     # Page to display details of a single job posting
└── ...                # Other project files


## Setup and Installation

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/Shabaz9380/ONLINE-JOB-PORTAL.git](https://github.com/Shabaz9380/ONLINE-JOB-PORTAL.git)
    cd ONLINE-JOB-PORTAL
    ```

2.  **Database Setup:**
    * Create a new database in your MySQL server.
    * Import the database schema (if provided in the repository, e.g., a `.sql` file) into your newly created database.
    * Update the database connection details in the `config/` directory (e.g., database host, username, password, database name) to match your MySQL setup.

3.  **PHP Configuration:**
    * Ensure you have a web server (e.g., Apache, Nginx) configured to run PHP.
    * Place the project files in your web server's document root or a configured virtual host directory.
    * Ensure that PHP has the necessary extensions enabled (e.g., MySQLi for database interaction, mail functions for email).

4.  **PHPMailer Configuration:**
    * Review the PHP files that use PHPMailer (likely in user registration and application processes). You might need to configure SMTP settings in these files if you intend to use an external SMTP server for email sending.

5.  **Access the Portal:**
    * Open your web browser and navigate to the URL where you have hosted the job portal (e.g., `http://localhost/ONLINE-JOB-PORTAL/`).

## Contributing

(If you are open to contributions, add guidelines here on how others can contribute to the project. This might include information on reporting issues, suggesting features, and submitting pull requests.)

## License

(Specify the license under which the project is distributed. For example, MIT License, GPL, etc.)

## Screenshots

(Optional: Add screenshots of the key pages of the job portal to provide a visual overview.)

## Further Development

(Optional: Mention any planned future features or areas for improvement.)

## Acknowledgements

(Optional: If you have used any external libraries, frameworks, or resources, you can acknowledge them here.)
