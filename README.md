# HoneyPots

Time spent: 5 hours spent in total

> Objective: Set up a honeypot and scan for activity.

## Honeypots Deployed
Following the steps outlined by CodePath week 9, a Dionaea with HTTP Honeypot was deployed.

## Issues Encountered
The main hardships of the project came in troubleshooting the set up. For example, when the firewall was being created, it ran for several hours without completion. It was discovered, however, that the firewall had in fact been created, it just continued running on the terminal past completion. Additionally, in using the "Deploy" section of the mhn-admin, the command kept generating something with the wrong IP address. By replacing this with the IP address of mhn-admin the problem was eventually fixed.

## Summary of Attack Data
In just 3 hours of running, hundreds of attack were done on the honeypot. These attacks came from all over including countries such as Brazil, Japan, China, and Russia. They were all detected through packet capture on the honeypot, as seen in the image below.
![](attacks.report)

## Unresolved Questions
While I understand the point of the honeypot, I still have questions about the attacks we picked up. For example, are these real people that we are monitoring? Are there really that many people looking for attack points, or was it part of a simulation?

