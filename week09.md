# week 09
## Task 2: Protection of Assets and CIA

### Asset 1: Customer Information

Use of the Business Website to distribute information regarding customers.Using the Business Website to share information about customers.

* **Protection-Confidentiality and Integrity**
* **Reason:** Only authorised users should have access to or be able to make changes to information about customers. Any information that has been changed, misinterpreted or unauthorized can result in a customer receiving inaccurate information.

---

### Asset 2: Business Website / Web Server

This is the primary website or web server for the business.This is the main Website / Web Server for the business.

Data that is safe and secure.Availability and Integrity = Data is protected and secure.

* **Reason:** The website should be readily accessible to customers when they require information regarding the business. It's also essential that the content is correct and cannot be changed by unauthorized users.

---

### Asset 3: User Account Credentials

This is a user account credential.

The protection relates to the confidentiality and integrity of data.Protection refers to the confidentiality and integrity of data.

* **Reason:** Staff security information (password and logon information) should never be shared or misused.

---

### Asset 4: Business or Office Client Records

Create a record from any office or business client.Make a record of any business or office client.

* **Protection:** Confidentiality

Choosing this is done to provide business client records to the asset. These can be proprietary business data. These should be accessible only to those staff with authorisation, kept up to date and be available at the appropriate times.

---

### Asset 5: Business Database / Data Files

These principles help to guarantee that data is kept private and secure.The three principles of protection are confidentiality, integrity and availability.

* **Reason:** Business data should be protected from unauthorised access, accidental or malicious change, and denial of access.

---

### Asset 6: OpenWRT Router / Firewall

This is an OpenWRT router / firewall.This is an OpenWRT Router / Firewall.

* **Accessibility:** Availability and Integrity
* **Reason:** The router/firewall must be turned on and operational for the staff to be able to use the Internet and for the business network to function. It must not be changed by anyone else than the authorised user.

---

### Asset 7: Staff Windows Workstations

What are the reasons for having Windows Workstations for staff?Why do we need Staff Windows Workstations?

* **Protection:** Confidentiality and Integrity
* **Reason:** Workstations can contain business and client information and must be stored and protected from unauthorised access or modification.

---

### Asset 8: Network and Firewall Configuration

The outcomes can be achieved in various ways, including:Methods of attaining the outcomes may include:

Bad/unauthorised firewall changes can reveal the network or prevent the network from running services. To work properly, the network needs to be set up properly.


## Task 3: Threat Sources and Motivation

### Threat Source 1: Cybercriminal / Hacker

The cybercriminal/hacker is the potential threat source.The potential threat source is the cybercriminal/hacker.

**Motivation:** Motivated to gain unauthorised access to business systems, steal information or disrupt business services for financial gain.

---

### Threat Source 2: Competitor Company

The other threat is Competitor Company.The other threat is Competitor Company.

**Motivation:** Desires access to confidential business or client information that would give a business/cliente the competitive edge.

---

### Threat Source 3: Disgruntled Employee

The third source of threat is a disgruntled employee.The third source of threat is a disgruntled employee.

**Motivation:** Dissatisfaction with the business, wants to harm, disrupt business, use and access confidential business information.

---

### Threat Source 4: External Attacker

Threat Source 4 involves an external attacker.

**Motivation:** Desire to take advantage of the vulnerability of the OpenWRT router or firewall, website or other networks to gain unauthorised access.

---

### Threat Source 5: Malicious Insider

Threat Source 5: Malicious Insider

**Motivation:** Desire to use the credit to access, alter or reveal business or client information without permission.

---

### Threat Source 6: Opportunistic Attacker

The opportunistic attacker is the next threat source on the list.The next threat source in the list is opportunistic attacker.

**Motivation:** Seeks to find poorly secured systems or services that can be exploited, without specifically targeting the business.

---

### Threat Source 7: Automated Bots / Scanners

They are also known as automated bots or scanners.They are also called automated bots or scanners.

Search automatically the Internet for vulnerable services, open ports, weak credentials or outdated systems that can be exploited.

---

### Threat Source 8: Former Employee

The last threat source is a former employee.The final threat source is a former employee.

**Motivation:** May attempt to access network services or business data with a previously known credential or access information to disrupt network services or access data.

## Task 4: Explore Vulnerabilities

### CVE 1 – Critical

#### CVE ID

**CVE-2025-14326**

#### CVE Description

Uses after free in the Audio/Video: GMP component. This vulnerability was fixed in Firefox 146 and Thunderbird 146.

#### Date

**9 December 2025**

#### CVSS Version 3 Score

**9.8 – Critical**

**CVSS Vector:** `CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H`

#### CIA Impact

* **Confidentiality:** High
* **Integrity:** High
* **Availability:** High

#### CWE

* **CWE-416 – Use After Free**

#### Company

**Mozilla**

#### Product

**Mozilla Firefox**

Firefox is a Web browser application through which one navigates websites or Web-based services.

#### Simple Explanation

This vulnerability occurs when Firefox uses a portion of computer memory after it has already freed. This can result in unpredictable user behavior and can enable an adversary to disrupt the browser.

#### Detection and Mitigation

The primary mitigation is to upgrade Firefox to version 146 or higher. The version that's been patched is Mozilla Firefox 146.Firefox 146 is identified as the fixed version in Mozilla's security advisory.

---

### CVE 2 – High

#### CVE ID

**CVE-2026-70336**

#### CVE Description

Visual Studio Code generates code improperly (also referred to as code injection), enabling an unauthorised attacker to run code over a network.

#### Date

**11 August 2026**

#### CVSS Version 3 Score

**8.8 – High**

**CVSS Vector:** `CVSS:3.1/AV:N/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H`

#### CIA Impact

* **Confidentiality:** High
* **Integrity:** High
* **Availability:** High

#### CWE

CWE-94 is the name given to the vulnerability.The name of the vulnerability is CWE-94: Improper Control of Generation of Code ('Code Injection').

#### Company

**Microsoft**

#### Product

**Visual Studio Code**

Visual Studio Code is a source-code editor that developers use to write, edit, debug and manage software projects.

#### Simple Explanation

Vulnerability: Code Injection. An attacker could run unwanted code via Visual Studio Code. This might enable the attacker to compromise the confidentiality, integrity and availability of the system.

#### Detection and Mitigation

The following versions of Visual Studio Code are affected: Microsoft identified versions prior to the fixed version. The primary mitigation is updating to a supported patched version of Visual Studio Code.

---

### CVE 3 – Medium

#### CVE ID

**CVE-2026-58546**

#### CVE Description

An uninitilized resource is a resource that has not been initialized with Windows RDP, which can be used by an unauthorised party to reveal data on a network.

#### Date

**14 July 2026**

#### CVSS Version 3 Score

**6.5 – Medium**

**CVSS Vector:** `CVSS:3.1/AV:N/AC:L/PR:N/UI:R/S:U/C:H/I:N/A:N`

#### CIA Impact

* **Confidentiality:** High
* **Integrity:** None
* **Availability:** None

#### CWE

Avoid using a resource that has not been initialized.Do not use any resources prior to them being initialized.

#### Company

**Microsoft**

#### Product

**Windows Remote Desktop Protocol (RDP)**

RDP is a feature of the Windows operating system that enables users to use a remote network connection to log on to and use another Windows computer.

### Simple Explanation

The vulnerability is due to an uninitialised resource used by Windows RDP. This could allow an attacker to steal information from the system via network.

#### Detection and Mitigation

The affected Windows versions should be identified and updated with Microsoft's security updates. Limiting unnecessary RDP access and enabling RDP access only to authorised users and networks can also help to limit exposure. Details on the security update are available from Microsoft.

## Task 5: Vulnerability Disclosures

I'm not a fan of any of those Californians.None of those Californians are my view.

I think that it's important to do vulnerability disclosure carefully, so that when you disclose them, they're not out there and the attackers have information about them so they can attack before the vendor can provide a patch. However, vendors cannot afford to stall for too long, otherwise users would not be aware of security threats and take steps to safeguard their systems.

### Why Vendors May Take Time

A vendor might require to:

* Understand and verify the vulnerability.
* Determine the affected products and versions.
* Create a security patch or other mitigation.
* Test fix to ensure it does not introduce new issues.
* * Give customer security recommendations.
* Coordinate with security researchers and any other organisations affected.

Triaging, code development, code review, testing, and deployment of a fix can take a long time in larger organisations, according to OWASP.

### What is a reasonable time?

I believe a reasonable time would allow the vendor to investigate and come up with a solution, but there should be a definite time limit. The 90 days period is a reasonable starting point for many vulnerabilities, but depends on the severity and complexity of the vulnerability.

According to OWASP, Google's Project Zero has a 90-day cycle for releasing vulnerability information.

### Should researchers "make it public"?

I would generally prefer researchers to report the vulnerability to the vendor first and give the vendor reasonable time to solve the problem, unless it seems to be too serious to do so. This minimizes the risk of attackers being tipped off about the vulnerability in advance of users being able to defend against it.

When repeated communication with the vendor has failed to bring about reasonable action and an agreed time limit has elapsed, however, public disclosure might be an option. Before releasing technical details or proof-of-concept code, the researcher should take into account the potential risks. Full disclosure is controversial, and is usually only considered if none of the other methods have succeeded or if the information on the exploit is already available.

---

#### Coordinated Vulnerability Disclosure

I think that coordinated disclosure is a good way to do it since it provides them a chance to cooperate with each other, the researcher, and the vendor. The researcher can give the vendor sufficient details to recreate the problem; the vendor can develop and test a fix before the vulnerability is made public.

Microsoft also tells users about Coordinated Vulnerability Disclosure: It is a process under which the researchers report vulnerabilities to the vendors privately, allowing the vendors to better understand the impact and solve the problem before the vulnerability is disclosed.

---

#### Bug Bounty Programs

Bug bounties can help incentivize security researchers to report vulnerabilities directly to companies. They can offer incentives and acknowledgements to researchers and assist companies fix their security vulnerabilities.

But companies must have guidelines with respect to what researchers can test, how vulnerabilities should be reported and whether researchers can publish the information. However, as cited by OWASP, there are challenges that can occur with bug bounties including false reports, resource needs and researchers testing systems outside the scope.

---

#### Conclusion

In general, I think a balance between the three pillars of security, transparency, and responsible communication should be struck in the disclosure of vulnerabilities. Generally, vulnerabilities should be reported privately to the author(s) of the research paper first and vendors should respond and make efforts for a fix within a reasonable time. Public disclosure needs to be thought out: it can get defenders a better idea of the problem, but it can also be helpful to an attacker. A coordinated approach can be a practical method for both researchers and vendors to collaborate and mitigate the dangers to users.

