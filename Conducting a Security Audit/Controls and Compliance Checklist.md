## Controls and Compliance Assessment

## Case Study: Botium Toys: Scope, goals, and risk assessment report

This scenario is based on a fictional company:

Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She's worried about maintaining compliance and business operations as the company grows without a clear plan. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

Your task is to review the IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist. 

## Scope 

This audit covers Botium Toys' security program, including employee devices, internal networks, systems, and compliance practices.

## Goals
Assess existing assets and complete the controls and compliance checklist to determine which controls and compliance best practices that need to be implemented
to improve Botium Toys’ security posture.

## Current assets
Assets managed by the IT Department include:
*  On-premises equipment for in-offce business needs
* Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
* Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse
* Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
* Internet access
* Internal network
* Data retention and storage
* Legacy system maintenance: end-of-life systems that require human monitoring

## Risk assessment

## Risk description

Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and
international regulations and standards.

## Control best practices

The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.

## Risk score

On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of controls and adherence to compliance best practices.

## Additional comments

The potential impact from the loss of an asset is rated as medium, because the IT department does not know which assets would be at risk. The risk to assets or fines
from governing bodies is high because Botium Toys does not have all of the necessary controls in place and is not fully adhering to best practices related to compliance
regulations that keep critical data private/secure. Review the following bullet points for specic details:
* Currently, all Botium Toys employees have access to internally stored data and may be able to access cardholder data and customers’ PII/SPII.
* Encryption is not currently used to ensure condentiality of customers’ credit card information that is accepted, processed, transmitted, and stored locally in the company’s internal database.
* Access controls pertaining to least privilege and separation of duties have not been implemented.
* The IT department has ensured availability and integrated controls to ensure data integrity.
* The IT department has a firewall that blocks traffic based on an appropriately defined set of security rules.
* Antivirus software is installed and monitored regularly by the IT department.
* The IT department has not installed an intrusion detection system (IDS).
* There are no disaster recovery plans currently in place, and the company does not have backups of critical data.
* The IT department has established a plan to notify E.U. customers within 72 hours if there is a security breach. Additionally, privacy policies, procedures, and processes have been developed and are enforced among IT department members/other employees, to properly document and maintain data.
* Although a password policy exists, its requirements are nominal and not in line with current minimum password complexity requirements (e.g., at least eight characters, a combination of letters and at least one number; special characters).
* There is no centralized password management system that enforces the password policy’s minimum requirements, which sometimes affects productivity when employees/vendors submit a ticket to the IT department to recover or reset a password.
* While legacy systems are monitored and maintained, there is no regular
schedule in place for these tasks and intervention methods are unclear.
* The store’s physical location, which includes Botium Toys’ main offices, storefront, and warehouse of products, has sufficient locks, up-to-date closed-circuit television (CCTV) surveillance, as well as functioning fire detection and prevention systems.

## Solution 

## Control categories

Controls within cybersecurity are grouped into three main categories:
* Administrative/Managerial controls
* Technical controls
* Physical/Operational controls

## Control types
Control types include, but are not limited to:
1. Preventative
2. Corrective
3. Detective
4. Deterrent

## Controls and compliance checklist

Does Botium Toys currently have this control in place?

| Yes/No | Control                       | Explanation                                                                 |
|--------|-------------------------------|-----------------------------------------------------------------------------|
| Yes    | Least Privilege               | Restrict user access to only the resources necessary for their role.        |
| No     | Disaster Recovery Plan        | A plan to restore operations in the event of a disaster is not in place.    |
| Yes    | Password Policies             | Strong password policies are enforced to secure accounts.                   |
| No     | Separation of Duties          | Critical functions are not divided among different individuals.             |
| Yes    | Firewall                      | Firewalls are used to block unauthorized access to the network.             |
| Yes    | Intrusion Detection System    | Monitors the network for suspicious activities or breaches.                 |
| No     | Backups                       | Regular data backups are not implemented.                                   |
| Yes    | Antivirus Software            | Protects systems from malware and other malicious software.                 |
| No     | Legacy System Maintenance     | Manual monitoring and maintenance for legacy systems are not conducted.     |
| Yes    | Encryption                    | Data is encrypted to ensure confidentiality and prevent unauthorized access.|
| YES    | Physical Security Measures    | The stores store’s physical location, which includes Botium Toys’ main offices, storefront, and warehouse of products, has suffcient locks, up-to-date closed-circuit television (CCTV) surveillance, as well as functioning fire detection and prevention systems.     |

## Recommendations
Based on this assessment, it is recommended to:
- Develop a disaster recovery plan.
- Implement separation of duties for critical operations.
- Regularly back up data to ensure recoverability.
- Enforce consistent physical security measures like locks and CCTV.
