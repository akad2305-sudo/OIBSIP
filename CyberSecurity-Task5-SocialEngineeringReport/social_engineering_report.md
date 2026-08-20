# Social Engineering Attacks

## Oasis Infobyte Cyber Security Internship

### Task 5 — Research Report: Social Engineering Attacks

---

## 1. Introduction

Social engineering is a cybersecurity technique in which attackers manipulate people into performing actions that help the attacker gain information, money, access, or control of systems. Instead of attacking only computers or networks, social engineering targets human psychology. Attackers commonly exploit trust, fear, urgency, curiosity, authority, and helpfulness.

Social engineering is highly effective because even strong technical security controls can be weakened when a legitimate employee is tricked into clicking a malicious link, revealing information, approving access, or installing malicious software. Common social engineering attacks include phishing, pretexting, baiting, and quid pro quo.

---

## 2. Phishing

### What is Phishing?

Phishing is an attack in which criminals send fake emails, messages, websites, or phone communications that appear to come from a trusted person or organization. The goal is usually to steal passwords, financial information, authentication codes, or other sensitive information.

MITRE ATT&CK identifies phishing as technique T1566 and includes different forms such as spearphishing attachments, spearphishing links, and spearphishing by voice.

### How Phishing Works

A typical phishing attack follows these steps:

1. The attacker chooses a target.
2. The attacker creates a convincing message.
3. The message creates urgency, fear, curiosity, or trust.
4. The victim clicks a link, opens an attachment, or provides information.
5. The attacker obtains credentials, information, or access.

---

## 3. Types of Phishing

### 3.1 Spear Phishing

Spear phishing is a targeted phishing attack directed at a particular person or organization.

For example, an attacker may research an employee and send an email that appears to come from their manager.

### 3.2 Whaling

Whaling is a highly targeted phishing attack against senior employees such as CEOs, directors, and financial managers.

The attacker may impersonate another executive and request sensitive information or a financial transaction.

### 3.3 Vishing

Vishing means voice phishing.

The attacker uses a phone call or voice communication to impersonate a trusted organization or person. The attacker may pretend to be from a bank, IT department, or government organization.

### 3.4 Smishing

Smishing means phishing through SMS or text messages.

For example, a victim may receive a message saying:

> "Your bank account has been locked. Click this link to verify your account."

The link may lead to a fake website designed to steal credentials.

---

## 4. Phishing Real-World Case Study — 2020 Twitter Attack

A famous example of social engineering occurred during the 2020 Twitter attack.

Attackers targeted Twitter employees using social engineering techniques and obtained access to internal systems. They then used internal administrative tools to take control of approximately 130 Twitter accounts.

Several high-profile accounts were affected, including accounts belonging to Elon Musk, Bill Gates, and other public figures.

The attackers used compromised accounts to promote a Bitcoin scam. The incident resulted in financial losses and significant reputational damage.

The attack demonstrated that criminals can sometimes gain access to valuable systems by manipulating employees rather than directly exploiting a complicated software vulnerability.

### Impact

The incident resulted in:

- High-profile account takeovers
- Financial losses
- Disruption of Twitter
- Reputational damage
- Loss of public trust
- Exposure of weaknesses in employee security

---

## 5. Four Phishing Prevention Recommendations

### 1. Security Awareness Training

Employees should regularly learn how to identify suspicious emails, links, attachments, text messages, and phone calls.

### 2. Multi-Factor Authentication

Organizations should use multi-factor authentication to provide additional protection when passwords are stolen.

Phishing-resistant authentication methods should be preferred where possible.

### 3. Verify Unexpected Requests

Employees should independently verify unusual requests involving:

- Money transfers
- Passwords
- Authentication codes
- Sensitive documents
- Account changes

### 4. Use Email and Web Security Controls

Organizations should use:

- Spam filtering
- Malicious-link detection
- Attachment scanning
- Email authentication
- External-email warnings

---

## 6. Pretexting

### What is Pretexting?

Pretexting is a social engineering technique in which an attacker creates a believable false story to convince a victim to provide information or perform an action.

The attacker may pretend to be:

- An IT employee
- A bank employee
- A manager
- A customer
- A supplier
- A government official

### How Pretexting Works

1. The attacker researches the target.
2. The attacker creates a fake identity.
3. The attacker creates a believable story.
4. The attacker builds trust.
5. The attacker requests information or an action.

For example, an attacker may say:

> "I am from the IT department. We are updating your account. Please confirm your login details."

---

## 7. Pretexting Case Study — Twitter 2020

The 2020 Twitter incident also demonstrates how impersonation and social engineering can be used against employees.

Attackers reportedly posed as Twitter employees and manipulated employees into providing access to internal systems.

After obtaining internal access, the attackers used Twitter's administrative tools to target high-profile accounts.

The incident demonstrates why employees should verify unusual requests, even when the person making the request appears to be a legitimate colleague.

---

## 8. Three Pretexting Prevention Measures

### 1. Verify Identity

Employees should independently verify the identity of people requesting sensitive information.

### 2. Follow Approval Procedures

Sensitive activities should require proper authorization.

Examples include:

- Password changes
- MFA resets
- System access
- Financial transfers
- Account changes

### 3. Limit Public Information

Organizations should avoid unnecessarily exposing sensitive employee and company information.

Employees should also be careful about what information they share publicly on social media.

---

## 9. Baiting

### What is Baiting?

Baiting is a social engineering attack in which an attacker offers something attractive or interesting to persuade a victim to perform an unsafe action.

Attackers may exploit curiosity, greed, or interest.

Examples include:

- Free software
- Free games
- Fake prizes
- Infected USB drives
- Fake downloads
- Free documents

---

## 10. Physical Baiting

Physical baiting involves a physical object.

For example, an attacker may leave an unknown USB drive in a location where employees are likely to find it.

The USB may have a label such as:

> "Employee Salaries"

or:

> "Confidential"

A curious employee may connect the USB to a company computer.

The device could contain malicious files or software.

---

## 11. Digital Baiting

Digital baiting happens through online content.

Examples include:

- Fake software downloads
- Cracked software
- Fake browser updates
- Free games
- Fake documents
- Fake video players

The victim believes they are receiving something useful or free, but the download may contain malware.

---

## 12. Baiting Case Study — Stuxnet

The Stuxnet incident is a well-known example involving removable media and targeted industrial systems.

Stuxnet was sophisticated malware that affected industrial control systems in Iran.

Removable media played an important role in helping the malware reach systems that were not directly connected to the internet.

The incident demonstrated that even systems with limited internet connectivity can be exposed through removable devices.

---

## 13. Three Baiting Prevention Measures

### 1. Restrict Unknown USB Devices

Organizations should control which removable devices can connect to company computers.

### 2. Avoid Untrusted Downloads

Employees should download software only from approved and trusted sources.

### 3. Train Employees

Employees should understand that unexpected USB drives, files, and free downloads may be traps.

---

## 14. Quid Pro Quo

Quid pro quo means "something for something."

In this attack, the attacker offers a benefit in exchange for information or access.

For example:

> "I am from technical support. Give me your login details and I can fix your computer."

The attacker promises assistance but actually wants information or access.

### Prevention

Organizations can reduce these attacks by:

1. Verifying support staff identities.
2. Never sharing passwords or authentication codes.
3. Using official IT support channels.
4. Training employees to recognize suspicious offers.

---

## 15. Comparison Table

| Attack Type | Primary Target | Psychological Lever | Best Countermeasure |
|---|---|---|---|
| Phishing | Employees and online users | Urgency and trust | Security awareness + MFA |
| Spear Phishing | Specific employees | Trust and personalization | Verification + MFA |
| Whaling | Executives | Authority and urgency | Strong approval procedures |
| Vishing | Employees and customers | Trust and fear | Caller verification |
| Smishing | Mobile users | Urgency and curiosity | Link verification |
| Pretexting | Employees | Trust and authority | Identity verification |
| Baiting | Employees and device users | Curiosity and greed | USB/download restrictions |
| Quid Pro Quo | Employees | Helpfulness and reward | Official support procedures |

---

## 16. Employee Security Awareness Training Checklist

Organizations should provide regular security awareness training.

### 1. Identify Phishing

Employees should learn to recognize suspicious links, attachments, sender addresses, and urgent requests.

### 2. Verify Requests

Employees should verify unusual requests through another trusted communication channel.

### 3. Protect Passwords and MFA

Employees should never share passwords or authentication codes.

### 4. Use Devices Safely

Employees should never connect unknown USB devices or install software from untrusted sources.

### 5. Report Suspicious Activity

Employees should be encouraged to report suspicious messages, calls, downloads, and possible security incidents.

---

## 17. Organisational Recommendations

Organizations should combine employee training with technical security controls.

Recommended measures include:

- Multi-factor authentication
- Phishing-resistant authentication
- Email filtering
- Endpoint protection
- Least-privilege access
- Security awareness training
- Strong password policies
- Identity verification procedures
- USB restrictions
- Application allowlisting
- Incident reporting procedures
- Regular security awareness exercises

---

## 18. Conclusion

Social engineering attacks demonstrate that people can be targeted just as effectively as computers and networks.

Phishing uses fake communications to steal information or deliver malware. Pretexting uses believable false stories to manipulate victims. Baiting uses attractive objects, files, or downloads to encourage unsafe actions. Quid pro quo attacks offer a supposed benefit in exchange for information or access.

The strongest defense is a combination of security awareness, strong authentication, verification procedures, technical security controls, and a culture of reporting suspicious activity.

Employees should remember that anyone can be impersonated and that unusual requests should always be verified before action is taken.

---

## 19. References

1. MITRE ATT&CK — Phishing (T1566)  
   https://attack.mitre.org/techniques/T1566/

2. MITRE ATT&CK — Spearphishing Attachment (T1566.001)  
   https://attack.mitre.org/techniques/T1566/001/

3. MITRE ATT&CK — Spearphishing Link (T1566.002)  
   https://attack.mitre.org/techniques/T1566/002/

4. MITRE ATT&CK — Spearphishing Voice (T1566.004)  
   https://attack.mitre.org/techniques/T1566/004/

5. SANS Institute — Security Awareness Resources  
   https://www.sans.org/

6. WIRED — Twitter 2020 Hack  
   https://www.wired.com/story/how-alleged-twitter-hackers-got-caught-bitcoin/

---

## 20. Task Completion Checklist

- [x] Introduction
- [x] Social engineering definition
- [x] Phishing
- [x] Spear phishing
- [x] Whaling
- [x] Vishing
- [x] Smishing
- [x] Phishing case study
- [x] Four phishing prevention recommendations
- [x] Pretexting
- [x] Pretexting case study
- [x] Three pretexting prevention measures
- [x] Baiting
- [x] Physical baiting
- [x] Digital baiting
- [x] Baiting case study
- [x] Three baiting prevention measures
- [x] Quid Pro Quo bonus
- [x] Comparison table
- [x] Five-point employee security awareness checklist
- [x] References
