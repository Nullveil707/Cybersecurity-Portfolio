# Website Compromise Investigation

## Project Overview

This project involved investigating a website compromise that resulted in visitors being redirected from a legitimate website to a malicious website containing malware.

## Scenario Summary

A former employee gained unauthorized access to the website's administrative account through a brute force attack. After accessing the admin panel, the attacker modified the website source code and embedded malicious JavaScript that prompted users to download an executable file. The file redirected users from the legitimate website to a malicious website.

## Key Findings

* Identified evidence of a brute force attack against the administrator account.
* Confirmed that the administrator password was still set to a default password.
* Detected unauthorized JavaScript code embedded in the website source code.
* Observed DNS and HTTP traffic associated with the malicious redirection.
* Verified that users were redirected from the legitimate website to a malicious website hosting malware.

## Protocols Analyzed

* DNS (Domain Name System)
* HTTP (Hypertext Transfer Protocol)

## Impact

* Unauthorized modification of website content.
* Malware distribution to website visitors.
* Loss of administrator account access.
* Increased security risk for customers and the organization.

## Recommended Remediation

Implement Multi-Factor Authentication (MFA) for administrative accounts to reduce the risk of unauthorized access, even if passwords are compromised.

## Skills Demonstrated

* Incident Investigation
* Network Traffic Analysis
* DNS Analysis
* HTTP Analysis
* Malware Investigation
* Security Documentation
* Risk Assessment

## Files

* Security-Incident-Report.pdf
