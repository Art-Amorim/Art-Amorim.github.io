---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

![Datum pic](/images/datum.png){: .align-right width="300px"}
I'm a Ph.D. student in Computer Science at the University of Central Florida, advised by [Dr. Gary T. Leavens](https://www.cs.ucf.edu/~leavens/homepage.html), and a Graduate intern at the Idaho National Laboratory (INL) in the National & Homeland Security directorate, I work at the intersection of runtime enforcement and provable security, applying formal methods to harden critical infrastructure against emerging threats. My research lies at the intersection of formal methods, cyber-physical system security, and type theory, with a focus on making safety-critical systems resilient to stealthy and protocol-level attacks.

My work primarily targets unmanned aerial vehicles (UAVs) and industrial control systems (ICSs). These systems that increasingly rely on complex software stacks and communication protocols, making them attractive targets for sophisticated adversaries. Many existing security mechanisms overlook attacks that appear protocol-compliant yet induce unsafe behavior. My goal is to bridge that gap.

To address these challenges, I developed DATUM (Dynamically Assured Typed Universal Messaging), a protocol verification tool that integrates static verification and runtime monitoring using refined multiparty session types. DATUM enforces protocol correctness at runtime while providing formal safety guarantees through static analysis. It supports the MAVLink protocol, widely used in UAV autopilot systems such as ArduPilot and PX4, and enables the validation of legacy systems without requiring significant code rewrites.

My approach draws on concepts such as runtime verification, protocol attestation, and seL4-based software isolation to defend against powerful adversaries—including those who have already compromised parts of the system. By retrofitting these techniques into existing platforms, my work provides practical and deployable security for vulnerable CPS infrastructures.

With a strong foundation in mathematical logic, I am passionate about bridging theory and practice to solve real-world problems. I specialize in software verification, programming languages, and formal reasoning, with hands-on experience using tools like Coq, F\*, and Haskell.

My research has been published and presented at top-tier venues, including ICSS'24, DICE'25, ICUAS'25, NFM'25, and HCSS'25.

Feel free to explore my [CV](/cv/), [publications](/publications/), and reach out via [email](mailto:arthur.amorim@ucf.edu).