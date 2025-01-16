## What is security?
The practice of protecting assets (data, systems, personal, financial, health, emotional, career, information, etc) from harm, theft, or unauthorized access.

## Cybersecurity
A branch of security focused on protecting assets in cyberspace.

### Need of cybersecurity
1. Protect sensitive data
2. Prevent financial loss
3. Maintain trust
4. Legal obligations

## Security Principles

### Spending for security is based on the impact and likelihood of potential harm - Both are nearly impossible to measure precisely 


1. **Know your threat model**
- Threat: Potential cause of harm; can be malicious or not.
- Threat model: Understanding who or what could attack you, why, and how.
- This is a structured process having the following objectives: Identify security requirements, Pinpoint security threats and Potential vulnerabilities, Quantify threat and vulnerability criticality, and Prioritize remediation methods.

2. **Trusted Computing Base**
- The set of hardware, software, and controls that are critical to a system's security.
- e.g., OS and encryption tools are part of my TCB, if they fail, everything else does too. 
- A smaller and simpler TCB is easier to write and audit; KISS principle (Keep it Simple, Stupid)
- Modern OS strive to reduce the size of the TCB; *reference monitor* in kernel space verifies that the request is allowed by the access control policy (all sys calls go through it for security checking).

3. **Human Factors**
- Humans are the weakest link in security so make systems which are easy to use and hard to mess up. There's no patch for human stupidity.
- Use password managers if employees keep forgetting their passwords.

4. **Security is economics**
- Security is not free - it requires money and time.
- If the attack costs more than the reward, the attacker probably won't do it. You don't put a $10 lock on $2 item.
- Using "Burglar alarm" sign board without even having one may help in preventing attacks, just like putting "Beware of Dog" poster without keeping a dog at home.

5. **Detect if you can't prevent**
- Deterrence: Stop the attack before it happens.
- Prevention: Stop the attack as it happens.
- Detection: After an attack has happened, learn that there was an attack.
- Response: Once attack has happened, respond to it. Detection without response is pointless.

6. **Defense in depth**

7. **Least privilege**

8. **Separation of responsibility**

9. **Ensure complete meditation**

10. **Don't rely on security through obscurity**

11. **Use Fail-Safe defaults**

12. **Design security from the start**
