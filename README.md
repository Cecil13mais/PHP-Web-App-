# PHP-Web-App-
🌐 PHP Web App Deployed on CentOS in Google Cloud – Connected to Remote MySQL DB! 🚀
Successfully completed a full-stack deployment of a lightweight PHP web application on Google Cloud Platform (GCP) using a CentOS Stream 9 VM and a Google Cloud SQL (MySQL 8) instance.

The app captures and displays client IP addresses in real time. 💻📊

🔧 Key Steps
Created and activated swap space to handle package installation
Installed required packages: php, mysql, and php-mysqlnd via dnf
Connected to Cloud SQL via MySQL CLI to create the project DB and audit table
Built a PHP script to log client IPs using $_SERVER['REMOTE_ADDR']
Developed a second PHP script using PDO to fetch and display records in a styled HTML table
Configured Apache HTTPD and disabled SELinux for external web access
📸 Project Highlights
Real-time server-side logging of client IPs
Verified data flow from browser to database and back
Dynamic, publicly accessible output at:
http://34.133.138.61
Output: HTML table showing IP addresses and timestamps
🔗 View screenshots on LinkedIn

🧪 Tech Stack
OS: CentOS Stream 9
Web Server: Apache HTTPD
Backend: PHP (mysqli + PDO)
Database: Google Cloud SQL (MySQL 8)
Cloud Platform: Google Cloud Compute Engine
💡 Why This Matters
This project reinforced key skills in:

🔹 Cloud-native deployment on GCP
🔹 Linux system administration
🔹 Database integration and SQL scripting
🔹 PHP development and PDO usage
🔹 Full-stack debugging and service configuration
🏷️ Tags
#GCP #CentOS #PHP #MySQL #CloudDeployment #Linux #FullStack #Sysadmin #DevOps #Cybersecurity #GoogleCloud #Database #WebDevelopment
