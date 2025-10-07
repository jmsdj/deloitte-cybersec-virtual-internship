# Incident Report – Daikibo Industrials Cyber Breach

## Summary
On June 26, 2021, Deloitte identified suspicious activity on Daikibo Industrial’s status dashboard. Sensitive company data was leaked to the public, coinciding with a production halt in their assembly lines.

## Root Cause
- The breach originated from an **internal network IP (192.168.0.101)**.
- This rules out direct internet exposure.
- Likely causes include **compromised VPN credentials** or **internal user misuse**.

## Affected Systems
- Meiyo Machine
- Seiko Machine
- Shenzen Machine
- Berlin Machine

## Impact
- Disruption of Daikibo’s assembly line operations.
- Leakage of sensitive operational data to external sources.
- Increased risk of reputational and financial damage.

## Next Steps
1. Conduct full credential audit and enforce **multi-factor authentication (MFA)**.  
2. Isolate affected machines and perform forensic investigation.  
3. Rotate all passwords and tokens associated with the dashboard.  
4. Enhance monitoring to detect unusual internal IP activity.  
