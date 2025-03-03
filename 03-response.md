# Security Best Practices Guide

## Internal Vulnerability Response Policies¹

Once you are able to receive secure reporting, project teams should create internal processes for handling the reported issues. Additionally, maintainers should codify the process for responding to reported incidents with a security impact on the project. 

Steps for triage and restitution of a reported security issue include:
- Assigning responsible team members for communicating with researchers and initiating the internal process to remediation;
- Acknowledging the report in a response and communicating about further processes and expected timelines to the researcher;
- Adding the reported vulnerability to any internal bug-tracking or ticketing system in order to establish documentation of each step;
- Triaging steps, which include impact analysis, reproducing and confirming issues, as well as the prioritization and communication of confirmation to the researcher;
- Planning remediation according to prioritization;
- Planning any needed outside communication to affected third parties (users, other projects, etc.); and 
- Performing the verification of the remediation or mitigation with the researcher.

Having a documented procedure for how your project responds to reported issues eliminates unnecessary labor on current and future maintainers, allows for open and clear communication with the person who disclosed, and promotes an outcome where both the vulnerability and the fix have a verified proof of concept. 

There can be circumstances where your project itself has not been exploited but is at risk after a vulnerability disclosure is published or shared with the maintainer team. We recommend introducing an internal process for handling security incidents, including but not limited to supply-chain attacks, malware campaigns that may target the project’s applications, infection or other attacks on the project’s development or production systems, and data breaches. Example checklists from government bodies can be found [here](https://www.cisa.gov/resources-tools/resources/cyber-incident-guide), [here](https://www.bsi.bund.de/EN/IT-Sicherheitsvorfall/Unternehmen/unternehmen.html?nn=916838&cms_pos=2), and [here](https://www.csa.gov.sg/Tips-Resource/Resources/singcert/incident-response-checklist). This internal process could require:

- Clarifying whether incidents (and what kind of incidents, more specifically) should be handled internally or by an external party;
- Reporting security incidents to users and related projects and companies; 
- Introducing a triage process (incident confirmation, impact and urgency review, and root cause analysis); and
- Reporting any security incidents in the country the project team operates in, if required by law.


|  |  |
| :---  | ---:  |
| [Back](./02-pipeline.md)  | [Next](04-follow.md)  |

*¹ This section topic and recommendations contributed by Least Authority*
