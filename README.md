# Task-4_Setup-and-Use-a-Firewall-on-Windows
Introduction

This report outlines the process of setting up and using the Windows Defender Firewall, a built-in security feature in Windows operating systems. The firewall controls incoming and outgoing network traffic to protect the system from unauthorized access and cyber threats.
Firewall Setup on Windows
Access Windows Firewall by opening Settings, then navigate to Update & Security > Windows Security > Firewall & network protection.
Select the active network profile (Domain, Private, or Public).
Enable Microsoft Defender Firewall by toggling it on for the selected profile. This activation ensures protection based on the network environment.
Usage and Management
To allow trusted applications through the firewall, use the Allow an app through firewall option and select the appropriate applications and network access types.
or advanced configurations, open the Windows Defender Firewall with Advanced Security console by running wf.msc.
Create custom inbound or outbound rules based on programs, ports, protocols, or IP addresses to manage traffic more precisely.
These rules help specify which network communications are permitted or blocked, enhancing system security
Regularly review firewall rules to avoid accidentally blocking essential services or applications.
Monitor firewall logs to detect unusual or unauthorized access attempts.
Avoid disabling the firewall unless necessary, as it increases system vulnerability.
Conclusion Windows Defender Firewall serves as a vital component of network security on Windows systems. Proper setup and diligent management of firewall rules protect the system from unauthorized network access and potential threats. This report emphasizes the importance of using the firewall effectively to maintain robust security tailored to different network environments.
