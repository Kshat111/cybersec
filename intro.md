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

Use multiple layers of security so that if one fails, others are ready to protect against the attack, keep in mind that 'security is economics'.

7. **Least privilege**

Information abstraction i.e. give people/system only the permissions they need, nothing more.

8. **Separation of responsibility**

Split responsibilities so that no single person has the complete power.

9. **Ensure complete meditation**

It's like authorization, always check permissions before allowing access to a resource.

10. **Don't rely on security through obscurity**
- Don't assume that something is secure just because no one knows how it works.
- Apps which hide their algorithms, design, or source code for security have failed miserably *(Shannon's Maxim)*.
- **Does this mean open source apps are less secure then closed source apps? NO**. Because a system should be secure even if everything about it is known, except the secret key/sensitive data *(Kerckhoff's Principle)*. *This means the design of the system should assume attackers know everything about the code and algorithms. Security should come from strong encryption, proper authentication mechanisms, and secure coding practices—not from "hiding" how the app works.*
- Closed source apps are not automatically more secure as attackers might reverse engineer to find the source code or vulnerabilities.

11. **Use Fail-Safe defaults**

The system must go to a 'secure state' if something goes wrong.

12. **Design security from the start**

Integrate security into the system from the start, instead of adding it later as an afterthought.
