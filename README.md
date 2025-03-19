## Cybersecurity Risk Assessment Report

## Overview
Cybersecurity risk assessment is the process of identifying, evaluating, and prioritizing potential threats and vulnerabilities that could compromise the confidentiality, integrity, and availability of information systems.
## Key Components of Cybersecurity Risk Assessment:
1.	Asset Identification: Identify and prioritize assets critical to the organization, including hardware, software, data, and personnel.
2.	Threat Identification: Identify potential threats that could exploit vulnerabilities and impact the security of assets.
3.	Vulnerability Assessment: Assess weaknesses and vulnerabilities in systems, applications, and processes that could be exploited by threats.
4.	Risk Analysis: Evaluate the likelihood and impact of identified risks to determine their overall risk level.
5.	Risk Mitigation: Develop strategies to mitigate or control identified risks, including implementing security controls and best practices.


## Threat Identification:
Sample Network/ System Setup:
The provided system is a small business network with a web server, database server, and multiple client workstations. The web server hosts a customer portal and the database server stores sensitive customer information.


## Identify Threats and vulnerabilities:
# Threats:
1.	Malware: potential for malware infections due to web server exposure.
2.	Unauthorized Access: Weaknesses in authentication may lead to unauthorized access.
3.	DDOS Attacks: The web server is susceptible to Distributed Denial of Service attacks.
# Vulnerabilities:
1.	Outdated Software: The web server software may not be up to date.
2.	Weak Passwords: Workstations might have weak passwords, increasing the risk of unauthorized access.


## Tools for Cybersecurity Risk Assessment:

# **Nmap**
1.	Conducted a network scan to identify active hosts and open ports.
2.	Identified the IP addresses of the web server, database server, and workstations.
Ping Scan: The simplest way to check active hosts and open ports is by a ping scan.

![Picture1](https://github.com/user-attachments/assets/6f5391e5-d825-42cd-a67f-51f46db25e48)

![Picture2](https://github.com/user-attachments/assets/bb3f6873-602a-4170-9d21-dbb43c4fcce2)

Service and version detection: To identify services running on open ports and their versions.

![Picture3](https://github.com/user-attachments/assets/cbe0c1bc-19b3-456c-86f6-d71344f915fc)

## **Nessus**
1.	Performed a vulnerability scan on each identified host.
2.	Discovered vulnerabilities such as outdated software versions and weak configurations.
An effective tool for vulnerability scanning and assessments, Nessus identifies security issues in systems and applications.
# Scan targets IP:
![Picture5](https://github.com/user-attachments/assets/4b924f27-c611-4288-85e3-9d2047f35715)

# Network scan 
![Picture6](https://github.com/user-attachments/assets/b10d9362-1ecd-4195-8066-3c9b5a8b79aa)

# Scan Vulnerabilities
![Picture7](https://github.com/user-attachments/assets/a877a6e3-7817-4218-85b9-b7aecca3229a)

# Vulnerabilities scan finds high risk
![Picture8](https://github.com/user-attachments/assets/6ecf85fc-c404-4822-a8a9-c107c0587b3d)

![Picture9](https://github.com/user-attachments/assets/bf648a6d-f95f-452c-8d9a-3a530bdf2b5f)

![Picture10](https://github.com/user-attachments/assets/1947cc02-678b-4562-8974-a4ea786de828)

## **Wireshark**
Useful for network protocol analysis and troubleshooting, Wireshark helps examine and analyze network traffic for potential security issues.
1.	Analyzed network traffic to identify any abnormal patterns or potential security issues.

![Picture11](https://github.com/user-attachments/assets/01318c8b-ee0f-4c3b-bfb2-c5c3fe97852c)

![Picture12](https://github.com/user-attachments/assets/91f35ece-7039-4034-97ca-08f7215d00b5)

![Picture13](https://github.com/user-attachments/assets/cadd9037-2f63-402b-b57a-b4aec2406819)


### 5. Risk Analysis and Mitigation
- Evaluates the likelihood and impact of risks.
- Develops mitigation strategies, such as security patches, stronger authentication, and network monitoring.

## Conclusion:
The cybersecurity risk assessment conducted as part of this internship has provided valuable insights into the security posture of the organization’s digital infrastructure. Through a systematic approach, including threat identification, vulnerability scanning, risk analysis, and mitigation strategies, critical security risks have been identified and addressed.
Overall, this cybersecurity risk assessment internship has provided valuable hands-on experience and insights into the complexities of cybersecurity. As cybersecurity threats continue to evolve, the knowledge and skills gained during this internship will serve as a solid foundation for future endeavors in the field.

## Repository Structure
```
├── README.md            # Project documentation
├── Cybersecurity_Risk_Assessment_Report.pdf  # Full assessment report
└── Tools_Results/       # Output from Nmap, Nessus, and Wireshark
```

## Author
Md Abu Rayhan  
Cybersecurity Engineer | Bug Bounty Hunter | Security Researcher

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For questions or contributions, feel free to reach out:
- LinkedIn: [[LinkedIn Profile]](https://www.linkedin.com/in/abu76/)
- Email: cybertechsecrets@gmail.com
- YouTube: [[YouTube Channel]](https://www.youtube.com/@CyberTechSecrets)
