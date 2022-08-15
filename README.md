
This repository contains the steps to deploy Ansible on an Ubuntu Instance (AWS EC2): 

1) Directory Structure
    a. configs - contain environment specific variable

    b. inventories - contains inventory file for each environment

    c. groups_vars - contains common variables across environments

    d. roles - This will have subfolders like java,tomcat

2) Web Server - this folder has files for the installation of Tomcat

     a. - files have what you need to copy to your destination servers

     b. - handlers are to start/stop the services

     c. - template files you could use

     d. - tasks have playbooks that will help you install the application
     
3) User - This folder helps with the setup of the initial user

4) main.yml contains the code to execute the playbook

5) How to Run the Playbook
