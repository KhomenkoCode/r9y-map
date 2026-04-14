# Proactive DDoS Countermeasures

**Proactive Distributed Denial-of-Service attack Countermeasures**

**Definition:**
Proactive DDoS countermeasures focus on early detection, automated response, and traffic control before saturation occurs.
Modern Proactive anti-DDoS tools can offer filtering web traffic inside (WAF filtering level) or outside of Cloud Service provider (ISP/Edge Router level).

**Benefits:**
- Faster Detection and Response. Flow-based tools (FastNetMon) detect attacks in sub-seconds
- Prevents Auto-scaling overreaction (unexpected cloud costs)
- Multi-layer Protection (L3–L7) 
- Automated DDoS Mitigation

## Related Tools and Products

**Tools and Products for Vanilla DDoS Protection:**

**1. AWS CloudWatch:**

- [Website](https://aws.amazon.com/cloudwatch/)
- **Description:** Monitoring and observability service that can act as a detection and orchestration layer for application-level (L7) and infrastructure-level anomalies.

**2. FastNetMon:**

- [Website](https://fastnetmon.com/)
- **Description:** Real-time DDoS detection (sub-second)

**3. ExaBGP:**

- [Website](https://www.segment-routing.net/open-software/exabgp/)
- **Description:** Used with FastNetMon to announce blackhole routes / Redirect DDoS traffic


**4. AWS Shield (Advanced):**

- [Website](https://aws.amazon.com/shield/)
- **Description:** Always-on L3/L4 protection. Advanced tier adds adaptive DDoS mitigation and support.

**5. Google Cloud Armor:**

- [Website](https://cloud.google.com/security/products/armor)
- **Description:** Google’s global infrastructure (always-on protection)

## Related Terms

**Related Terms to Vanilla DDoS Protection:**

These related terms are often used in conjunction with Vanilla DDoS Protection.

## Prerequisites

Before conducting Proactive DDoS Protection, it is essential to have Vanilla DDoS Protection.

**1. :**---
type: post
---