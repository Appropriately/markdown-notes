<!---DOC:CIS Risk Assessment Method;Notes I made on the CIS RAM and RAM Express documents;Sean Lewis-->
# CIS Risk Assessment Method (RAM)

> TL;DR: CIS RAM is an information security risk assessment method to help implement CIS Controls.

[toc]

## CIS Controls

### Goals

The guidelines consist of 20 key actions, called critical security controls (CSC), that organizations should take to block or mitigate known attacks. The controls are designed so that primarily automated means can be used to implement, enforce and monitor them. The security controls give no-nonsense, actionable recommendations for cyber security, written in language that’s easily understood by IT personnel. Goals of the Consensus Audit Guidelines include to:

* Leverage cyber offense to inform cyber defense, focusing on high payoff areas,
* Ensure that security investments are focused to counter highest threats,
* Maximize use of automation to enforce security controls, thereby negating human errors, and
* Use consensus process to collect best ideas.

### Key Actions

#### Basic

* CSC 1: [Inventory of Authorized and Unauthorized Devices](https://www.cisecurity.org/controls/inventory-and-control-of-hardware-assets/)
* CSC 2: [Inventory of Authorized and Unauthorized Software](https://www.cisecurity.org/controls/inventory-and-control-of-software-assets)
* CSC 3: [Secure Configurations for Hardware and Software on Mobile Devices, Laptops, Workstations, and Servers](https://www.cisecurity.org/controls/secure-configuration-for-hardware-and-software-on-mobile-devices-laptops-workstations-and-servers)
* CSC 4: [Continuous Vulnerability Assessment and Remediation](https://www.cisecurity.org/controls/continuous-vulnerability-management/)
* CSC 5: [Controlled Use of Administrative Privileges](https://www.cisecurity.org/controls/controlled-use-of-administrative-privileges)
* CSC 6: [Maintenance, Monitoring, and Analysis of Audit Logs](https://www.cisecurity.org/controls/maintenance-monitoring-and-analysis-of-audit-logs)

#### Foundational

* CSC 7: [Email and Web Browser Protections](https://www.cisecurity.org/controls/email-and-web-browser-protections)
* CSC 8: [Malware Defenses](https://www.cisecurity.org/controls/malware-defenses)
* CSC 9: [Limitation and Control of Network Ports, Protocols, and Services](https://www.cisecurity.org/controls/limitation-and-control-of-network-ports-protocols-and-services)
* CSC 10: [Data Recovery Capability](https://www.cisecurity.org/controls/data-recovery-capability)
* CSC 11: [Secure Configurations for Network Devices such as Firewalls, Routers, and Switches](https://www.cisecurity.org/controls/secure-configuration-for-network-devices-such-as-firewalls-routers-and-switches)
* CSC 12: [Boundary Defense](https://www.cisecurity.org/controls/boundary-defense)
* CSC 13: [Data Protection](https://www.cisecurity.org/controls/data-protection)
* CSC 14: [Controlled Access Based on the Need to Know](https://www.cisecurity.org/controls/controlled-access-based-on-the-need-to-know)
* CSC 15: [Wireless Access Control](https://www.cisecurity.org/controls/wireless-access-control)
* CSC 16: [Account Monitoring and Control](https://www.cisecurity.org/controls/account-monitoring-and-control)

#### Organisational

* CSC 17: [Security Skills Assessment and Appropriate Training to Fill Gaps](https://www.cisecurity.org/controls/implement-a-security-awareness-and-training-program)
* CSC 18: [Application Software Security](https://www.cisecurity.org/controls/application-software-security)
* CSC 19: [Incident Response and Management](https://www.cisecurity.org/controls/incident-response-and-management)
* CSC 20: [Penetration Tests and Red Team Exercises](https://www.cisecurity.org/controls/penetration-tests-and-red-team-exercises)

### Further Reading

* https://www.cisecurity.org/controls/cis-controls-list/

## CIS RAM Express Edition

### Principles and Practices

## Gloassary

* __Appropriate:__ A condition in which risks to information assets will not foreseeably create harm that is greater than what the organization or interested parties can tolerate.
* __Asset Class:__ A group of information assets that are evaluated as one set based on their similarity. “Servers,” “end-user computers,” “network devices” are examples, as are “email servers,” “web servers” and “authentication servers.”
* __Attack Path:__ A series of activities and information assets within the lifecycle of a security incident.
* __Attack Path Model:__ A description of how a specific attack path may occur within an environment.
* __Burden:__ The negative impact that a safeguard may pose to the organization, or to others.
* __Business Owners:__ Personnel who own business processes, goods, or services that information technologies support. i.e. customer service managers, product managers, sales management.
* __Constituents:__ Individuals or organizations that may be benefit from effective security over information assets, or may be harmed if security fails.
* __Control:__ A documented method for protecting information assets using technical, physical, or procedural safeguards.
* __Control Objective:__ The intended outcome of a control.
* __Due Care:__ The amount of care that a reasonable person would take to prevent foreseeable harm to others.
* __Duty of Care:__ The responsibility to ensure that no harm comes to others while conducting activities, offering goods or services, or performing any acts that could foreseeably harm others.
* __Impact:__ The harm that may be suffered when a threat compromises an information asset.
* __Impact Score:__ The magnitude of impact that can be suffered. This is stated in plain language and is associated with numeric scales, usually from ‘1’ to ‘3’ or ‘1’ to ‘5’.
* __Impact Type:__ A category of impact that estimates the amount of harm that may come to a party or a purpose. The CIS RAM describes three impact types; Mission, Objectives, and Obligations.
* __Information Asset:__ Information or the systems, processes, people, and facilities that facilitate information handling.
* __Inherent Risk:__ The likelihood of an impact occurring when a threat compromises an unprotected asset.
* __Key Risk Indicator:__ Aggregations and trending analysis of measures that management may use to understand their risk status.
* __Likelihood:__ The degree to which a threat is expected to create an impact. May be stated in terms of frequency, foreseeability, or probability.
* __Measure:__ A repeatable, evidence-based indication that a safeguard achieves its control objective.
* __Observed Risk:__ The current risk as it appears to the risk assessor.
* __Probability:__ The product of statistical analysis that estimates the likelihood of an event.
* __Reasonable:__ A condition in which safeguards will not create a burden to the organization that is greater than the risk it is meant to protect against.
* __Residual Risk:__ The risk that remains after a safeguard is applied. This concept is not directly used by CIS RAM, but implies that risk is lowered when a safeguard is applied. Residual risk does not take into account potential negative impacts to the organization when safeguards are applied.
* __Risk:__ An estimation of the likelihood that a threat will create an undesirable impact. In terms of this method, risk may be expressed as the product of a likelihood and an impact.
* __Risk Analysis:__ The process of estimating the likelihood that an event will create an impact. The foreseeability of a threat, the expected effectiveness of safeguards, and an evaluated result are necessary components of risk analysis. Risk analysis may occur during a comprehensive risk assessment, or as part of other activities such as change management, vulnerability assessments, system development and acquisition, and policies exceptions.
* __Risk Assessment:__ A comprehensive project that evaluates the potential for harm to occur within a scope of information assets, controls, and threats.
* __Risk Evaluation__: The mathematical component of risk analysis that estimates the likelihood and impact of a risk, and compares it to acceptable risk.
* __Risk Management:__ A process for analyzing, mitigating, overseeing, and reducing risk.
* __Risk Treatment Option:__ The selection of a method for addressing risks. Organizations may choose to Accept, Reduce, Transfer, or Avoid risks.
* __Risk Treatment Plan:__ A comprehensive project plan for implementing risk treatment recommendations.
* __Risk Treatment Recommendations:__ A listing of safeguards or processes that may be implemented and operated to reduce the likelihood and/or impact of a risk.
* __Safeguard:__ Technologies, processes, and physical protections that prevent or detect threats against information assets. Safeguards are implementations of controls.
* __Safeguard Risk:__ The risk posed by recommended safeguards. An organization’s mission or objectives may be negatively impacted by a new security control. These impacts must be evaluated to understand their burden on the organization, and to determine whether the burden is
reasonable.
* __Security:__ An assurance that characteristics of information assets are protected. Confidentiality, Integrity, and Availability are common security characteristics. Other characteristics of information assets such as velocity, authenticity, and reliability may also be considered if these are valuable to the organization and its constituents.
* __Steward:__ Personnel who are responsible for the security and proper operations of information assets, (e.g. database administrator, records manager, or network engineer).
* __Threat:__ A potential or foreseeable event that could compromise the security of information assets.
* __Threat Model:__ A description of how a threat could compromise an information asset, given the current safeguards and vulnerabilities around the asset.
* __Vulnerability:__ A weakness that could permit a threat to compromise the security of information assets.

## Additional material

* Download CIS controls [here](https://learn.cisecurity.org/cis-controls-download)