# Week 05

## task 02
![ethernet](./image/week05_task01_ethernet.png)

Below is a quick summary of each trail:

255.255.255.255/32: IPv4 Limited Broadcast — Network-wide broadcast traffic is sent to all hosts on the local physical segment.

224.0.0.0/4: IPv4 Multicast Range — Directs traffic sent to multicast groups (224.0.0.0–239.255.255.255).

10.178.35.255/32: Subnet Broadcast — Broadcast address specific to the local 10.178.32.0/22 subnet.

Local IPv4 Address — Represents the IP address that this local computer has been assigned.

10.178.32.0/22: Local Subnet Route — Directs traffic to local neighbor devices (10.178.32.1–10.178.35.254) without needing a router.

0.0.0.0/0: Default Gateway — Routes all Internet and external network traffic through gateway router 10.178.32.1.

ff00::/8: IPv6 Multicast Block – All IPv6 group traffic on the local interface.

fe80::91fd:c26c:d9b6:80b: Local IPv6 Address — IPv6 Address assigned to this machine that is used for local communication.

fe80::/64: IPv6 Link-Local Subnet — IPv6 traffic— a reserved address that links together devices that are directly connected on the same physical link.
 IPv6 Link-Local Subnet: IPv6 traffic is sent to other devices that are attached to the same physical link.

 ## task 03
  ![ethernet](./image/week05_task03_lan.png)
![ethernet](./image/week05_task03_packet.png)
![ethernet](./image/week05_task03_routing_table.png)


| Device | Interface | IP Address/Subnet Mask | Default Gateway |
| :--- | :--- | :--- | :--- |
| PC 1   | eth0 |  62.11.0.10 /24 | 62.11.0.1 |
| PC 2   | eth0 | 62.11.0.11 /24 | 62.11.0.1 |
| PC 3  | eth0 | 62.11.0.12 /24 | 62.11.0.1 |
| Switch 1  | — | Unassigned | — |
|Router 1 | eth0 | 62.11.0.1 /24 | N/A |
| Router 1 | eth1 | 10.0.0.1 /24 | N/A |
| Router 2 | eth1 |  10.0.0.2 /24 | N/A |
| Router 2 | eth0 |    74.24.0.1 /24 | N/A |
| Switch 2 | — | Unasdsigned | — |
| PC 4 | eth0 | 74.24.0.10 /24 | 74.24.0.1 |
| PC 5 | eth0 |   74.24.0.11 /24 | 74.24.0.1 |


## Task 4 
-The students will adhere to academic honesty.The students will demonstrate academic honesty.

- This is the strongest case for an overlap in the scenarios of un-cited AI code generation and AI for collaboration.This is the best scenario for overlapping AI code generation and AI for collaboration.
- A student was given a tight deadline for an assessment script, and was able to use an AI coding assistant to turn an idea into a nucleus of an assessment, without citing or declaring it appropriately. Moreover, they presented their completed logics to another classmate and asked them to "help" them "debug," so that their two logics are very similar.

---

### 1. Group Discussion Summary

- What were the students' opportunities for improvement?
- The student should have sought extension of time for the assignment through the formal process at CQU instead of relying on the unreferenced AI generation under time pressure, or during consultation time with the unit coordinator/tutor.
- If AI tools are allowed to use during brainstorming or debugging (in the unit), the student MUST clearly state and cite the use of AI as per the CQ assessment guidelines.
Independent Work: The student should have discussed the concepts they used, rather than giving their actual code solution to their classmate, to the student's classmate, or to the student's teacher.

---

- A person's level of breach, likely outcome and fairness (CQU Policy) will be assessed.The person's level of breach, likely outcome and fairness (CQU Policy) will be assessed.

-  Violation of Minor to Moderate Academic Misconduct (Inappropriate use of generative AI/ Plagiarism and Collusion):
Under CQU Policy: most likely outcome:
  First Offence: Warning, Attendance to Academic Integrity Module (AIM) and Loss of 1 mark or a score of zero for the specific assessment element.
  Repeated/Severe Offence: Zero grade ($0\%$) for the entire assessment or failure of the unit ($F$ grade), that appears on the CQU Academic Misconduct Register.
* **Fairness Perspective:**
  Is the student fairly treated? (Yes/No) Yes. It holds students accountable to professional ethics and provides a chance to learn through remedial education to first-time offenders.
  Yes – for fair to hardworking students. The integrity and worth of the degree are valued and protected by strict penalties for students who labor individually.

---

If not caught, what might be implications into the future?

* **For the Student:**
  Skill Deficit: Fails to build fundamental skills and experiences significant problems in more demanding courses, capstone projects, and/or industry placement.
  Unsafely using shortcuts could lead to workplace consequences such as discipline, termination, or disqualification from professional bodies (such as ACS membership).
For Other Students & CQ HECATE (Awarded by CQ HECATE)
  Passes without any effort devalue CQUs technology degrees' reputation and accreditation in the job market, affecting all graduates.

---

## 2. Recommendations for Students

2. Always declare & cite external tools: If using AI assistants, code libraries or other external documentation to aid learning, declare and cite in line with the guidelines of the CQU and referencing rules.
Never share your code files or finished assignments with another student, but only explain the abstract logic, make block diagrams or post the official CQU documentation.
## Task 5: IP Address Lookup.

- **Accuracy:** Approximate. It is the city or metropolitan area, not an exact address or street.

- The choice between home Wi-Fi and mobile data.Home Wi-Fi vs Mobile Data.
-          Home Wi-Fi or Broadband IP (e.g., `120.147.45.12`) is correct as broadband IP ranges are associated with the local ISP exchange hubs.
-         Less accurate (often miles away from the location in a central gateway state) using less accurate Carrier-Grade NAT (CGNAT) routing.

- The public IP, ISP name, country, state, and a rough estimate of the city are identified.

- Not identified: Exact street address, GPS location, local private IP (such as `192.168.1.15`) or specific device name.
