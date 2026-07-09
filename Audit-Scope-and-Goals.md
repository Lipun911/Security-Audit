# Audit Scope and Goals

**Summary:** The internal audit needs to align current business practices with industry standards and best practices. The audit is meant to provide mitigation recommendations for vulnerabilities found that are classified as “high risk,” and present an overall strategy to improve the security posture of the organization. The audit team needs to document their findings, provide remediation plans and efforts, and communicate with stakeholders.

**Scope:** The internal IT audit will assess the following:
* Assess user permissions
* Identify existing controls, procedures, and system protocols
* Account for technology currently in use

**Goals:** The goals for the internal IT audit are:
* Adhere to the NIST Cybersecurity Framework (CSF)
* Establish policies and procedures to ensure compliance with regulations
* Fortify system controls

## Risk Assessment

**Current assets**
Assets managed by the IT Department include:
* Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
* Internal network: protected storage of customer, vendor, organizational data

**Risk description**
Currently, there is inadequate management of assets. Additionally, proper controls are not in place and the organization may not be compliant with U.S. and international compliance regulations and standards.

**Control best practices**
The organization will need to dedicate resources to managing assets. Additionally, they will need to determine the impact of the loss of existing assets, including systems, on business continuity.

**Risk score**
On a scale of 1-10, the risk score is 8, which is fairly high. This is due to a lack of controls and adherence to necessary compliance regulations and standards.

**Additional comments**
The likelihood of a lost asset or fines from governing bodies is high because the organization does not have all of the necessary controls in place and is not adhering to required regulations and standards related to keeping PII data private.

## Controls Assessment

| **Administrative Controls** | | |
| ------ | ------ | ------ |
| **Control name** | **Control type and explanation** | **Needs to be implemented (X)** | 
| Password policies | Preventative; establish password strength rules to reduce likelihood of account compromise | X |
| Least Privilege | Preventative; limits user access to reduce the risk of an internal breach | X |
| Separation of duties | Preventative; reduces the possibility of fraud and inappropriate access to critical data | X |
| Disaster recovery plans | Corrective; ensures business continuity after an incident | X |

| **Technical Controls** | | |
| ------ | ------ | ------ |
| **Control Name** | **Control type and explanation** | **Needs to be implemented (X)** | 
| Intrusion Detection System (IDS) | Detective; allows IT team to identify possible intrusions (i.e., anomalous traffic) quickly | X | 
| Encryption | Deterrent; makes confidential information/data more secure (i.e., website payment transactions) | X | 
| Backups | Corrective; allows the IT department to restore critical data in the event of a breach | X |
| Password management system | Preventative; improves productivity and limits credential exposure | X |
| Legacy system management | Preventative; regular scheduling and monitoring to intervene before a legacy system is breached | X |
| Firewall | Preventative; blocks traffic based on defined security rules | |
| Antivirus software | Corrective/Detective; software installed to detect and quarantine threats | |

| **Physical Controls** | | |
| ------ | ------ | ------ |
| **Control Name** | **Control type and explanation** | **Needs to be implemented (X)** |
| Closed-circuit television (CCTV) surveillance | Preventative/detective; can reduce risk of certain events; can be used after event for investigation | |
| Locks | Preventative; physical and digital assets are more secure | | 
| Fire detection/prevention | Detective/Preventative; detects fire and prevents damage to physical assets | | 

## Compliance Frameworks Addressed

* **General Data Protection Regulation (GDPR)**
GDPR is a European Union (EU) general data regulation that protects the processing of EU citizens’ data and their right to privacy in and out of EU territory. The organization needs to adhere to GDPR because we conduct business and collect personal information from people in the EU.
* **Payment Card Industry Data Security Standard (PCI DSS)**
PCI DSS is an international security standard meant to ensure that organizations storing, accepting, processing, and transmitting credit card information do so in a secure environment. The organization needs to adhere to PCI DSS because we process and transmit credit card information in person and online.
* **System and Organizations Controls (SOC type 1, SOC type 2)**
Ensures that user access policies are established, sensitive data (PII/SPII) is confidential, data integrity is validated, and data is only available to authorized individuals.