# Manage-Security-Risks-Lab

## Objective

To showcase a comprehensive understanding of security programs by evaluating assets, internal networks, and systems, and assessing the effectiveness of implemented controls and compliance practices. This audit aims to enhance knowledge of security frameworks, risk management, and best practices in safeguarding organizational resources.


### Skills Learned

- Security Frameworks and Standards (NIST CSF, GDPR, PCI DSS)
- Risk Assessment
- Asset Management
- Audit and Reporting


## Control categories

Controls within cybersecurity are grouped into three main categories:

1. Administrative / Managerial controls
2. Technical controls
3. Physical / Operational controls
 
Administrative / Managerial controls address the human component of cybersecurity. These controls include policies and procedures that define how an organization manages data and clearly defines employee responsibilities, including their role in protecting the organization. While administrative controls are typically policy based, the enforcement of those policies may require the use of technical or physical controls. 

Technical controls consist of solutions such as firewalls, intrusion detection systems (IDS), intrusion prevention systems (IPS), antivirus (AV) products, encryption, etc. Technical controls can be used in a number of ways to meet organizational goals and objectives.

Physical / Operational controls include door locks, cabinet locks, surveillance cameras, badge readers, etc. They are used to limit physical access to physical assets by unauthorized personnel. 
Control types
Control types include, but are not limited to:	
Preventative
Corrective
Detective
Deterrent


These controls work together to provide defense in depth and protect assets. Preventative controls are designed to prevent an incident from occurring in the first place. Corrective controls are used to restore an asset after an incident. Detective controls are implemented to determine whether an incident has occurred or is in progress. Deterrent controls are designed to discourage attacks. 

In the following charts there are specific details about each type of control and its purpose.


### Administrative / Managerial Controls
| Control Name             | Control Type | Control Purpose                                                                 |
|--------------------------|--------------|---------------------------------------------------------------------------------|
| Least Privilege          | Preventative | Reduce risk and overall impact of malicious insider or compromised accounts     |
| Disaster recovery plans  | Corrective   | Provide business continuity                                                    |
| Password policies        | Preventative | Reduce likelihood of account compromise through brute force or dictionary attacks |
| Access control policies  | Preventative | Bolster confidentiality and integrity by defining which groups can access data |
| Account management       | Preventative | Manage account lifecycle, reduce attack surface, and limit impact from threats |
| Separation of duties     | Preventative | Reduce risk and overall impact of malicious insider or compromised accounts     |

### Technical Controls
| Control Name             | Control Type  | Control Purpose                                                                |
|--------------------------|---------------|--------------------------------------------------------------------------------|
| Firewall                 | Preventative  | Filter unwanted or malicious traffic from entering the network                 |
| IDS/IPS                  | Detective     | Detect and prevent anomalous traffic matching a signature or rule              |
| Encryption               | Deterrent     | Provide confidentiality to sensitive information                               |
| Backups                  | Corrective    | Restore/recover from an event                                                 |
| Password management      | Preventative  | Reduce password fatigue                                                       |
| Antivirus (AV) software  | Preventative  | Detect and quarantine known threats                                           |
| Manual monitoring        | Preventative  | Identify and manage threats or vulnerabilities in outdated systems            |

### Physical / Operational Controls
| Control Name             | Control Type             | Control Purpose                                                                |
|--------------------------|--------------------------|--------------------------------------------------------------------------------|
| Time-controlled safe     | Deterrent                | Reduce impact from physical threats                                           |
| Adequate lighting        | Deterrent                | Deter threats by limiting "hiding" places                                     |
| Closed-circuit television (CCTV) | Preventative/Detective | Reduce risk of events and inform on conditions after an event                 |
| Locking cabinets         | Preventative             | Prevent unauthorized access to network gear                                   |
| Signage (alarm provider) | Deterrent                | Deter threats by indicating a low likelihood of a successful attack           |
| Locks                    | Deterrent/Preventative   | Prevent unauthorized physical access                                          |
| Fire detection/prevention | Detective/Preventative   | Detect and prevent damage from fire   

## Scenario

Botium Toys: Scope, goals, and risk assessment report

### Scope: 
The scope of this audit is defined as the entire security program at Botium Toys. This includes their assets like employee equipment and devices, their internal network, and their systems. You will need to review the assets Botium Toys has and the controls and compliance practices they have in place.

### Goals: 
Assess existing assets and complete the controls and compliance checklist to determine which controls and compliance best practices that need to be implemented to  improve Botium Toys’ security posture.

### Current assets
Assets managed by the IT Department include: 
- On-premises equipment for in-office business needs
- Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
- Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse
- Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
- Internet access
- Internal network
- Data retention and storage
- Legacy system maintenance: end-of-life systems that require human monitoring
- Risk assessment
- Risk description

Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards. 
### Control best practices
The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.
### Risk score
On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of controls and adherence to compliance best practices.

### Additional comments
The potential impact from the loss of an asset is rated as medium, because the IT department does not know which assets would be at risk. The risk to assets or fines from governing bodies is high because Botium Toys does not have all of the necessary controls in place and is not fully adhering to best practices related to compliance regulations that keep critical data private/secure. 

- All Botium Toys employees have access to internally stored data and may be able to access cardholder data and customers’ PII/SPII.
- Encryption is not currently used to ensure confidentiality of customers’ credit card information that is accepted, processed, transmitted, and stored locally in the company’s internal database.
- Access controls pertaining to least privilege and separation of duties have not been implemented.
- The IT department has ensured availability and integrated controls to ensure data integrity.
- The IT department has a firewall that blocks traffic based on an appropriately defined set of security rules.
- Antivirus software is installed and monitored regularly by the IT department.
- The IT department has not installed an intrusion detection system (IDS).
- There are no disaster recovery plans currently in place, and the company does not have backups of critical data.
- The IT department has established a plan to notify E.U. customers within 72 hours if there is a security breach. Additionally, privacy policies, procedures, and processes have been developed and are enforced among IT department members/other employees, to properly document and maintain data.
- Although a password policy exists, its requirements are nominal and not in line with current minimum password complexity requirements (e.g., at least eight characters, a combination of letters and at least one number; special characters).
- There is no centralized password management system that enforces the password policy’s minimum requirements, which sometimes affects productivity when employees/vendors submit a ticket to the IT department to recover or reset a password.
- While legacy systems are monitored and maintained, there is no regular schedule in place for these tasks and intervention methods are unclear.
- The store’s physical location, which includes Botium Toys’ main offices, store front, and warehouse of products, has sufficient locks, up-to-date closed-circuit television (CCTV) surveillance, as well as functioning fire detection and prevention systems.

## Controls and compliance checklist

### Controls Assessment Checklist

| Control                                      | Yes | No  |
|----------------------------------------------|-----|------|
| Least Privilege                              | [  ] | [ X ]  |
| Disaster recovery plans                      | [  ] | [ X ]  |
| Password policies                            | [  ] | [ X ]  |
| Separation of duties                         | [  ] | [ X ]  |
| Firewall                                     | [ X ] | [  ]  |
| Intrusion detection system (IDS)             | [  ] | [ X ]  |
| Backups                                      | [  ] | [ X ]  |
| Antivirus software                           | [ X ] | [  ]  |
| Manual monitoring, maintenance, and intervention for legacy systems | [ X ] | [  ]  |
| Encryption                                   | [  ] | [ X ]  |
| Password management system                   | [  ] | [ X ]  |
| Locks (offices, storefront, warehouse)       | [ X ] | [  ]  |
| Closed-circuit television (CCTV) surveillance| [ X ] | [  ]  |
| Fire detection/prevention (fire alarm, sprinkler system, etc.) | [ X ] | [  ]  |

### Compliance Checklist

### PCI DSS
| Best Practice                                                    | Yes | No  |
|------------------------------------------------------------------|-----|------|
| Only authorized users have access to customers' credit card information. | [  ] | [ X ]  |
| Credit card information is stored, accepted, processed, and transmitted securely. | [  ] | [ X ]  |
| Data encryption procedures secure credit card transactions.     | [  ] | [ X ]  |
| Secure password management policies are adopted.                | [  ] | [ X ]  |

### GDPR
| Best Practice                                                    | Yes | No  |
|------------------------------------------------------------------|-----|------|
| E.U. customers' data is kept private/secure.                    | [ X ] | [ ]  |
| A plan is in place to notify customers within 72 hours of a breach. | [ X ] | [ ]  |
| Data is properly classified and inventoried.                    | [ X ] | [ ]  |
| Privacy policies are enforced to maintain data documentation.   | [ X ] | [ ]  |

### SOC (Type 1, Type 2)
| Best Practice                                                    | Yes | No  |
|------------------------------------------------------------------|-----|------|
| User access policies are established.                           | [ ] | [ X ]  |
| Sensitive data (PII/SPII) is kept confidential.                 | [ ] | [ X ]  |
| Data integrity ensures consistency, completeness, and accuracy. | [ X ] | [ ]  |
| Data is available to authorized individuals.                    | [ X ] | [ ]  |


## Recommendations

### Administrative Controls:

Implement least privilege and separation of duties to minimize insider threats.
Develop robust password policies and adopt a password management system to secure access.

### Disaster Recovery:

Establish a comprehensive disaster recovery plan to ensure business continuity.

### Technical Controls:

Deploy an intrusion detection system (IDS) to monitor network traffic.
Implement encryption for sensitive data, especially for payment and customer information.
Perform regular backups and ensure their integrity and recoverability.

### PCI DSS Compliance:

Restrict access to credit card data and enforce secure storage and transmission practices.

### GDPR Compliance:

Classify and inventory data to strengthen control over personal information.
Continue enforcing privacy policies and ensure compliance with breach notification timelines.

### SOC Compliance:

Define user access policies and ensure confidentiality of sensitive data.
