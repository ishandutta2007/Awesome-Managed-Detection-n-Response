# Awesome-Managed-Detection-n-Response

## Top Managed Detection & Response (MDR) Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on 24/7 Threat Detection, Incident Response, Threat Hunting, SOC-as-a-Service & Endpoint Visibility*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Managed Detection & Response (MDR)**. MDR combines technology (EDR/XDR, SIEM, telemetry) with human analysts who continuously monitor, hunt, investigate, and respond to threats on behalf of customers.



**Examples** include CrowdStrike Falcon Complete, Arctic Wolf, Red Canary, Expel, Huntress, ReliaQuest GreyMatter, eSentire, Secureworks Taegis, Sophos MDR, SentinelOne Vigilance, Rapid7 MDR, and related offerings (the category leaders).



**Open-source emphasis**: True MDR is a managed service, so there is no direct open-source “MDR product.” However, organizations can build internal detection-and-response capability using mature open tools such as **Wazuh**, **Security Onion**, **TheHive**, **Velociraptor**, **MISP**, and **OpenTelemetry**-based stacks. This section focuses on those building blocks and is realistic about the service gap.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[CrowdStrike Falcon Complete](https://www.crowdstrike.com/)**  

  Premium MDR service layered on the Falcon platform, providing 24/7 monitoring, detection, investigation, and response with high automation and response authority.



- **[Arctic Wolf](https://arcticwolf.com/)**  

  Concierge-style MDR with a named security team, continuous monitoring, and broad coverage across endpoints, networks, and cloud.



- **[Red Canary](https://redcanary.com/)**  

  Detection and response service known for high-quality detection engineering, transparency, and strong endpoint-focused MDR.



- **[Expel](https://www.expel.com/)**  

  MDR provider emphasizing transparency, multi-technology support, and clear investigation narratives for security teams.



- **[Huntress](https://www.huntress.com/)**  

  MDR and managed EDR oriented toward small and mid-sized businesses and the MSPs that serve them, with strong value positioning.



- **[ReliaQuest GreyMatter](https://www.reliaquest.com/)**  

  Security operations platform and MDR offerings that unify telemetry and enable detection, investigation, and response across tools.



- **[eSentire](https://www.esentire.com/)**  

  MDR and managed security services combining endpoint, network, and cloud detection with 24/7 SOC support.



- **[Secureworks Taegis / Taegis MDR](https://www.secureworks.com/)**  

  XDR platform and associated MDR services delivering detection, investigation, and response capabilities.



- **[Sophos MDR](https://www.sophos.com/)**  

  Managed detection and response service built on Sophos endpoint and security technologies, popular in mid-market environments.



- **[SentinelOne Vigilance](https://www.sentinelone.com/)**  

  MDR service layered on the SentinelOne Singularity platform for continuous monitoring and response.



- **[Rapid7 MDR](https://www.rapid7.com/)**  

  Managed detection and response offerings integrated with Rapid7’s Insight platform and vulnerability expertise.



- **[Additional ReliaQuest / GreyMatter MDR services](https://www.reliaquest.com/)**  

  Expanded MDR and security-operations services around the GreyMatter platform.



## Open-Source GitHub Projects

- **[Wazuh](https://github.com/wazuh/wazuh)**  

  Leading open-source XDR/SIEM platform providing endpoint detection, log analysis, file integrity monitoring, and compliance—commonly used as the core of self-managed detection stacks.



- **[Security Onion](https://github.com/Security-Onion-Solutions/securityonion)**  

  Free and open-source platform for threat hunting, network security monitoring, and log management that bundles many detection tools into a ready-to-deploy SOC foundation.



- **[TheHive](https://github.com/TheHive-Project/TheHive)**  

  Open-source Security Incident Response Platform (SIRP) for case management, collaboration, and investigation workflows.



- **[Cortex](https://github.com/TheHive-Project/Cortex)**  

  Open-source analysis engine that enriches observables and integrates with TheHive for automated investigation.



- **[Velociraptor](https://github.com/Velocidex/velociraptor)**  

  Advanced open-source endpoint visibility and digital forensics/incident response (DFIR) tool used for hunting and live response.



- **[MISP](https://github.com/MISP/MISP)**  

  Open-source threat intelligence platform for sharing, storing, and correlating Indicators of Compromise (IOCs).



- **[OpenCTI](https://github.com/OpenCTI-Platform/opencti)**  

  Open-source cyber threat intelligence platform focused on structured knowledge and relationship modeling.



- **[Falco](https://github.com/falcosecurity/falco)**  

  Cloud-native runtime security project for detecting anomalous behavior in containers and hosts.



- **[osquery](https://github.com/osquery/osquery)**  

  Open-source endpoint instrumentation framework that exposes operating-system data as a high-performance relational database.



- **[Shuffle / StackStorm and open SOAR tools](https://github.com/)**  

  Open-source security orchestration, automation, and response (SOAR) projects used to automate investigation and remediation playbooks.



### Additional Strong Open-Source Options

- Building an internal detection stack with **Wazuh + Security Onion + TheHive + MISP** for SIEM, NSM, case management, and threat intel.

- Using **Velociraptor** for powerful endpoint hunting and live response capabilities.

- Combining open EDR/XDR agents with commercial threat-intel feeds and (optionally) a commercial MDR service for 24/7 coverage.

- Accepting that true 24/7 analyst coverage, contractual response authority, advanced detection content, and SLAs remain the domain of commercial MDR providers (CrowdStrike Falcon Complete, Arctic Wolf, Red Canary, Expel, Huntress, etc.).

- Focusing open-source efforts on visibility, data ownership, and reducing reliance on any single vendor’s black-box detection.



**Frameworks for building custom systems**: Deploy endpoint and network sensors (Wazuh, Falco, osquery, Security Onion) → centralize telemetry → detect with open rules and threat intel (MISP/OpenCTI) → manage incidents in TheHive → automate with open SOAR → optionally escalate high-severity cases to a commercial MDR provider. Suitable for organizations with skilled security teams. Most mid-market and enterprise buyers still purchase MDR services for continuous coverage and expertise.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- MDR and detection tools handle sensitive security telemetry and may be subject to regulatory requirements. Building an internal SOC requires skilled people, processes, and continuous tuning—tools alone are not a complete MDR replacement. This list is not security, legal, or compliance advice.



---

**Made for security leaders, SOC managers, and teams evaluating detection & response options.**

Let's keep threat detection effective, transparent, and as open as practical.
