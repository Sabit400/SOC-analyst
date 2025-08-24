# SOC-analyst
The responsibilities for a Junior Security Analyst or Tier 1 SOC Analyst include:

Monitor and investigate the alerts (most of the time, it's a 24x7 SOC operations environment)
Configure and manage the security tools
Develop and implement basic IDS (Intrusion Detection System) signatures
Participate in SOC working groups, meetings
Create tickets and escalate the security incidents to the Tier 2 and Team Lead if needed
Required qualifications (most common):

0-2 years of experience with Security Operations
Basic understanding of Networking ( OSI model (Open Systems Interconnection Model) or  TCP/IP model (Transmission Control Protocol/Internet Protocol Model)), Operating Systems (Windows, Linux), Web applications.
To further learn about OSI and TCP/IP models, please refer to the Introductory Networking Room.
Scripting/programming skills are a plus
Desired certification:

**CompTIA Security+ **
As you progress and advance your skills as a Junior Security Analyst, you will eventually move up to Tier 2 and Tier 3.

An overview of the Security Operations Center (SOC) Three-Tier Model:

SOC Analyst Three-Tier Model.
https://tryhackme-images.s3.amazonaws.com/user-uploads/5fc2847e1bbebc03aa89fbf2/room-content/7bf731bb9c58b0e9172a4788b761ad37.png<img width="1279" height="656" alt="image" src="https://github.com/user-attachments/assets/a64cfb69-1e12-4855-8671-d45021ef9386" />
The core function of a SOC (Security Operations Center) is to investigate, monitor, prevent, and respond to threats in the cyber realm 24/7 or around the clock. Per Trellix's definition of a SOC,  "Security operations teams are charged with monitoring and protecting many assets. These include intellectual property, personnel data, business systems, and brand integrity". As the implementation component of an organisation's overall cyber security framework, security operations teams act as the central point of collaboration in coordinated efforts to monitor, assess, and defend against cyberattacks". The number of people working in the SOC can vary depending on the organisation's size.
https://tryhackme-images.s3.amazonaws.com/user-uploads/5fc2847e1bbebc03aa89fbf2/room-content/e2b97e6d9224da98764e21085190e54e.png<img width="879" height="801" alt="image" src="https://github.com/user-attachments/assets/0ab73a06-5cc9-47cf-9f36-91d457005946" />
Preparation and Prevention

As a Junior Security Analyst, you should stay informed of the current cyber security threats (Twitter and Feedly can be great resources to keep up with the news related to Cybersecurity). It's crucial to detect and hunt threats, work on a security roadmap to protect the organisation, and be ready for the worst-case scenario.

Prevention methods include gathering intelligence data on the latest threats, threat actors, and their TTPs (Tactics, Techniques, and Procedures). It also includes the maintenance procedures like updating the firewall signatures, patching the vulnerabilities in the existing systems, block-listing and safe-listing applications, email addresses, and IPs. 

To better understand the TTPs, you should look into one of the CISA's (Cybersecurity & Infrastructure Security Agency) alerts on APT40 (Chinese Advanced Persistent Threat). Refer to the following link for more information, https://us-cert.cisa.gov/ncas/alerts/aa21-200a.

Monitoring and Investigation 

A SOC team proactively uses SIEM (Security information and event management) and EDR (Endpoint Detection and Response) tools to monitor suspicious and malicious network activities. Imagine being a firefighter and having a multi-alarm fire - one-alarm fires, two-alarm fires, three-alarm fires; the categories classify the seriousness of the fire, which is a threat in our case. As a Security Analyst, you will learn how to prioritise the alerts based on their level: Low, Medium, High, and Critical. Of course, it is an easy guess that you will need to start from the highest level (Critical) and work towards the bottom - Low-level alert. Having properly configured security monitoring tools in place will give you the best chance to mitigate the threat. 


Junior Security Analysts play a crucial role in the investigation procedure. They perform triaging on the ongoing alerts by exploring and understanding how a certain attack works and preventing bad things from happening if they can. During the investigation, it's important to raise the question "How? When, and why?". Security Analysts find the answers by drilling down on the data logs and alerts in combination with using open-source tools, which we will have a chance to explore later in this path.
https://www.cisa.gov/sites/default/files/publications/CSA_TTPs-of-Indicted-APT40-Actors-Associated-with-China-MSS-Hainan-State-Security-Department.pdf

End of this session there is a LAB that's amazing and answer THM{UNTIL-WE-MEET-AGAIN} .
