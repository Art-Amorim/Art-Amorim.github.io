---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


My research focuses on applying formal methods to ensure system security and resilience in cyber-physical environments. Below are selected publications:

---

### Peer-Reviewed Papers

### **Enhancing Cyber-Physical System Dependability via Synthesis: Challenges and Future Directions**
**Authors**: Max Taylor, Arthur Amorim  
**Conference**: *International Conference on Dependable Systems and Networks Workshops 2025*  
**Abstract**:  
Cyber-physical systems (CPS) rely on software that contains vulnerabilities and is connected to the public internet. Internet connectivity exposes CPS to adversaries, who can exploit vulnerabilities and cause CPS to operate in unsafe ways, thus compromising safety and liveness requirements. By formally designing safety and liveness requirements and synthesizing software that adheres to these specifications, unsafe behaviors can be prevented from the very beginning of system development. This paper presents initial results from ongoing research aimed at enabling the synthesis of software that controls CPS, ensuring dependability from the outset. 

**URL**: [IEEE](https://ieeexplore.ieee.org/abstract/document/11071612)

---

### **Runtime-Enforced Safety and Isolation for Unmanned Aerial Vehicles**
**Authors**: Arthur Amorim, Max Taylor, Trevor Kann, Gary T. Leavens, William L. Harrison, Lance Joneckis  
**Conference**: *2025 International Conference on Unmanned Aircraft Systems (ICUAS 2025)*  
**Abstract**:  
Unmanned aerial vehicles (UAVs) depend on untrusted software components to automate dangerous or critical missions, making them a desirable target for attacks. Some work has been done to prevent an attacker who has either compromised a ground control station or parts of a UAV's software from sabotaging the vehicle, but not both. We present an architecture running a UAV software stack with runtime monitoring and seL4-based software isolation that prevents attackers from both exploiting software bugs and stealthy attacks. Our architecture retrofits legacy UAVs and secures the popular MAVLink protocol, making wide adoption possible.  

**URL**: [Arxiv](https://arxiv.org/abs/2503.17298), [IEEE](https://ieeexplore.ieee.org/abstract/document/11007915)


---

### **Enforcing MAVLink Safety & Security Properties via Refined Multiparty Session Types**  
**Authors**: Arthur Amorim, Max Taylor, Trevor Kann, William L. Harrison, Gary T. Leavens, Lance Joneckis  
**Conference**: *2025 NASA Formal Methods Symposium (NFM 2025)*  
**Abstract**:  
A compromised system component can issue message sequences that are legal while also leading the overall system into unsafe states. Such stealthy attacks are challenging to characterize, because message interfaces in standard languages specify each individual message separately but do not specify safe sequences of messages. We present initial results from ongoing work applying refined multiparty session types as a mechanism for expressing and enforcing proper message usage to exclude unsafe sequences. We illustrate our approach by using refined multiparty session types to mitigate safety and security issues in the MAVLink protocol commonly used in UAVs.  

**URL**: [Arxiv](https://arxiv.org/abs/2501.18874),  [Springer](https://link.springer.com/chapter/10.1007/978-3-031-93706-4_1)

---

### **Towards Provable Security in Industrial Control Systems via Dynamic Protocol Attestation**  
**Authors**: Arthur Amorim, Trevor Kann, Max Taylor, Lance Joneckis  
**Conference**: *IEEE Workshop on Industrial Control System Security (ICSS 2024), co-located with ACSAC*  
**Abstract**:  
Industrial control systems (ICSs) increasingly rely on digital technologies vulnerable to cyber attacks. Cyber attackers can infiltrate ICSs and execute malicious actions. Individually, each action seems innocuous. But taken together, they cause the system to enter an unsafe state. These attacks have resulted in dramatic consequences such as physical damage, economic loss, and environmental catastrophes.  
This paper introduces a methodology that restricts actions using protocols. These protocols only allow safe actions to execute. Protocols are written in a domain-specific language we have embedded in an interactive theorem prover (ITP). The ITP enables formal, machine-checked proofs to ensure protocols maintain safety properties. We use dynamic attestation to ensure ICSs conform to their protocol even if an adversary compromises a component. Since protocol conformance prevents unsafe actions, the previously mentioned cyber attacks become impossible.  
We demonstrate the effectiveness of our methodology using an example from the Fischertechnik Industry 4.0 platform. We measure dynamic attestation's impact on latency and throughput. Our approach is a starting point for studying how to combine formal methods and protocol design to thwart attacks intended to cripple ICSs.  

**URL**: [Arxiv](https://arxiv.org/abs/2412.14467), [IEEE](https://www.computer.org/csdl/proceedings-article/acsac-workshops/2024/328100a120/25bv2vFkH9m)

---

## Invited Talks
**Automated Reasoning for UAV Safety & Security: The DATUM Protocol Stack** 
**Authors**: Arthur Amorim, Max Taylor, Trevor Kann, Gary T. Leavens, William L. Harrison, Lance Joneckis  
**Conference**: *2025 High Confidence Software and Systems Conference (HCSS 2025)*  

**Dynamically checking protocols with DATUM**  
**Authors**: Max Taylor, Arthur Amorim
**Conference**: *2025 DICE Digital Engineering Conference (DICE 2025)*  






