# Log Analysis – Deloitte Cyber Virtual Internship

## Overview
The client, Daikibo Industrials, reported a possible breach of their status dashboard. I was tasked with reviewing the provided `web_requests.log` file to determine whether suspicious activity occurred during the reported timeframe.

## Findings
- The **IP address (192.168.0.101)** indicates an internal/private network address, not a public internet source.  
- The **timestamp** matches the period of the alleged attack.  
- The **request type (GET)** suggests data retrieval from the dashboard.  
- The **user ID** appears unusual and may be compromised or unauthorized.  

## Conclusion
The evidence suggests that the attacker **did not access the dashboard directly from the internet**. Instead, the activity likely originated from inside the network or through VPN access. 