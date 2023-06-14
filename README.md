# Sprint-6-Anna-Francisco
Sprint 6 
# Efficient, Cost Effective, and Secure Design using AWS Cloud Resources and Services 

![Sprint 5](https://mti.com/wp-content/uploads/2020/06/blog-siem-image-03.jpg)

# Documentation: 
As a cybersecurity engineer, your role involves designing, developing, and implementing various measures to protect computer systems, networks, and data from unauthorized access, attacks, and vulnerabilities. Here's a detailed explanation of the design, development, and implementation process in cybersecurity:

1. Design Phase:
   
 a. Identify Requirements: Understand the organization's security goals, compliance regulations, and risk assessment to determine the necessary security measures. 
 
 b. Threat Modeling: Identify potential threats and vulnerabilities specific to the system or network being protected. Conduct a comprehensive analysis of potential attack vectors and their potential impact.
 c. Security Architecture: Design a robust security architecture that includes network segmentation, secure communication protocols, access controls, encryption, intrusion detection and prevention systems (IDPS), firewalls, and other security mechanisms.
 d. Security Policies: Develop security policies and procedures that outline acceptable use, incident response, access control, data classification, and other security guidelines specific to the organization.
 e. Collaboration: Coordinate with other stakeholders, such as system administrators, developers, and management, to ensure the security measures align with operational requirements and business objectives.
 
 2. Development Phase:
   
 a. Secure Coding Practices: Promote secure coding practices among software developers, emphasizing the use of libraries and frameworks with built-in security features, input validation, and protection against common vulnerabilities (e.g., SQL injection, cross-site scripting).
 b. Security Testing: Perform security testing, including vulnerability scanning, penetration testing, code review, and security assessment, to identify and address potential weaknesses and vulnerabilities.
 c. Secure Configuration: Configure systems, network devices, and software applications securely, following industry best practices and hardening guidelines provided by vendors.
 d. Encryption and Authentication: Implement robust encryption mechanisms (e.g., SSL/TLS) for data in transit and at rest. Utilize strong authentication methods, such as multi-factor authentication (MFA), to enhance access controls.
 e. Incident Response Planning: Develop an incident response plan to efficiently handle security incidents and mitigate their impact. Define roles, responsibilities, communication channels, and procedures for incident detection, containment, eradication, and recovery.

3. Implementation Phase:
   
 a. Network Security: Implement network security controls, such as firewalls, intrusion prevention systems (IPS), virtual private networks (VPNs), and secure Wi-Fi networks, to protect against unauthorized access, malware, and other threats.
 b. Access Control: Configure user access controls, including role-based access control (RBAC), privileged access management (PAM), and least privilege principles, to ensure only authorized individuals have access to critical systems and data.
 c. Security Monitoring: Deploy security monitoring tools and systems, including Security Information and Event Management (SIEM) solutions, log analyzers, and intrusion detection systems (IDS), to detect and respond to security incidents in real-time.
 d. Security Awareness Training: Conduct regular security awareness training sessions to educate employees about common security threats, best practices for data protection, phishing awareness, and social engineering techniques.
 e. Continuous Improvement: Regularly review and update security measures based on emerging threats, industry trends, and lessons learned from security incidents. Stay informed about the latest vulnerabilities and security patches.

Throughout the entire process, it is essential to document and maintain records of security measures, configurations, incident response activities, and any changes made to the systems. Additionally, ongoing monitoring, periodic audits, and risk assessments help ensure the effectiveness and adaptability of the implemented security controls.


To design an efficient, cost-effective, and secure solution using AWS cloud resources and services as a Cyber Security engineer

Identity and Access Management (IAM):
   - Utilize AWS Identity and Access Management (IAM) to manage user access and permissions. Apply the principle of least privilege, ensuring that users have only the necessary permissions to perform their tasks.
   - Enable multi-factor authentication (MFA) for all user accounts to add an extra layer of security.

Virtual Private Cloud (VPC):
   - Design a well-structured VPC architecture with public and private subnets.
Use network access control lists (ACLs) and security groups to control inbound and outbound traffic at the subnet and instance level.
Implement network segmentation to isolate sensitive systems and resources.
Secure Data Storage:
Utilize Amazon S3 for storing and securing data. Enable versioning, access control, and encryption at rest using AWS Key Management Service (KMS) for sensitive data.
Implement server-side encryption for data stored in Amazon S3 buckets.
Consider using Amazon Glacier for long-term archival storage of less frequently accessed data.
Encryption and Key Management:
Utilize AWS Key Management Service (KMS) for managing encryption keys.
Enable encryption at rest for all data stored in AWS services, including databases, S3, and EBS volumes.
Implement SSL/TLS certificates for secure communication between clients and services.
Logging and Monitoring:
Enable AWS CloudTrail to capture API activity and log files for auditing and compliance purposes.
Use Amazon CloudWatch for monitoring and alerting on system events, resource utilization, and security-related incidents.
Implement centralized logging by forwarding logs to services like Amazon CloudWatch Logs or a dedicated log management solution.
Security Testing and Vulnerability Management:
Regularly conduct vulnerability assessments and penetration testing to identify and remediate security weaknesses.
Utilize AWS services such as Amazon Inspector and AWS Security Hub to automate vulnerability assessments and monitor security compliance.
Implement a patch management strategy to keep all systems and software up to date.
Disaster Recovery and High Availability:
Design a disaster recovery plan that includes regular backups, off-site replication, and automated recovery procedures.





## Technical Documentation

[Step by step documentation](https://docs.google.com/document/d/1IvccqKaTwomLh-dwx_DB6I_jegXq9G-Y/edit#heading=h.gjdgxs)

## Presentation

[Software_Documentation/Powerpoint](https://docs.google.com/presentation/d/1HIGtFUXZXtAImRDnoDwXjvFat2nGWqwMEFrV3eIWatI/edit#slide=id.g4dfce81f19_0_45)

## AWS Cost
[AWS Cost](https://docs.google.com/document/d/1KC6UXP5oOpZBwpPOoJ6RnTnGg7duFGMMM3kzqdfUY5Y/edit)


## Agile Framework
[Jira ](https://drive.google.com/file/d/1Ki3C_C_G0apC7y3RJmJfZxOgo-k_pvSB/view?usp=sharing)



## Research Questions

[Research](https://docs.google.com/document/d/1q-4s0wYduzxw-lVYxSbrizw33M_LNwQY/edit)

## Team Members
- Anna [@annitamaria](https://github.com/orgs/cybertrainingrange/people/ANNITAMARIA)
- Francisco [@killbay](https://github.com/orgs/cybertrainingrange/people/killbay)


