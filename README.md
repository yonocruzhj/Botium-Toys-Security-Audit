<h1>Botium Toys Security Audit</h1>

 ### 

<h2>Description</h2>
In this lab, we simulated a comprehensive security audit of Botium Toy's IT infrastructure to identify vulnerabilities, assess risk, and ensure compliance with security policies. We assessed current security measures and provided reccomendations to improve the organization's security posture.
<br />

<h2>Goals</h2>
The goal is to understand the process of auditing an organization’s security posture and to recommend remediation steps for identified issues.

<h2>Framework and Guidelines</h2>

- <b>NIST CSF</b> 

<h2>Security Audit Process:</h2>

<p align="center">
Scenario: <br/>
<img src="https://imgur.com/2N1vg2F.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

# Botium Toys: Controls and compliance checklist

**Controls assessment checklist**

|   Yes |     No | Control |
| ----- | ----- | :---- |
|  |[x]| Least Privilege |
|  |[x]| Disaster recovery plans |
|  |[x]| Password policies |
|  |[x]| Separation of duties |
|[x]|  | Firewall |
|  |[x]| Intrusion detection system (IDS) |
|  |[x]| Backups |
|[x] |  | Antivirus software |
|  |[x]| Manual monitoring, maintenance, and intervention for legacy systems |
|  |[x]| Encryption |
|  |[x]| Password management system |
|[x]|  | Locks (offices, storefront, warehouse) |
|[x]|  | Closed-circuit television (CCTV) surveillance |
|[x]|  | Fire detection/prevention (fire alarm, sprinkler system, etc.) |

---
**Compliance checklist**

Payment Card Industry Data Security Standard (PCI DSS)

| Yes |     No | Best practice |
| ----- | ----- | :---- |
|  |[x]| Only authorized users have access to customers’ credit card information.  |
|  |[x]| Credit card information is stored, accepted, processed, and transmitted internally, in a secure environment. |
|  |[x]| Implement data encryption procedures to better secure credit card transaction touchpoints and data.  |
|  |[x]| Adopt secure password management policies. |

General Data Protection Regulation (GDPR)

| Yes |     No | Best practice |
| ----- | ----- | :---- |
|   |[x]| E.U. customers’ data is kept private/secured. |
|[x]|  | There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach. |
|   |[x]| Ensure data is properly classified and inventoried. |
|[x]|  | Enforce privacy policies, procedures, and processes to properly document and maintain data. |

System and Organizations Controls (SOC type 1, SOC type 2\) 

| Yes |     No | Best practice |
| ----- | ----- | :---- |
|  |[x]| User access policies are established. |
|  |[x]| Sensitive data (PII/SPII) is confidential/private. |
|[x]|  | Data integrity ensures the data is consistent, complete, accurate, and has been validated. |
|  |[x]| Data is available to individuals authorized to access it. |

---

Recommendations to improve security posture include the following: 

* Separating duties for employees and having levels of access for each employee.  
* Create a disaster recovery plan.  
* Adhere to current password policies such as 8 character minimum, 1 number, and 1 special character.  
* Update passwords periodically   
* Create password management system  
* Install IDS   
* Back up data in an encrypted device.  
* Use encryption for customer SPII, PII, and data.  
* Train employees to properly classify data and add data to inventory.  
* Train employees to monitor legacy systems properly.  

<h2>Full Audit Report</h2>

- https://github.com/yonocruzhj/Botium-Toys-Security-Audit/blob/main/Botium%20Toys%20Audit%20Github.md
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
