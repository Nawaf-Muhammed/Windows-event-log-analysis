# Windows Event Log Analysis (Beginner)

This repository document is my beginner practice analyzing Windows Security Event Logs
using Windows Event Viewer.

## Tools Used
- Windows Event Viewer

## Event IDs Studied
- 4624: Successful logon
- 4625: Failed logon
- 4688: Process creation

## What I Observed
- Successful and failed login attempts are recorded in Security logs
- Programs executed on the system generate process creation events

## SOC Perspective
Repeated failed logins may indicate brute-force activity
and should be monitored by a SOC analyst.

## Learning Outcomes
- Gained a basic understanding of Windows Security Event Logs and their role in SOC investigations.
- Learned to identify and analyze successful and failed login events.
- Practiced filtering logs and reviewing events to identify suspicious behavior.
- Improved understanding of how SOC analysts use logs to detect brute-force activity.

