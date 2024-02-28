# Botium Toys Audit
### Purpose
The purpose of this audit is provide mitigation recommendations for vulnerabilities found that are classified as “high risk,” and present an overall strategy for improving the security posture of the organization. The audit needs to align current business practices with industry standards and best practices.

### Scope
Botium Toys internal IT audit will assess the following:
- Current user permissions set in the following systems: accounting, end point detection, firewalls, intrusion detection system, security information and event management (SIEM) tool.
- Current implemented controls in the following systems: accounting, end point detection, firewalls, intrusion detection system, Security Information and Event Management (SIEM) tool.
- Current procedures and protocols set for the following systems: accounting, end point detection, firewall, intrusion detection system, Security Information and Event Management (SIEM) tool.
- Ensure current user permissions, controls, procedures, and protocols in place align with necessary compliance requirements.
- Ensure current technology is accounted for. Both hardware and system access.

### Goals
The goals for Botium Toys’ internal IT audit are:
- To adhere to the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF)
- Establish a better process for their systems to ensure they are compliant
- Fortify system controls
- Implement the concept of least permissions when it comes to user credential management
- Establish their policies and procedures, which includes their playbooks
- Ensure they are meeting compliance requirements

## Controls Assessment
### Current Assets
Assets managed by the IT Department include: 
- On-premises equipment for in-office business needs  
- Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
- Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
- Internet access
- Internal network
- Vendor access management
- Data center hosting services  
- Data retention and storage
- Badge readers
- Legacy system maintenance: end-of-life systems that require human monitoring 


### Controls
<div align="center"><b>Administrative Controls</b></div>
<br>

| Control Name               | Control Type and Explanation  | Needs to be Implemented (X) | Priority |
|----------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------|----------|
| Least Privilege            | Preventative; reduces risk by making sure vendors and non-authorized staff only have access to the assets/data they need to do their jobs                                                                                                                                      |           X         | High     |
| Disaster Recovery Plans    | Corrective; business continuity to ensure systems are able to run in the event of an incident/there is limited to no loss of productivity downtime/impact to system components, including: computer room environment (air conditioning, power supply, etc.); hardware (servers, employee equipment); connectivity (internal network, wireless); applications (email, electronic data); data and restoration | X                           | Medium   |
| Password Policies          | Preventative; establish password strength rules to improve security/reduce likelihood of account compromise through brute force or dictionary attack techniques                                                                                                                 | X                           | Medium   |
| Access Control Policies    | Preventative; increase confidentiality and integrity of data                                                                                                                                                                                                                    | X                           | Medium   |
| Account Management Policies | Preventative; reduce attack surface and limit overall impact from disgruntled/former employees                                                                                                                                                                                  | X                           | Medium   |
| Separation of Duties       | Preventative; ensure no one has so much access that they can abuse the system for personal gain                                                                                                                                                                                 | X                           | Low      |

<div align="center"><b>Technical Controls</b></div>
<br>

| Control Name                                 | Control Type and Explanation                                                                                   | Needs to be Implemented (X) | Priority |
|---------------------------------------------|----------------------------------------------------------------------------------------------------------------|-----------------------------|----------|
| Firewall                                    | Preventative; firewalls are already in place to filter unwanted/malicious traffic from entering internal network | X                          | High     |
| Intrusion Detection System (IDS)            | Detective; allows IT team to identify possible intrusions (e.g., anomalous traffic) quickly                     | X                           | High     |
| Encryption                                  | Deterrent; makes confidential information/data more secure (e.g., website payment transactions)                 | X                           | High     |
| Backups                                     | Corrective; supports ongoing productivity in the case of an event; aligns to the disaster recovery plan         | X                           | Low      |
| Password management system                  | Corrective; password recovery, reset, lock out notifications                                                    | X                           | Medium   |
| Antivirus (AV) software                     | Corrective; detect and quarantine known threats                                                                 | X                           | Medium   |
| Manual monitoring, maintenance, and intervention | Preventative/corrective; required for legacy systems to identify and mitigate potential threats, risks, and vulnerabilities | X          | Medium   |


<div align="center"><b>Physical Controls</b></div>
<br>

| Control Name                             | Control Type and Explanation                                                                                                       | Needs to be Implemented (X) | Priority |
|------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------|-----------------------------|----------|
| Time-controlled safe                     | Deterrent; reduce attack surface/impact of physical threats                                                                        | N/A                         |          |
| Adequate lighting                        | Deterrent; limit “hiding” places to deter threats                                                                                  | X                           | Low      |
| Closed-circuit television (CCTV) surveillance | Preventative/detective; can reduce risk of certain events; can be used after event for investigation                              | X                           | Low      |
| Locking cabinets (for network gear)      | Preventative; increase integrity by preventing unauthorized personnel/individuals from physically accessing/modifying network infrastructure gear | X | High |
| Signage indicating alarm service provider | Deterrent; makes the likelihood of a successful attack seem low                                                                   | N/A                         |          |
| Locks                                    | Preventative; physical and digital assets are more secure                                                                          | X                           | Medium   |
| Fire detection and prevention (fire alarm, sprinkler system, etc.) | Detective/Preventative; detect fire in the physical location to prevent damage to inventory, servers, etc.                       | X                           | Low      |

## Stakeholder Memorandum

TO: IT Manager, Stakeholders<br>
FROM: David Jones<br>
DATE: 22/07/2023<br>
SUBJECT: Internal IT Audit Findings and Recommendations

Dear Colleagues,

Please review the following information regarding the Botium Toys internal audit scope, goals, critical findings, summary and recommendations.

#### Scope:
- Current user permissions set in the following systems: accounting, end point detection, firewalls, intrusion detection system, security information and event management (SIEM) tool.
- Current implemented controls in the following systems: accounting, end point detection, firewalls, intrusion detection system, Security Information and Event Management (SIEM) tool.
- Current procedures and protocols set for the following systems: accounting, end point detection, firewall, intrusion detection system, Security Information and Event Management (SIEM) tool.
- Ensure current user permissions, controls, procedures, and protocols in place align with necessary compliance requirements.
- Ensure current technology is accounted for. Both hardware and system access.


#### Goals:
- To adhere to the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF)
- Establish a better process for their systems to ensure they are compliant
- Fortify system controls
- Implement the concept of least permissions when it comes to user credential Management
- Establish their policies and procedures, which includes their playbooks
- Ensure they are meeting compliance requirements


#### Critical findings (must be addressed immediately): 
The following controls are of high priority and must be implemented immediately:
- Least privilege
- Firewalls
- Intrusion detection systems
- Encryption
- Locking cabinets for network gear on site

#### Findings (should be addressed, but no immediate need): 
The following controls are of medium priority and should be implemented soon:
- Disaster recovery plans
- Password policies
- Access control policies
- Account Management policies
- Password management system
- Antivirus software
- Manual monitoring, maintenance, and intervention
- Locks

#### The following controls are of low priority and should be implemented when the business has capacity to do so:
- Separation of duties
- Backups
- Adequate lighting
- Closed circuit television surveillance
- Fire detection and prevention systems

#### Summary/Recommendations: 
The current state of security controls at the organisation is currently leaving the business open to risk of regulatory non-compliance, fines and reputational damage. Insufficient processes and controls could lead to a breach in security, loss of customer PII, SPII and intellectual property.

I strongly recommend to achieve the outlined goals above the immediate implementation of controls outlined above under <b>‘Critical Findings’</b> to ensure the safety of customer and company data, reducing risk to the current exposure.

Key regulations that the business needs to adhere to are:
- <b>GDPR</b>; due to the expanse of the business into the European market.
- <b>PCI-DSS</b>; due to the collection, processing and storage of customer payment information in person and online
- <b>SOC 1 & 2</b>; due to the implementation of information access controls, and the need to adhere to basic information security outlined under the CIA triad model.
