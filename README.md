# Network Incident Report Analysis

This repository contains a summary and analysis of a recent network incident that the company experienced, along with the response and mitigation strategies employed by the cybersecurity team. The incident was characterized by a disruption in network services caused by a distributed denial of service (DDoS) attack through a flood of incoming ICMP packets.

## Incident Summary

The incident report provides an overview of the security event, wherein all network services suddenly became unresponsive. The disruption was promptly attributed to a DDoS attack using a surge of ICMP packets. The response involved blocking the attack and temporarily stopping non-essential network services to facilitate the restoration of critical network resources.

## Incident Analysis

- **Identification:** The incident report outlines the identification of a malicious actor or actors who targeted the company with an ICMP flood attack, affecting the entire internal network. The report emphasizes the importance of securing and restoring critical network resources in such situations.

- **Protection:** The cybersecurity team's response involved implementing measures to protect against similar incidents in the future. This included the introduction of a new firewall rule to limit incoming ICMP packet rates and the setup of an Intrusion Detection System (IDS) and Intrusion Prevention System (IPS) to filter suspicious ICMP traffic.

- **Detection:** The incident report describes the implementation of source IP address verification on the firewall to prevent spoofed IP addresses on incoming ICMP packets. Additionally, network monitoring software was utilized to detect abnormal traffic patterns.

- **Response:** The report outlines the team's response strategy, which includes isolating affected systems to prevent further disruptions, restoring critical systems and services, analyzing network logs for suspicious activity, and reporting incidents to upper management and legal authorities when necessary.

- **Recovery:** In terms of recovery from a DDoS attack involving ICMP flooding, the report provides a recovery plan. This plan encompasses blocking external ICMP flood attacks at the firewall, temporarily pausing non-essential network services to reduce internal network traffic, prioritizing the restoration of critical network services, and bringing non-essential systems and services back online after the ICMP flood has subsided.

## Reflections/Notes

[Include any additional reflections or notes here, if applicable.]

This incident analysis and response report serves as a reference for understanding and addressing network security incidents and can be used as a valuable resource for incident response teams and cybersecurity professionals.

Feel free to explore the incident report analysis and use it as a guide for incident response and network security best practices.
