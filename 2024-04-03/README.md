# 2024-04-03: Risk-Based Approach to Vulnerability Prioritization

Unpacking in more detail: see pdf

The main focus of the paper, "Health-ISAC: Risk-Based Approach to Vulnerability Prioritization," is to advocate for a more nuanced and risk-based approach to the Sisyphean task of vulnerability management. In a world where the number of vulnerabilities is so high that it could give anyone trying to patch them all a Sysadmin version of a nervous breakdown, the paper wryly suggests that maybe, just maybe, we should focus on the ones that bad actors are actually exploiting in the wild. It's a radical thought—prioritizing based on actual risk rather than just running around like headless man trying to address a CVSS score while apocalyptic cats are falling from the sky.

The document, with a hint of black humor, acknowledges the absurdity of the traditional "patch everything yesterday" approach, given that only a minuscule 2-7% of published vulnerabilities are ever exploited. It's like preparing for every possible natural disaster every day, instead of just the ones that are likely to hit your area. The paper introduces a cast of characters in the form of frameworks and scoring systems—such as the EPSS and SSVC—that are designed to help organizations make sense of the vulnerability chaos with the precision of a surgeon rather than the blunt force of a sledgehammer.

In essence, the paper is a call to arms for organizations to stop playing whack-a-mole with vulnerabilities and instead adopt a more strategic, targeted approach that considers factors like the actual exploitability of a vulnerability, the value of the asset at risk, and whether the vulnerability is lounging around on the internet or hiding behind layers of security controls. It's about working smarter, not harder, in the cybersecurity equivalent of an endless game of Tetris where the blocks just keep coming faster and faster. 

**Key findings**
So, let's dive into the thrilling world of vulnerability management. If you're a fledgling organization, you might be tempted to remediate all critical and high severity vulnerabilities using the scoring system within your chosen vulnerability scanning tool. It's like trying to buy the entire stock market in an attempt to diversify.

Wait, there's a catch! This approach might just overwhelm your remediation teams with the sheer number of vulnerabilities they have to focus on. It's like asking someone to count all the grains of sand on a beach. And let's not forget, those sneaky threat actors might not always exploit the highest severity vulnerabilities. Instead, they might chain together multiple exploits of less severe vulnerabilities to gain access to systems

Now, if you're feeling adventurous, you might want to focus on known exploited vulnerabilities. It's like playing whack-a-mole, but instead of moles, you're dealing with actual threats. This approach significantly reduces the number of vulnerabilities that need immediate attention and ensures practitioners focus on vulnerabilities that pose the greatest threat to organizations

Now, it gets even more exciting! You also need to consider the network location of your vulnerabilities. Internet-facing vulnerabilities and misconfigurations should always be a priority since they're like a neon sign inviting threat actors to come and play. For systems that are internally facing or not accessible from the internet, these should fall under an internal service level agreement (SLA) remediation timeline

And let's not forget about asset value. It's like playing a game of Monopoly, but instead of properties, you're dealing with your organization's assets. If a device that is of the utmost importance to the operation of the business or holds critical information were to be compromised, it could be catastrophic to the organization

But wait, there's more! You also have to consider compensating controls. These are like your organization's security bodyguards, making it more difficult to exploit vulnerabilities. However, changing a vulnerability's severity or risk rating without sufficient data to support the change can cause teams to focus on the wrong vulnerabilities and weaken an organization's security posture

Finally, we have the Exploit Prediction Scoring System (EPSS) and Stakeholder-Specific Vulnerability Categorization (SSVC). EPSS is like a crystal ball, predicting the likelihood or probability that a vulnerability will be exploited in the wild. SSVC, on the other hand, is like a personalized roadmap, focusing on values, including the security flaw's exploitation status, its impact on safety, and the prevalence of the affected products

So there you have it, the rollercoaster ride that is CVSS scoring. It's a wild ride, but with the right approach, you can navigate the twists and turns and keep your organization safe from those pesky vulnerabilities.