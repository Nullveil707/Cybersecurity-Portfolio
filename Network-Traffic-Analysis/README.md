# Network Traffic Analysis

## Project Overview

This project involved analyzing DNS and ICMP traffic captured using tcpdump to investigate why users could not access a website.

## Scenario Summary

Users reported receiving a "destination port unreachable" error when attempting to access a website. Network traffic analysis revealed repeated DNS requests over UDP and ICMP responses indicating that UDP port 53 was unreachable.

## Findings

- DNS requests were sent using UDP.
- The DNS server returned ICMP error messages.
- Port 53 was unreachable.
- DNS resolution failed, preventing users from accessing the website.

## Skills Demonstrated

- Network Traffic Analysis
- DNS Investigation
- ICMP Analysis
- Log Interpretation
- Incident Documentation

## Files

- Cybersecurity-Incident-Report.pdf
