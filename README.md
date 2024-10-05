# Cyber-Threat-Management
Cyber-Threat Management is a framework that often used to manage the life cycle of a threat, helping me identify and respond to it with speed and accuracy. At its core, threat management relies on the seamless integration of people, processes, and technology to stay ahead of emerging threats (Pathak P, 2020). The process is continuous and involves several key stages: assessment, mitigation, insurance, detection, and remediation.

<img src="https://github.com/user-attachments/assets/02513bf8-7b39-49d0-814a-0997a6782d21" width ='600'>


In applying the threat management cycle, I focused on various domains such as System Security, Security Policy, Organizational Security, Asset Classification and Control, Personnel Security, Physical and Environmental Security, Communications and Operations Management, Access Control, Systems Development and Maintenance, Business Continuity Management, Compliance, or Financial Considerations. My discussions on threat management were always informed by specific threats or vulnerabilities within the Security Development Lifecycle, organization, or system.

To enhance threat management further, I designed my own Threat Model based on my understanding of the threat management cycle. I created attack trees to visually represent potential threat scenarios. For example, I developed an attack tree for "Unauthorized Access to a System" or "A Fraud Attack Tree." This approach allowed me to break down threats into more manageable components, assess risks, and develop strategies for mitigating those threats effectively. Download [Full Documentation here](./InformationSecurityAssignment.pdf)

#### Data Breach Attack Tree

I designed a Data Breach Attack Tree to illustrate various threat vectors leading to data breaches. The tree categorizes attacks into four main types: **External**, **Internal**, **Physical**, and **Social Engineering**. External attacks include phishing and exploiting software vulnerabilities, while internal attacks involve malicious insiders and accidental data exposure. Physical attacks focus on device theft or unauthorized facility access. Social engineering threats include tactics like scareware and pretexting. This model helps in visualizing the different ways data breaches can occur and the associated vulnerabilities to address.

<img src="https://github.com/user-attachments/assets/ff423ee9-584b-4f26-a7bf-4dd73c2303c1" width = '600'>

#### Threat Model: Protecting Patients medical records

I designed a Threat Model aimed at protecting patients' medical records in healthcare facilities, emphasizing the importance of maintaining integrity and confidentiality. The model includes a workstation zone where employees access sensitive information through multi-factor authentication to prevent unauthorized access. Additionally, I highlighted the need for regular system updates, endpoint protection with antivirus and antimalware, employee training on phishing and social engineering, and the encryption of devices containing sensitive data. 

In the cloud gateway zone, the model incorporates multiple cloud databases, such as  Microsoft Azure MySQL for employee credentials, Amazon RDS MariaDB for patient medical records, and Amazon QuickSight for data insights and reporting. To ensure robust security, I incorporated firewalls, specifically Firewall as a Service (FwaaS), to block suspicious network activity in the cloud without disrupting operations. Transport Layer Security (TLS) is employed for encrypted API communication, preventing unauthorized access during data transmission.

Additionally, the model emphasizes the critical need for data recovery or backup solutions to protect against data loss, cyber-attacks, and hardware failures. A Next Generation Firewall (NGFW) is implemented to safeguard backup data, with restricted access granted only to authorized personnel for better tracking and monitoring. Finally, security measures include fingerprint access and surveillance cameras to prevent device theft, enhancing the overall security posture of healthcare facilities. Overall, this comprehensive approach helps healthcare organizations safeguard against various cyber threats and maintain the confidentiality of patient information.

<img src="https://github.com/user-attachments/assets/e91ac979-24f7-4266-8bd2-94022425e3ff" width = '600'>


Download [Full Documentation here](./InformationSecurityAssignment.pdf)
