---
title: "Uncovering Secret Threats: 10 Essential Steps to Conducting a Successful Threat Hunt!"
ShowToc: true 
date: "2022-11-29"
author: "Melanie Crane"
---
*****
# Uncovering Secret Threats: 10 Essential Steps to Conducting a Successful Threat Hunt!

In today's world, where cyber threats loom large and security breaches can cripple even the most robust organizations, proactive threat hunting has become more crucial than ever. With threat actors becoming increasingly sophisticated in their tactics, techniques, and procedures, it's no longer enough to rely solely on cybersecurity defenses like firewalls and anti-virus software to keep your organization safe.

To stay ahead of the curve, it's essential to conduct regular threat hunts - proactive searches for hidden threats that could be lurking in your organization's network. But how do you go about conducting a successful threat hunt? Here are ten essential steps to get started:

## Step 1: Determine Your Objectives

Before embarking on your hunt, it's essential to define your objectives: What do you want to achieve? What threats are you looking for? What assets are most critical to your organization? Answering these questions upfront will help you narrow down your search, prioritize your efforts, and measure your success.

## Step 2: Assemble Your Team

Effective threat hunting requires a multidisciplinary team comprising individuals with diverse skill sets, including threat intelligence, network security, endpoint security, and incident response. Your team should work together seamlessly, sharing insights and expertise to identify, investigate, and neutralize threats.

## Step 3: Choose Your Tools

A variety of tools and technologies can help you conduct a successful threat hunt. These include threat intelligence platforms, security information and event management (SIEM) systems, endpoint detection and response (EDR) solutions, and network traffic analysis tools. Choose the right tools for your objectives and make sure they work together seamlessly.

## Step 4: Collect Raw Data

To uncover hidden threats, you need to collect and analyze vast amounts of data from across your network and endpoints. This includes network traffic logs, system logs, firewall logs, security event logs, and endpoint telemetry data. Ensure that you're collecting the right data, at the right time, and in the right format.

## Step 5: Analyze the Data

Once you've collected your raw data, it's time to start analyzing it. Use threat intelligence feeds and other tools to identify patterns, anomalies, and other suspicious behavior. Make sure you're looking at data from different sources and at different granularities to get a complete picture.

## Step 6: Identify Threat Scenarios

As you analyze your data, start building threat scenarios based on what you've observed. These scenarios should describe how an attacker could exploit vulnerabilities and move laterally throughout your network. Use these scenarios to focus your hunt and tailor your investigation.

## Step 7: Investigate the Threats

Armed with your threat scenarios, it's time to start investigating. Use your EDR and other tools to collect more data, perform memory forensics, and isolate suspicious endpoints or network segments. Make sure you're documenting your findings and sharing them with your team.

## Step 8: Contain and Neutralize the Threat

Once you've identified a threat, it's time to contain and neutralize it. This includes isolating infected endpoints, blocking malicious domains and IP addresses, and removing malware from systems. Ensure that you're following established incident response procedures to minimize collateral damage.

## Step 9: Learn from Your Experience

Threat hunting is an iterative process, and every hunt should contribute to your organization's collective knowledge. After each hunt, take the time to debrief your team and identify areas for improvement. Use this knowledge to refine your objectives, processes, and tools.

## Step 10: Proactively Protect Your Environment

Finally, use the knowledge gained from your threat hunts to proactively protect your environment. Use your threat intelligence and other insights to adjust your security controls, identify gaps in your defenses, and prioritize security investments. Remember that threat hunting is an ongoing process, and you must remain vigilant to stay ahead of evolving threats.

In conclusion, threat hunting is an essential part of proactive cybersecurity. By following these ten essential steps, you can conduct successful hunts and protect your organization from hidden threats.

{{< youtube JBaGT83KBRI >}} 



Adversaries try their level best to perform reconnaissance with hopes of penetrating corporate networks and exploiting systems without detection. In response, organizations require a proactive and iterative threat-hunting program that should be ranked highly for precision and sophistication. In this article, we will explore ten steps covering how to conduct such an effective and reliable threat-hunting campaign.


 
## 1. Decide Whether to Choose In-House or Outsourced


When your company decides to conduct a threat-hunting program, it has two options — either in-house or outsourced. In-house threat hunting involves threat hunters from within the organization without hiring the services of a third-party or outsourcer. In this situation, the company should possess a sufficient talent pool to conduct a threat hunt itself. For example, your own threat-hunting team should have the ability to deal with Advanced Persistent Threats (APTs) carried out by adversaries.
On the other hand, if your company doesn’t have enough security staff and resources to conduct a threat hunt, then it will look towards outsourcing the threat-hunting program. In fact, outsourcing is the agreement whereby one organization hires another organization to get its specific tasks or projects done. In the case of threat hunting, one company will hire threat hunters from another company on an ad-hoc basis. These outsourced threat hunters will remain associated with the company until a threat-hunting program is completed successfully.

 
## 2. Start With Proper Planning


Whether you start threat hunting in-house or outsourced, the best threat-hunting campaign begins with proper planning. You must plan which processes will be executed to conduct your threat-hunting program. These processes are designed to discern not only what you have, but also the data sources that are misconfigured or missing. You cannot secure what you do not know exists!

 
## 3. Establish and Test Hypothesis


Next, analysts must develop a hypothesis by identifying the results they expect from the hunting campaign. For example, if they are conducting a hunt against fileless malware, the hunt’s aim is to find adversaries who are launching attacks by employing tools such as WMI and PowerShell.
A fileless malware or fileless infection is malicious coding that exists only in memory rather than on the hard drive of the targeted system. It is written directly to Random Access Memory (RAM). Attackers use attacking tools such as PowerShell to carry out this fileless malware. PowerShell and WMI include powerful scripting language that delivers deep access into a system’s inner core, including unrestricted access to the Windows APIs.
Testing every PowerShell process can be a time-consuming, frustrating and daunting task. Therefore, analysts should make smart choices and collect only that information which provides meaningful outcomes. The analysts should develop a wise approach to test the hypothesis without reviewing every event.

 
## 4. Gather Data


Data gathering is a vital process that involves the collection, normalization, and analysis of critical data. However, identifying what should be logged can be a Gordian knot. The easiest and most reliable way to formulate your own logging strategy is to follow already-existing standards, including NIST and OWASP. Collecting all types of logs is not a prudent approach, as it is a time-consuming process that further creates annoying and pesky noise.
The following logs are recommended to collect for your threat hunting campaign.

 

Network infrastructure logs (e.g., load balancer, firewall, router, VPN)
Host-based logs (e.g., endpoint detection response, operating systems)
Virtual machine hypervisor
Antivirus
Host/network IPS/IDS
Host-based logs
Database application and transaction
Application firewall
Domain Name Service (DNS)
Active Directory/LDAP
Proxy
Application and Web server
DHCP
Service logs
Configuration Management Database (CMDB)



Data should also be collected from some other internal sources, including past incidents, threats to your employees’ intellectual property, threats to your particular line of business and industry verticals, and reconnaissance attempts in the face of your infrastructure. External sources may include paid intelligence feeds, a partnership with government agencies and Open-Source Intelligence (OSINT).
Data retention is the essential component of any logging policy. Data retention determines the quantity and the validity of data for a certain span of time.

 
## 5. Organize Data


Once the data is collected and compiled properly, hunters need to identify which hunting tools they are going to utilize for organizing and analyzing this information. For this to be done effectively, various tools are available, including reporting tools in Security Information and Event Management (SIEM), buying analytical tools or employing Excel to sort data or create pivot tables. After that, this organized data can provide meaningful results to the analysts.

 
## 6. Automate Your Routine Tasks


Some security analysts consider automation inappropriate for the hunt. According to Anton Chuvakin, a Gartner research vice president, threat hunting is and ought to be human analyst-centric, not tool-centric. He believes that the hunt needs manpower to pursue threats proactively. Unlike automation through machines, manpower has the capability to anticipate an adversary’s move or potential attacks. Nevertheless, we cannot underestimate the importance of automation in threat hunting. By using automation tools to automate some repetitive or routine tasks, we can free up valuable analyst time for more pressing duties.
In some circumstances, the organization does not have enough analysts to proactively hunt down advanced threats. But what if it could teach machines to hunt? In this case, we would use human analysts to fine-tune and train automation processes. Automation tools can be programmed to look for an anomalous event and check whether that event involves the Indicators of Compromise (IoC) or Indicators of Threats (IoT).
Automation mainly addresses three challenges, including:

 

Automate Data Enrichment: An automation tool can assist with enriching data by performing root-cause analysis and automatically clustering similar events together
Automate Factor Identification: Machine learning has the ability to identify factors that bear analysis, either through discovery performed by the automation tool or through clear labeling provided by analysts
Automate Event Analysis: A good automation tool can quickly analyze millions or billions of events

 
## 7. Containing and Responding to Cybersecurity Threats and Vulnerabilities


At this point, analysts should now have enough data to answer their hypothesis. With the information in hand, there are two types of possibilities: either the vulnerability is found, or the actual threat is detected. In either case, the analysts will have to take an immediate action.
If the vulnerability is found, the analysts should resolve it. On the other hand, if the actual threat is identified, then the incident response team should contain a threat and perform the remediation process. However, the third possibility may exist that neither vulnerability nor threat is found. In this scenario, no action is needed, as a security posture is not compromised.

 
## 8.   Final Action


At this crucial stage, threat hunters define their course of action. For example, what resources are available to contain detected threats or vulnerabilities? How much time is required to eliminate a threat altogether and prevent it from becoming a nightmare? This process usually involves remediation, which puts the responsibility on the incident response team. Most often, threat hunters cede their responsibility in the remediation phase.

 
## 9. Documenting and Reporting to Stakeholders


Documentation of any detected vulnerabilities or threats is also a crucial part of the threat-hunting campaign. As soon as you get to conclusions, you will need to communicate to stakeholders, such as information security management, about the result of the process. Prepare a clear document informing stakeholders of the risk level criteria employed for the assessment, including the crucial factors employed for the threat assessment. At the same time, try to perform documentation on all the identified IoCs and sources.
Documented data will retain all the results drawn from the previous threat-hunting efforts. This data can be helpful to trace the history of attacks and verify whether the current attack is repeating or a new one.

 
## 10. Learned Lessons: A Continuous Improvement Cycle


It is rightly said that “anticipation is better than realization.” From a threat-hunting perspective, it’s better to anticipate threats than to realize and react to them once your antivirus program or SIEM raises an alert. Being proactive requires threat hunters to understand the entire IT infrastructure, including systems, applications and networks. To this end, threat hunters must obtain proper training from a reliable institution.

Now that the intrusion has been neutralized, identify the porous areas that threat actors capitalized on to penetrate the network. Learn how similar types of weaknesses and vulnerabilities could be prevented in the short or long term.

 
## Conclusion


It’s plain to see that threat hunting involves complex methods that can certainly help in detecting and responding to the cyberattacks. Though there is no globally accepted standard for threat hunting, companies have devised their own plans and strategies to conduct a threat hunting. In this article, you have learned the most common techniques that organizations use to conduct threat hunting program proactively and iteratively.
 

 
### Sources
 

Logging Cheat Sheet, OWASP
Guide to Computer Security Log Management, NIST
How to automate threat hunting, CSO
The Hunter’s Handbook, Endgame
Is threat hunting the next step for modern SOCs?, SearchSecurity
Huntpedia: Your Threat Hunting Knowledge Compendium, Sqrrl
What you need to know about PowerShell attacks, Cybereason




