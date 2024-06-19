# SECURITY INCIDENT LAB

## Objective

The Security Incident Lab focused on addressing a Distributed Denial of Service (DDoS) attack incident within a multimedia company’s network environment. The incident disrupted network services for two hours, necessitating the blocking of incoming ICMP traffic and the restoration of critical services. Using the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF), my objective was to develop a comprehensive plan to enhance network security. This plan includes identifying security risks through regular audits, implementing protective measures, enhancing detection capabilities, responding effectively to incidents, and ensuring the recovery of affected systems. This project showcases my ability to apply cybersecurity best practices and contribute to ongoing security strategy improvements within organizations.

### Skills Learned

- Advanced understanding of firewall configuration and implementation of IP address verification.
- Proficient in conducting security audits of internal networks, systems, devices, and access privileges to identify vulnerabilities and gaps in security.
- Ability to respond to DDoS attack incidents, including immediate actions to mitigate the impact and restore critical network services.
- Enhanced knowledge of  IDS/IPS systems and use in enhancing security posture.
- Development of strategies for business continuity and recovery.


### Tools Used

- NIST CSF

### Supplementary Material

![image](https://github.com/aehumphrey/Security-Incident-Lab/assets/33531835/f8cbd3cc-b795-433d-906f-b4e11dd20973)

*Ref 1: Scenario Overview*

## Steps

### Step One 
Description: Summarize the incident.

| NIST CSF                                         | Description       |
|-----------------------------------------------|----------------------------|
| Summarize    | A security incident occurred when all network services stopped responding. After investigating, a distributed denial of service (DDoS) attack involving a flood of incoming ICMP packets was identified as the cause. a flood of incoming ICMP packets. The cybersecurity team blocked the attack and stopped non-critical network services in order to prioritize restoring critical network services.|



### Step Two

Description: <b>Identify</b> the type of attack and systems covered.

| NIST CSF                                         | Description       |
|-----------------------------------------------|----------------------------|
| Summarize    | A security incident occurred when all network services stopped responding. After investigating, a distributed denial of service (DDoS) attack involving a flood of incoming ICMP packets was identified as the cause. a flood of incoming ICMP packets. The cybersecurity team blocked the attack and stopped non-critical network services in order to prioritize restoring critical network services.|
| Identify | An ICMP flood attack overwhelmed the network servers, affecting the entire internal network. This impacted all critical network resources. |

### Step Three

Description: <b>Protect</b> asssets. Assess where the organization can improve.
| NIST CSF                                         | Description       |
|-----------------------------------------------|----------------------------|
| Summarize    | A security incident occurred when all network services stopped responding. After investigating, a distributed denial of service (DDoS) attack involving a flood of incoming ICMP packets was identified as the cause. a flood of incoming ICMP packets. The cybersecurity team blocked the attack and stopped non-critical network services in order to prioritize restoring critical network services.|
| Identify | An ICMP flood attack overwhelmed the network servers, affecting the entire internal network. This impacted all critical network resources. |
| Protect | Two tools have been implemented to filter ICMP traffic: 1) a new firewall rule limits the rate of incoming ICMP packets, and 2) a newly implemented IDS/IPS system filters ICMP traffic based on predefined rules of “suspicious” characteristics. |

### Step Four

Description: Determine how to <b>detect</b> similar incidents. 
| NIST CSF                                         | Description       |
|-----------------------------------------------|----------------------------|
| Summarize    | A security incident occurred when all network services stopped responding. After investigating, a distributed denial of service (DDoS) attack involving a flood of incoming ICMP packets was identified as the cause. a flood of incoming ICMP packets. The cybersecurity team blocked the attack and stopped non-critical network services in order to prioritize restoring critical network services.|
| Identify | An ICMP flood attack overwhelmed the network servers, affecting the entire internal network. This impacted all critical network resources. |
| Protect | Two tools have been implemented to filter ICMP traffic: 1) a new firewall rule limits the rate of incoming ICMP packets, and 2) a newly implemented IDS/IPS system filters ICMP traffic based on predefined rules of “suspicious” characteristics. |
| Detect | Source IP address verification has been configured on the firewall. This will check for spoofed IP addresses on incoming ICMP packets in order to detect abnormal traffic patterns and, in doing so, alert systems administrators to a potential ICMP flood attack before one occurs. |

### Step Five

Description: Create a <b>response</b> plan
| NIST CSF                                         | Description       |
|-----------------------------------------------|----------------------------|
| Summarize    | A security incident occurred when all network services stopped responding. After investigating, a distributed denial of service (DDoS) attack involving a flood of incoming ICMP packets was identified as the cause. a flood of incoming ICMP packets. The cybersecurity team blocked the attack and stopped non-critical network services in order to prioritize restoring critical network services.|
| Identify | An ICMP flood attack overwhelmed the network servers, affecting the entire internal network. This impacted all critical network resources. |
| Protect | Two tools have been implemented to filter ICMP traffic: 1) a new firewall rule limits the rate of incoming ICMP packets, and 2) a newly implemented IDS/IPS system filters ICMP traffic based on predefined rules of “suspicious” characteristics. |
| Detect | Source IP address verification has been configured on the firewall. This will check for spoofed IP addresses on incoming ICMP packets in order to detect abnormal traffic patterns and, in doing so, alert systems administrators to a potential ICMP flood attack before one occurs. |
| Respond | Text... ... ... |

### Step Six

Description: Help the organization <b>recover</b> from the incident
| NIST CSF                                         | Description       |
|-----------------------------------------------|----------------------------|
| Summarize    | A security incident occurred when all network services stopped responding. After investigating, a distributed denial of service (DDoS) attack involving a flood of incoming ICMP packets was identified as the cause. a flood of incoming ICMP packets. The cybersecurity team blocked the attack and stopped non-critical network services in order to prioritize restoring critical network services.|
| Identify | An ICMP flood attack overwhelmed the network servers, affecting the entire internal network. This impacted all critical network resources. |
| Protect | Two tools have been implemented to filter ICMP traffic: 1) a new firewall rule limits the rate of incoming ICMP packets, and 2) a newly implemented IDS/IPS system filters ICMP traffic based on predefined rules of “suspicious” characteristics. |
| Detect | Source IP address verification has been configured on the firewall. This will check for spoofed IP addresses on incoming ICMP packets in order to detect abnormal traffic patterns and, in doing so, alert systems administrators to a potential ICMP flood attack before one occurs. |
| Respond | Text... ... ... |
| Recover | Text... ... ...|





