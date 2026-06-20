Linux File Permissions Management

Project Overview

This project demonstrates the use of Linux commands to examine and modify file and directory permissions. The objective was to ensure that file permissions aligned with organizational security requirements by removing unauthorized access and restricting access to sensitive resources.

Skills Demonstrated
* Linux command line navigation
* File permission auditing
* Permission management using chmod
* Hidden file management
* Directory access control
* Principle of least privilege

Tasks Performed
1. Reviewed Existing Permissions
Used the following command to display detailed file and directory permissions:
ls -la

2. Modified File Permissions
Removed write access for others on project_k.txt:
chmod o-w project_k.txt

3. Updated Hidden File Permissions
Modified permissions on .project_x.txt to remove write access while maintaining appropriate read permissions:
chmod u-w,g+r,g-w .project_x.txt

4. Restricted Directory Access
Removed group execute permissions from the drafts directory:
chmod g-x drafts

Files Included
* Linux File Permissions Report
* Screenshot of initial permissions
* Screenshot of permission modifications

This project reinforced the importance of managing Linux file permissions to protect sensitive resources and enforce organizational security policies. Proper use of the chmod command helps ensure that users only have the level of access necessary to perform their responsibilities.
