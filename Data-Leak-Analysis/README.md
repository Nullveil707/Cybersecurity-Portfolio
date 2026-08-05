# Data Leak Analysis

This project was completed as part of the Google Cybersecurity Certificate. The activity focused on reviewing a data leak caused by improper access sharing and identifying ways to improve least privilege controls.

In this scenario, internal business documents were accidentally shared with an external business partner. The issue happened because access to a folder of internal documents was shared too broadly and was not removed after it was no longer needed. As a result, confidential information was exposed outside the organization.

For this project, I reviewed the incident and connected it to the principle of least privilege. I also used NIST SP 800-53: AC-6 to identify control improvements that could help prevent similar incidents in the future.

The main recommendations were to restrict access to sensitive resources based on user roles and to automatically revoke access after a set period of time. These controls would reduce the chance of employees keeping access they no longer need or accidentally sharing confidential information.

This activity helped me understand how access control, least privilege, and regular permission reviews can help protect sensitive data and reduce the risk of data leaks.

## File

* `Data-Leak-Analysis.pdf`
