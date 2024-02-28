| Asset                        | Risk(s)                       | Description of vulnerability                                     | Likelihood | Severity | Priority |
|------------------------------|-------------------------------|-------------------------------------------------------------------|------------|----------|----------|
| Funds                        | Business email compromise     | An employee is tricked into sharing confidential information.     | 2          | 2        | 4        |
| Compromised user database    | Customer data is poorly encrypted. | Poor encryption of customer data.                              | 2          | 3        | 6        |
| Financial records leak       | A database server of backed up data is publicly accessible.      | 3          | 3        | 9        |
| Theft                        | The bank's safe is left unlocked.                                | 1          | 3        | 3        |
| Supply chain disruption      | Delivery delays due to natural disasters.                        | 1          | 1        | 1        |

**Notes:**
The immediate risk to the bank is that the backed up database server is publicly accessible; this is the priority to remediate due to the likelihood of unauthorized access and potential for threat actors to negatively affect the database. Due to the remote workforce and poor encryption, the next highest risk is the compromised user database; given the low level of encryption, this vulnerability could be exploited to leak PII & SPII.

Theft is a risk, however, due to the low crime rates of the area, physical risks are of a lower risk and priority than digital.

