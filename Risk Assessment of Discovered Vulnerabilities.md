## Purpose
After a recent major breach of Social Media Co., 4 vulnerabilities have been discovered that require a risk assessment:
- The organisation’s employees' share passwords.
- The admin password for the database is set to the default.
- The firewalls do not have rules in place to filter traffic coming in and out of the network.
- Multi Factor authentication (MFA) is not used. 

The purpose of this security risk assessment is analyse the incident and explain what methods can be used to further secure the network.

## Associated Risks
The vulnerabilities raised as a result of the recent data breach highlight a number of areas that can be hardened by the business. The following table shows the current state of the highlighted vulnerability and the risks that can be associated with them:

|            Vulnerability                 |               Associated Risk            |
|-------------------------------------------|------------------------------------------|
|  The organisation’s employees' share passwords  |   Sharing passwords within an organization can lead to security breaches, unauthorized access to sensitive data, reduced accountability, compliance violations, and increased vulnerability to attacks, undermining the integrity and safety of the organization's systems and data.    |
|  The admin password for the database is set to the default  |   Attackers can easily gain authorization due to the public knowledge of default passwords, potentially leading to data breaches, system compromise, and regulatory non-compliance  |
|  The firewalls do not have rules in place to filter traffic coming in and out of the network  |  Without rules to filter traffic, firewalls cannot effectively prevent unauthorized access or data exfiltration, exposing the network to cyber threats, breaches, and potential data loss  |
|  Multi Factor authentication (MFA) is not used  |  The lack of MFA removes a critical layer of security, relying solely on passwords that can be easily stolen, guessed, or cracked, thus significantly simplifying unauthorized access  |

## Suggested Mitigations

Implementing the following security hardening tools will ultimately strengthen the organisation's security posture, reducing the risk of another breach:
- <b>Port filtering</b>; Configuring port filtering on firewalls will create rules that block or allow certain ports to limit unwanted communication to the network. This will reduce the potential for malicious traffic accessing the network and reduce risk.
- <b>Multi Factor authentication (MFA)</b>; Implementing MFA adds an additional layer of security preventing unauthorised access to the system. An example of which is sending a one time passcode (OTP) to the employee’s mobile phone to be used when logging in.
- <b>Password Policies</b>; Enforcing password policies will outline standards for the company that will ensure default credentials will change and stop users from sharing passwords.


