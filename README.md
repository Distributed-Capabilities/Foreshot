# Foreshot – Gathering Intelligence on the Early Stages of the Cyber Killchain

Foreshot is a methodology focused on making cyber intelligence more proactive.
In short, it involves honeypotting the first three phases of the cyber kill chain, whereas traditional honeypots typically focus on the last four phases. Proper execution of the initial three phases bypasses conventional honeypots.

There are three parties involved:

- **The adversary** – the attacker looking for information for their cyber operation
- **The target/victim** – the actor the adversary wants to compromise
- **The operator** – the person who creates the honeytrap for the adversary

## Main Goal

The primary objective is to provide the adversary with controlled information in the very early stages of a cyber operation, thereby increasing the likelihood of operational security failures. In these stages, an adversary is rarely concerned with the traceability of the information gathering, the potential risks involved, or the possibility of weaponizing that information to dismantle or expose their own operation. Regardless of the collection method, the aim is to create and disseminate specific target information that the adversary is interested in or that represents key components of a potential cyber operation.

## Preconditions

The success of the methodology relies on several preconditions:

- The information should be disseminated through a trusted or neutral source.
- Ideally, the information itself should not pose a risk to the adversary.
- Patience and time are required; forcing the adversary to consume the information can increase exposure and risk for the operator.
- The information should be highly target‑specific and require prior knowledge, such as:
  - Public penetration‑testing reports
  - Network diagrams
  - Presentations or slides about systems
  - Tender documents
  - Version details of software or systems used by the target
  - Contact lists
  - Repositories
  - Credentials (usernames, passwords, secrets)

## Implementation

The methodology has the following phases.

1. **Selecting the adversary** to target.
2. **Determining which data** the operator wants to gather from the adversary:
   - IP addresses
   - User agents
   - Behaviours & interests
   - Access level (high risk, high reward, but also potential by‑catch).
3. **Identifying a significant target for the adversary**:
   - Past targets
   - Similar targets to those previously targeted
   - Intelligence – this methodology can also be used to discover who is being targeted by spreading a wide range of information.
4. **Understanding the target’s operations**: what they do, how they work, and what they need.
5. **Acquiring specific information** relevant to the adversary.
6. **Tailoring the information**:
   - Making it more relevant to the adversary
   - Removing real details
   - Weaponising the information.
7. **Identifying distribution channels**. These can be created depending on the objective:
   - Press releases
   - Information‑specific forums or distributions
   - Leaking through adversary‑aligned social media.
8. **Setting up monitoring systems** for the information:
   - Web Application Firewall (WAF)
   - Google Analytics
   - Execution‑triggered systems
   - Information‑specific tracking.
9. **Adding/implementing vpn/tor stripping**
10. **Testing everything**.
11. **Publishing and distributing the information**.
12. **Monitoring, detecting, identifying, and gathering**.
13. **Using the gathered data as targeting information for your operation**.

## Example

*(Work in progress – overview will be added soon.)
