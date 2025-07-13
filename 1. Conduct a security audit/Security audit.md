# Security frameworks and controls

This case aims to explore the common elements of internal security audits, as well as examine how companies use security frameworks and controls to protect their business operations. Both the company and the information presented are fictitious.

## Case Study

Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She's worried about maintaining compliance and business operations as the company grows without a clear plan. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

Your task is to review the IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist. 

## Scope and goals of the audit
The following information was extracted from Botium Toys' scope, objectives, and risk assessment report.

### Scope 

The scope covers the complete security program at Botium Toys. This includes evaluating all assets as well as reviewing internal processes and procedures connected to the application of controls and adherence to compliance best practices.

### Goals
Review the current assets and complete the controls and compliance checklist to identify which security controls and compliance best practices should be implemented to strengthen Botium Toys’ security posture.

### Current assets
Assets managed by the IT Department include: 
* On-premises equipment for in-office business needs.
* Employee equipment: End-user devices, remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
* Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse.
* Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management.
* Internet access.
* Internal network.
* Data retention and storage.
* Legacy system maintenance: End-of-life systems that require human monitoring.

### Risk assessment

#### Risk description
Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards. 

#### Control best practices
The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.

#### Risk score
On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of controls and adherence to compliance best practices.

#### Additional comments
The potential impact from the loss of an asset is rated as medium, because the IT department does not know which assets would be at risk. The risk to assets or fines from governing bodies is high because Botium Toys does not have all of the necessary controls in place and is not fully adhering to best practices related to compliance regulations that keep critical data private/secure. Review the following bullet points for specific details:

#### Additional Info 

In Cybersecurity, control types can be classified in three ways: 
1. Administrative/Managerial controls
2. Technical controls
3. Physical/Operational controls

Control types (providing defense and protecting assets) include, but are not limited to:
1. Preventative (preventing an incident from occurring in the first place)
2. Corrective (restoring an asset after an incident)
3. Detective (Determining whether an incident has occurred or is in progress)
4. Deterrent (Discouraging attacks)

## Controls Assessment Checklist

Does Botium Toys currenly have this control in place? 

| Y/N | Control | Description |
| :--------        |    :---:   | :---     |
| No | Least Privilige | Staff members are able to access customer's information. This must be modified to lower the likelihood of a data breach. |
| No | Disaster recovery plans | There are currently no disaster recovery strategies established. It is necessary to put these in place to guarantee the continuity of business operations. |
| No | Password policies | Even though a password policy exists, its standards are inadequate and could put identity management security at risk. |
| No | Separation of duties |It should be put in place to lower the risk of fraud or unauthorized access to sensitive information, as the CEO is currently responsible for daily operations and payroll management. |
| Yes | Firewall | The current firewall restricts network traffic according to a properly established set of security policies. |
| No | IDS | The IT team requires an IDS to detect potential unauthorized access by malicious actors. | 
| No | Backups | The IT team should maintain backups of essential information to guarantee that business operations can continue if a security breach occurs. |
| Yes | Antivirus software | The IT department routinely installs and oversees antivirus software. |
| No | Manual monitoring, maintenance, and intervention for legacy systems | The asset inventory mentions the presence of legacy systems. According to the risk assessment, these systems are being monitored and maintained; however, there is no established routine for these activities, and the guidelines or policies for intervention are not clearly defined. This lack of structure could make the systems vulnerable to security breaches. |
| No | Encryption | Encryption is not being used at the moment; putting it in place would offer better protection for confidential information. |
| No | Password management system | Currently, there is no password management system in use. Implementing one would enhance efficiency for the IT team and other staff members when handling password issues. |
| Yes | Locks | The store’s premises are equipped with adequate locks. |
| Yes | CCTV surveillance | Closed-circuit television (CCTV) is set up and operating at the store’s physical premises. |
| Yes | Fire detection/prevention | Botium Toy's physical location is equipped with an operational fire detection and prevention system. |

## Compliance Checklist
Does Botium Toys currently adhere to this compliance best practice? 

* Payment Card Industry Data Security Standard (PCI DSS)

| Y/N | Best Practice | Explanation |
| :---        |    :---:   | :---     |
| No | Only authorized users have access to customers’ credit card information. | Currently, every employee can access the organization’s internal information. |
| No | Credit card information is accepted, processed, transmitted, and stored internally, in a secure environment. | Credit card details are not protected by encryption, and all staff members presently have access to internal data, which includes customers’ credit card information. |
| No | Implement data encryption procedures to better secure credit card transaction touchpoints and data. | The company is currently not using encryption to improve the security of customers’ financial information. | 

* General Data Protection Regulation (GDPR)
  
| Y/N | Best Practice | Explanation |
| :---        |    :---:   | :---     |
| No | E.U. customers’ data is kept private/secured. | At this time, the company does not utilize encryption to enhance the protection of customers’ financial data. |
| Yes | There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach. | There is an intention to inform customers in the European Union about any data breach within 72 hours. |
| No | Ensure data is properly classified and inventoried. | The current assets have been recorded, but they have not been categorized. |
| Yes | Enforce privacy policies, procedures, and processes to properly document and maintain data. | Privacy guidelines, protocols, and workflows have been created and implemented for IT staff and other employees as necessary. |

* System and Organizations Controls (SOC type 1, SOC type 2)  

| Y/N  | Best Practice | Explanation |
| :---        |    :---:   | :---     |
| No | User access policies are established. | Staff members can access data stored within the organization, indicating that the access policy has not been enforced. |
| No | Sensitive data (PII/SPII) is confidential/private. | Encryption is not presently implemented to enhance the protection of PII/SPII confidentiality. |
| Yes | Data integrity ensures the data is consistent, complete, accurate, and has been validated. | Data integrity is correctly in place. | 
| No | Data is available to individuals authorized to access it. | Only those who need it for their job responsibilities should be allowed to use it. |

## Recommendations 

Several security measures should be put in place to strengthen Botium Toys’ security posture and better protect confidential information. These measures include:

1. Enforcing the principle of least privilege.
2. Developing disaster recovery plans.
3. Establishing strong password policies.
4. Ensuring separation of duties.
5. Deploying an intrusion detection system (IDS).
6. Setting up a regular schedule for monitoring and maintaining legacy systems, as well as procedures related to their intervention.
8. Using encryption.
9. Implementing a password management solution.

To close compliance gaps, Botium Toys must adopt controls such as least privilege, separation of duties, and encryption. Additionally, the company should accurately classify its assets to determine if further controls are necessary to enhance security and safeguard sensitive data.
