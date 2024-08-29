ELK SIEM Home-Lab Setup
Welcome to the ELK SIEM Home-Lab Setup project! This guide will walk you through setting up a Security Information and Event Management (SIEM) lab using the Elastic Stack (Elasticsearch, Logstash, Kibana) on a Parrot OS virtual machine. This is perfect for cybersecurity enthusiasts looking to gain hands-on experience with SIEM tools.

Table of Contents
Introduction
Prerequisites
Setup Guide
Task 1: Create an Elastic Account
Task 2: Set Up Parrot OS VM
Task 3: Install Elastic Agent
Task 4: Generate Security Events
Task 5: Query Security Events in SIEM
Task 6: Create Dashboards
Task 7: Set Up Alerts
Next Steps
Connect With Me
References
License
Introduction
Setting up an ELK SIEM (Elasticsearch, Logstash, Kibana) lab at home is a great way to understand how security information and event management works. In this project, you'll create a virtual environment to simulate and monitor security events, providing a practical understanding of SIEM.

Prerequisites
Before you begin, ensure you have the following:

Virtualization Software: VirtualBox or VMware
Basic Linux Knowledge: Familiarity with Linux commands and virtualization
Elastic Cloud Account: A free Elastic Cloud account to manage your Elastic Stack
Parrot OS ISO: Download Parrot OS Security Edition from the official site
Setup Guide
Task 1: Create an Elastic Account
Sign up for a free Elastic Cloud account.
Log in and start your 14-day free trial.
Create a deployment with Elasticsearch as the deployment type.
Configure the deployment settings and wait for it to complete.
Task 2: Set Up Parrot OS VM
Download the Parrot OS Security Edition ISO.
Create a new virtual machine in VirtualBox or VMware.
Install Parrot OS on the virtual machine.
Log in to the VM once the installation is complete.
Task 3: Install Elastic Agent
Log in to your Elastic SIEM instance.
Navigate to Integrations and select Elastic Defend.
Install the Elastic Agent on your Parrot OS VM.
Verify the installation by running sudo systemctl status elastic-agent.service.
Task 4: Generate Security Events
Install Nmap on the Parrot OS VM.
Run Nmap scans to generate security events.
Confirm that logs are being forwarded to the SIEM.
Task 5: Query Security Events in SIEM
Access the Logs tab in Elastic SIEM.
Use the search bar to filter and query logs.
Analyze the security events collected.
Task 6: Create Dashboards
Go to Dashboards in Elastic.
Create a new dashboard and add visualizations for your security events.
Save and customize your dashboard as needed.
Task 7: Set Up Alerts
Navigate to Alerts under Security in Elastic SIEM.
Create a custom alert rule for Nmap scans.
Define the actions for the alert and enable it.
Next Steps
Continue generating security events and analyzing them in your SIEM.
Explore more advanced features of Elastic SIEM.
Enhance your lab by integrating additional security tools.
Connect With Me
I'm always interested in connecting with others in the cybersecurity community. If you have questions, feedback, or just want to chat, feel free to reach out!

LinkedIn: Your LinkedIn Profile
GitHub: Your GitHub Profile
Email: your.email@example.com
References
Elastic Cloud
Parrot OS
VirtualBox
License
This project is licensed under the MIT License. See the LICENSE file for more details.
