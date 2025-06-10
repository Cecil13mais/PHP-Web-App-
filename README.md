🌐 PHP Web App Deployed on CentOS in Google Cloud – Connected to Remote MySQL DB! 🚀
Successfully completed a full-stack deployment of a lightweight PHP web application on Google Cloud Platform (GCP) using a CentOS Stream 9 VM and a Cloud SQL (MySQL 8) instance.

📊 The app captures and displays client IP addresses in real time — showcasing live data from users hitting the web app.

🔧 Key Deployment Steps

Provisioned CentOS Stream 9 on GCP Compute Engine

Activated swap space to support package installations

Installed php, mysql, and php-mysqlnd via dnf

Connected to Cloud SQL using the MySQL CLI to configure DB and schema

Developed PHP scripts:

Logger.php – captures and inserts client IPs via $_SERVER['REMOTE_ADDR']

Viewer.php – fetches and displays records in a styled HTML table using PDO

Configured Apache HTTPD and adjusted SELinux to allow external web access

📸 Project Highlights

Real-time server-side logging of client IPs

Verified full data flow from browser ➡️ backend ➡️ database ➡️ frontend

Live Demo: http://34.133.138.61

Output: HTML table of client IPs and access timestamps

Screenshots available on LinkedIn

🧪 Tech Stack

OS: CentOS Stream 9

Web Server: Apache HTTPD

Backend: PHP (mysqli + PDO)

Database: Google Cloud SQL (MySQL 8)

Cloud: Google Cloud Compute Engine

💡 Key Skills Practiced
✅ Cloud-native deployment on GCP
✅ Linux system administration & Apache configuration
✅ SQL scripting and DB connectivity
✅ PHP scripting with security-focused PDO usage
✅ Full-stack debugging and production readiness

🏷️ Tags
#GCP #CentOS #PHP #MySQL #CloudDeployment #Linux #FullStack #SysAdmin #DevOps #CyberSecurity #GoogleCloud #Database #WebDevelopment
