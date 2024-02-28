## Introduction
The Asset being assessed is the funds of the bank. Below is a table of the risks, vulnerability description and scoring of the likelihood of the event, severity of the event and the priority of getting it resolved.

| Risk(s)                       | Description of vulnerability                                     | Likelihood | Severity | Priority |
|-------------------------------|-------------------------------------------------------------------|------------|----------|----------|
| Business email compromise     | An employee is tricked into sharing confidential information.     | 2          | 2        | 4        |
| Compromised user database    | Customer data is poorly encrypted.                                 | 2          | 3        | 6        |
| Financial records leak       | A database server of backed up data is publicly accessible.        | 3          | 3        | 9        |
| Theft                        | The bank's safe is left unlocked.                                  | 1          | 3        | 3        |
| Supply chain disruption      | Delivery delays due to natural disasters.                          | 1          | 1        | 1        |

**Notes:**
The immediate risk to the bank is that the backed up database server is publicly accessible; this is the priority to remediate due to the likelihood of unauthorized access and potential for threat actors to negatively affect the database. Due to the remote workforce and poor encryption, the next highest risk is the compromised user database; given the low level of encryption, this vulnerability could be exploited to leak PII & SPII.

Theft is a risk, however, due to the low crime rates of the area, physical risks are of a lower risk and priority than digital.

## Scoring breakdown

To formulate the priority scoring of the risks, I have mapped them to the risk matrix shown in image 1 below.  

![image](https://github.com/JustA-Byte/Risk-Lab/assets/161458321/82a5649f-1b7e-45e8-894a-5572bacc79f8)<br>
Ref: image 1

<b>Likelihood:</b> Score from 1-3 of the chances of a vulnerability being exploited. A 1 means there's a low likelihood, a 2 means there's a moderate likelihood, and a 3 means there's a high likelihood.<br>
<b>Severity:</b> Score from 1-3 of the potential damage the threat would cause to the business. A 1 means a low severity impact, a 2 is a moderate severity impact, and a 3 is a high severity impact.<br>
<b>Priority:</b> How quickly a risk should be addressed to avoid the potential incident. Use the following formula to calculate the overall score: Likelihood x Impact Severity = Risk
