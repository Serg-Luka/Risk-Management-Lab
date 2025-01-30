# Risk Management Lab - Conducting a Security Audit and Risk Assessment Reporting

## Objective

The goal of the Risk Management Lab project is to address potential risks and prevent security incidents for a fictional company, Botium Toys. This project includes carrying out key activities such as security audits and risk assessments, which play a vital role in strengthening the company’s resilience, ensuring regulatory compliance, and improving overall security awareness in today’s ever-changing digital landscape. Security audits ensure that vulnerabilities, threats, or risks are effectively identified and mitigated to safeguard business continuity and critical assets. As part of the risk assessment, I’m reviewing the security controls and regulatory adherence of Botium Toys, aiming to boost its overall security framework. This hands-on experience is designed to deepen my understanding of security auditing, risk assessment, and defence-in-depth strategies.

### Skills Learned

- Performing a full security audit and risk assessment to evaluate an organisation's current security health.
- Evaluating security practices and controls like separation of duties, least privilege access, and intrusion detection systems (IDS).
- Understanding and applying compliance frameworks such as PCI DSS, GDPR, and SOC 1/SOC 2 to ensure the organisation aligns with industry standards.
- Developing and documenting effective security policies, procedures, and processes to protect sensitive information and strengthen organisational resilience.
- Leveraging frameworks to guide the structure of security audits.

## Scenario

_The following scenario involves a fictional company:_

Botium Toys is a small business based in the U.S. that manufactures and sells toys. It operates from a single physical location, which serves as its main office, storefront, and product warehouse. However, with an expanding online presence, Botium Toys has seen an influx of both U.S. and international customers. This rapid growth has placed increasing pressure on their IT department to support their global online marketplace.

The IT manager has realised that an internal IT audit is necessary to ensure that the company’s infrastructure is secure, compliant with regulations, and able to support business continuity as the company grows. The manager also wants to address concerns regarding online payment processing and data privacy regulations, especially in the European Union (E.U.).

To tackle this, the IT manager decides to implement a cybersecurity framework as a foundation. This will help set the scope and goals for the audit, identify assets managed by the IT department, and complete a comprehensive risk assessment. The audit's objective is to identify potential risks, assess fines or penalties the company might face, and improve the company's overall security posture.

As part of the project, I’m tasked with reviewing the IT manager’s scope, audit goals, and risk assessment report. Afterward, I’ll perform an internal audit and use a checklist to assess controls and compliance.

## Botium Toys: Scope, Goals, and Risk Assessment Report

### Scope and Goals of the Audit

**Scope:** This audit covers the entire security programme at Botium Toys, including all assets under the IT department's management. This will involve reviewing employee devices, internal networks, and systems to ensure security practices are up to par.

**Goals:** To assess the current assets and complete the controls and compliance checklist, identifying necessary actions to improve the company’s security posture.

### Current Assets

Assets managed by the IT department include:
- Office-based equipment for day-to-day operations
- Employee devices like desktops, laptops, smartphones, headsets, and more
- Storefront inventory available online and in-store, along with warehouse management
- Management of critical systems such as accounting, telecommunications, database security, ecommerce, and inventory systems
- Internet access
- Internal network infrastructure
- Data storage and retention
- Ongoing maintenance of legacy systems that need continuous monitoring

## Risk Assessment

### Risk Description

At the moment, asset management is inadequate, and the company doesn’t have sufficient controls in place. Moreover, Botium Toys may not be fully compliant with U.S. regulations or international standards, putting its critical assets at risk.

### Control Best Practices

The first phase of the cybersecurity framework—Identify—emphasises the importance of resource allocation for asset identification. Botium Toys will need to dedicate time and resources to accurately classify their assets and assess the potential business impact if these assets were compromised.

### Risk Score

On a scale of 1 to 10, I’d rate the current risk at 8, which is high due to inadequate controls and compliance gaps.

### Additional Comments

The potential consequences of asset loss are considered medium, given the lack of asset knowledge. However, there’s a high risk of financial penalties and exposure of sensitive information because the necessary compliance and security controls are not fully implemented. Key issues include:

- All employees have unrestricted access to sensitive data, including customer credit card and PII/SPII.
- Credit card information is not encrypted, putting confidentiality at risk.
- There are no controls related to least privilege access or separation of duties.
- Availability and integrity of systems are secured, but an intrusion detection system (IDS) is absent.
- Antivirus software is installed and actively monitored by the IT department.
- There’s no disaster recovery plan or critical data backups.
- A breach notification plan is in place for E.U. customers, and privacy procedures are well-documented and enforced.
- The password policy is too lenient and needs to be updated to meet current standards.
- No centralised password management system to enforce these policies.
- Legacy systems are monitored but lack a regular maintenance schedule.
- The physical office, storefront, and warehouse are secured with locks, CCTV, and fire prevention systems.

## My Security Audit

## Security Controls Checklist

Here’s my assessment of the critical security controls currently implemented at Botium Toys:

| Control                                   | Yes             | No              | Explanation                                   |
|-------------------------------------------|-----------------|-----------------|-----------------------------------------------|
| Separation of Duties                      |                 | 🗹              | Critical roles (e.g., CEO managing payroll) need separation to prevent fraud. |
| Password Policies                         |                 | 🗹              | The current policy doesn’t meet best practices, allowing easy access for attackers. |
| Least Privilege                           |                 | 🗹              | Employees have access to sensitive data that they don’t need for their job. |
| Intrusion Detection System (IDS)          |                 | 🗹              | No IDS is in place, leaving the network vulnerable to intrusions. |
| Antivirus Software                        | 🗹              |                 | Antivirus software is installed and monitored. |
| Data Recovery Plans                       |                 | 🗹              | No data recovery plans are in place, which could result in data loss. |
| Backups                                   |                 | 🗹              | There are no backups of critical data. |
| Password Management System                |                 | 🗹              | No password management system, which leads to inefficiencies. |
| Firewalls                                 | 🗹              |                 | Firewalls are configured and blocking unwanted traffic effectively. |
| Legacy Systems Monitoring                 |                 | 🗹              | Legacy systems lack a maintenance schedule and monitoring processes. |
| CCTV Surveillance                         | 🗹              |                 | CCTV is installed and operational. |
| Locks (Offices, Storefront, Warehouse)    | 🗹              |                 | Physical locations are secured with locks. |
| Fire Detection/Prevention Systems         | 🗹              |                 | Fire safety systems are in place and functional. |

## Compliance Checklist

Here’s my evaluation of Botium Toys’ adherence to regulatory standards:

### PCI DSS

| Best Practice                                                                 | Yes | No  | Explanation                                                                                           |
|-------------------------------------------------------------------------------|-----|-----|-------------------------------------------------------------------------------------------------------|
| Secure handling of credit card data.                                           |     | 🗹  | Credit card data isn’t encrypted, and all employees have access to sensitive information. |
| Data encryption procedures implemented.                                        |     | 🗹  | No encryption, compromising financial data security. |
| Restricted access to credit card information.                                |     | 🗹  | All employees have access to cardholder data. |
| Enforced password management policies.                                        |     | 🗹  | The password policy is outdated and doesn’t meet current standards. |

### GDPR

| Best Practice                                                                 | Yes | No  | Explanation                                                                                           |
|-------------------------------------------------------------------------------|-----|-----|-------------------------------------------------------------------------------------------------------|
| Proper classification and inventory of data.                                  |     | 🗹  | Assets are inventoried, but not properly classified. |
| Plan to notify E.U. customers within 72 hours of a breach.                     | 🗹  |     | A notification plan is in place. |
| Ensuring E.U. customer data is kept secure.                                    |     | 🗹  | Data is not encrypted, putting customer data at risk. |
| Enforcement of privacy policies.                                               | 🗹  |     | Privacy policies are in place and enforced. |

### SOC 1, SOC 2

| Best Practice                                                                 | Yes | No  | Explanation                                                                                           |
|-------------------------------------------------------------------------------|-----|-----|-------------------------------------------------------------------------------------------------------|
| Authorised access to data.                                                     |     | 🗹  | All employees can access internal data; access needs to be restricted. |
| Sensitive data is kept confidential.                                          |     | 🗹  | No encryption means sensitive data is not adequately protected. |
| User access policies established.                                              |     | 🗹  | Lack of controls for Least Privilege and Separation of Duties. |
| Ensuring data integrity.                                                       | 🗹  |     | Controls for data integrity are in place. |

## Recommendations for the IT Manager of Botium Toys

### 1. **Implement Separation of Duties**

**Current Situation:**  
There is a lack of separation between critical roles, such as the CEO managing payroll, which increases the risk of fraud or unauthorised access to sensitive systems.

**Recommendation:**  
To mitigate the risk of fraud and unauthorised access, it’s essential to divide responsibilities. Implement tools to enforce the separation of duties effectively.

---

### 2. **Strengthen Password Policies**

**Current Situation:**  
The company’s password policy is outdated and doesn’t meet current best practices. This leaves systems vulnerable to brute force attacks or unauthorised access.

**Recommendation:**  
Update the password policy to ensure compliance with modern security standards, such as requiring complex passwords and regular changes. Implement tools to enforce these policies across the organisation.

---

### 3. **Apply Least Privilege**

**Current Situation:**  
Employees currently have broader access to sensitive data than necessary for their roles, which increases the risk of data breaches or internal sabotage.

**Recommendation:**  
Adopt the principle of least privilege by restricting access to sensitive data based on role requirements. Tools should be used to enforce least privilege and manage permissions effectively.

---

### 4. **Install an Intrusion Detection System (IDS)**

**Current Situation:**  
There is no IDS in place to monitor network traffic, which makes it difficult to detect potential intrusions in real-time.

**Recommendation:**  
Implement an IDS solution to monitor network traffic and detect malicious activities or potential breaches. This will help identify and mitigate threats quickly.

---

### 5. **Develop Disaster Recovery Plans**

**Current Situation:**  
There is no formal disaster recovery plan in place to ensure business continuity in the event of a system failure or data loss.

**Recommendation:**  
Create and implement a disaster recovery plan to safeguard critical systems and data. Automate backup and recovery processes, ensuring minimal downtime during disruptions.

---

### 6. **Ensure Regular Data Backups**

**Current Situation:**  
Critical data is not being regularly backed up, which increases the risk of losing valuable business information in the event of a cyberattack or system failure.

**Recommendation:**  
Set up automated, regular backups of critical data. Ensure that backups are stored securely and are regularly tested to confirm data integrity.

---

### 7. **Use a Password Management System**

**Current Situation:**  
The lack of a centralised password management system makes it challenging to enforce strong password policies and handle credentials securely.

**Recommendation:**  
Adopt a password management solution to store and manage credentials securely. This will also help to enforce strong password practices.

---

### 8. **Monitor Legacy Systems Regularly**

**Current Situation:**  
Legacy systems are not monitored regularly, increasing the risk of vulnerabilities being left unaddressed.

**Recommendation:**  
Set up a regular maintenance and monitoring schedule for legacy systems. Use monitoring tools to ensure that these systems are up-to-date and vulnerabilities are mitigated in a timely manner.

---

### 9. **Review and Implement Encryption Practices**

**Current Situation:**  
Sensitive data, including credit card information and personal data, is not encrypted, leaving it vulnerable to interception or theft.

**Recommendation:**  
Ensure all sensitive data, including financial and personal information, is encrypted using strong encryption protocols. Implement tools for data encryption both at rest and in transit.

---

### Conclusion

Botium Toys is at risk of significant security breaches due to inadequate controls and non-compliance with critical regulations. Immediate action is required to address these gaps and improve security resilience. Following the recommendations above will help Botium Toys bolster its security posture, comply with regulatory standards and reduce potential threats and risks.
