# ELK-SIEM-Home-Lab-Setup
This repository provides a step-by-step guide for setting up a Security Information and Event Management (SIEM) lab using the Elastic Stack (Elasticsearch, Logstash, Kibana) on a Parrot OS virtual machine.
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
This project guides you through setting up an ELK SIEM lab on a Parrot OS VM. You'll learn how to install and configure Elastic Stack components, generate security events, and analyze them in the SIEM. By the end, you'll have a functional SIEM lab that you can use to practice and refine your cybersecurity skills.

Prerequisites
Before starting, make sure you have:

Virtualization Software: VirtualBox or VMware
Basic Linux Knowledge: Understanding of Linux commands and virtualization
Elastic Cloud Account: A free Elastic Cloud account for creating and managing your Elastic Stack deployment
Parrot OS ISO: A downloaded copy of Parrot OS Security Edition
Setup Guide
Task 1: Create an Elastic Account
Sign up for a free Elastic Cloud account.
Log in and start your 14-day free trial.
Create a deployment with Elasticsearch as the deployment type.
Configure the deployment and wait for it to complete.
Task 2: Set Up Parrot OS VM
Download Parrot OS Security Edition.
Create a new VM in VirtualBox or VMware.
Install Parrot OS on the VM.
Log in to the VM after installation.
Task 3: Install Elastic Agent
Log in to your Elastic SIEM instance.
Navigate to Integrations and select Elastic Defend.
Install the Elastic Agent on your Parrot OS VM.
Verify the installation using sudo systemctl status elastic-agent.service.
Task 4: Generate Security Events
Install Nmap on the Parrot OS VM.
Run Nmap scans to generate security events.
Verify that logs are being forwarded to the SIEM.
Task 5: Query Security Events in SIEM
Access the Logs tab in Elastic SIEM.
Use the search bar to filter and query logs.
Analyze the security events collected.
Task 6: Create Dashboards
Go to Dashboards in Elastic.
Create a new dashboard and add visualizations for security events.
Save and customize your dashboard to fit your needs.
Task 7: Set Up Alerts
Navigate to Alerts under Security in Elastic SIEM.
Create a custom alert rule for Nmap scans.
Define actions for the alert and enable it.
Next Steps
Generate more security events and analyze them in the SIEM.
Explore additional Elastic SIEM features for deeper insights.
Continuously refine your SIEM skills with more advanced configurations.
Connect With Me
I'm always open to connecting with fellow cybersecurity enthusiasts and professionals. If you have any questions, feedback, or just want to chat about cybersecurity, feel free to reach out to me!

LinkedIn: Your LinkedIn Profile
GitHub: Your GitHub Profile
Twitter: Your Twitter Handle
Email: Your Email Address
References
Elastic Cloud
Parrot OS
VirtualBox
License
This project is licensed under the MIT License. See the LICENSE file for details
