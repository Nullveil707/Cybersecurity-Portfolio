# Network Attack Analysis: TCP SYN Flood Attack Investigation

## Project Overview

This project involved analyzing network traffic to investigate a website outage affecting employees and customers of a travel agency. The goal was to identify the type of network attack responsible for the service interruption and explain its impact on the organization's web server.

## Scenario Summary

Users reported connection timeout errors when attempting to access the company website. Network traffic analysis revealed an unusually high volume of TCP SYN requests originating from a single external IP address.

## Key Findings

* Identified a TCP SYN Flood attack.
* The attack generated excessive TCP SYN packets directed at the web server.
* The server became overwhelmed while attempting to process connection requests.
* Legitimate users experienced connection failures and timeout errors.

## Technical Analysis

The attack exploited the TCP three-way handshake process by sending large numbers of SYN packets without completing the connection. This created numerous half-open connections that consumed server resources and prevented legitimate users from accessing the website.

Protocols involved:

* TCP
* HTTPS

## Impact

* Reduced website availability
* Connection timeout errors for users
* Degraded network performance
* Service disruption affecting business operations

## Recommended Mitigations

* Enable SYN flood protection
* Configure firewall rate limiting
* Implement Intrusion Detection and Prevention Systems (IDS/IPS)
* Use SYN cookies
* Deploy traffic filtering and DDoS protection services

## Skills Demonstrated

* Network Traffic Analysis
* TCP/IP Fundamentals
* Packet Inspection
* Threat Identification
* Incident Investigation
* Security Reporting
