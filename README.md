## Zero-Trust-Resources ##

Resources and Tools for Zero Trust Security

## What is Zero Trust? ##

Zero Trust is a security model, a set of system design principles, and a coordinated cybersecurity and system
management strategy based on an acknowledgement that threats exist both inside and outside traditional network
boundaries. The Zero Trust security model eliminates implicit trust in any one element, node, or service and instead
requires continuous verification of the operational picture via real-time information fed from multiple sources to determine
access and other system responses.
The Zero Trust security model assumes that a breach is inevitable or has likely already occurred, so it constantly limits
access to only what is needed and looks for anomalous or malicious activity. Zero Trust embeds comprehensive security
monitoring; granular risk-based access controls; and system security automation in a coordinated manner throughout all
aspects of the infrastructure in order to focus on protecting critical assets (data) in real-time within a dynamic threat
environment. This data-centric security model allows the concept of least-privileged access to be applied for every access
decision, allowing or denying access to resources based on the combination of several contextual factors.

**Adopt a Zero Trust mindset**

To adequately address the modern dynamic threat environment requires:
- Coordinated and aggressive system monitoring, system management, and defensive operations capabilities.
- Assuming all requests for critical resources and all network traffic may be malicious.
- Assuming all devices and infrastructure may be compromised.
- Accepting that all access approvals to critical resources incur risk, and being prepared to perform rapid damage assessment, control, and recovery operations.

**Embrace Zero Trust guiding principles**

A Zero Trust solution requires operational capabilities that:
- Never trust, always verify – Treat every user, device, application/workload, and data flow as untrusted. Authenticate and explicitly authorize each to the least privilege required using dynamic security policies.
- Assume breach – Consciously operate and defend resources with the assumption that an adversary already has presence within the environment. Deny by default and heavily scrutinize all users, devices, data flows, and requests for access. Log, inspect, and continuously monitor all configuration changes, resource accesses, and network traffic for suspicious activity.
- Verify explicitly – Access to all resources should be conducted in a consistent and secure manner using multiple attributes (dynamic and static) to derive confidence levels for contextual access decisions to resources. 

**Leverage Zero Trust design concepts**

When designing a Zero Trust solution:
- Define mission outcomes – Derive the Zero Trust architecture from organization-specific mission requirements that identify the critical Data/Assets/Applications/Services (DAAS).
- Architect from the inside out – First, focus on protecting critical DAAS. Second, secure all paths to access them.
- Determine who/what needs access to the DAAS to create access control policies – Create security policies and apply them consistently across all environments (LAN, WAN, endpoint, perimeter, mobile, etc.).
- Inspect and log all traffic before acting – Establish full visibility of all activity across all layers from endpoints and the network to enable analytics that can detect suspicious activity.

NSA [Releases Guidance on Zero Trust Security Model](https://media.defense.gov/2021/Feb/25/2002588479/-1/-1/0/CSI_EMBRACING_ZT_SECURITY_MODEL_UOO115131-21.PDF)

## Articles ##

BeyondCorp began as an internal Google initiative to enable every employee to work from untrusted networks without the use of a VPN. Now, BeyondCorp is used by most Googlers every day to provide user-and device-based authentication and authorization for Google's core infrastructure and corporate resources.
BeyondCorp allows for single sign-on, access control policies, access proxy, and user- and device-based authentication and authorization. 

The BeyondCorp principles are:
- Access to services must not be determined by the network from which you connect 
- Access to services is granted based on contextual factors from the user and their device
- Access to services must be authenticated, authorized, and encrypted

  * Google BeyondCorp 1 [An overview: "A New Approach to Enterprise Security"](https://research.google.com/pubs/pub43231.html)
  * Google BeyondCorp 2 [How Google did it: "Design to Deployment at Google"](https://research.google.com/pubs/pub44860.html)
  * Google BeyondCorp 3 [Google's front-end infrastructure: "The Access Proxy"](https://research.google.com/pubs/pub45728.html)
  * Google BeyondCorp 4 [Migrating to BeyondCorp: Maintaining Productivity While Improving Security](https://research.google.com/pubs/pub46134.html)
  * Google BeyondCorp 5 [The human element: "The User Experience"](https://research.google.com/pubs/pub46366.html)
  * Google BeyondCorp 6 [Secure your endpoints: "Building a Healthy Fleet"](https://ai.google/research/pubs/pub47356)

- Deloitte's [Automating Zero Trust on AWS](https://www-cio-com.cdn.ampproject.org/c/s/www.cio.com/article/189367/automating-zero-trust-on-aws-implementing-security-automation-to-achieve-goals-for-deloitte-s-zero.html/amp)
- Forrester [Building Security Into Your Network's DNA: The Zero Trust Network Architecture](http://www.virtualstarmedia.com/downloads/Forrester_zero_trust_DNA.pdf)

## Books ##
- [Zero Trust Security: An Enterprise Guide](https://www.amazon.com/Zero-Trust-Security-Enterprise-Guide-dp-148426701X/dp/148426701X)

## Frameworks/Guidelines ##
- NIST [800-207](https://csrc.nist.gov/publications/detail/sp/800-207/final)
- CISA [Zero-Trust Maturity Model](https://www.cisa.gov/zero-trust-maturity-model)
- CISO [Guidance on Zero-Trust Maturity Model](https://www.cisa.gov/uscert/ncas/current-activity/2021/02/26/nsa-releases-guidance-zero-trust-security-model)

## Thank you!
A big 'thank you' to the content creators, and those working to make our systems and networks safer and more resilient!  

## Contribution rules
Clarifications, suggestions, and contributions welcome! If you want to contribute to this resource guide, please create a PR (Pull Request) with description what you are adding following these rules: 

* Clear description of PR (description of contribution, and resource to add or reference ) 
* Keep it simple - Fill the description properly
* Fact over feelings or personal opinions
* Add source and follow the library style
* Avoid duplicits

For tool additions:
* Open-Source only
* Add only active projects 

