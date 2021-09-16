# SECtember 2021

 Notes from SECtember

Worth looking into - <https://www.vendorpedia.com/>

<h2> Jen Easterly - Director of CISA </h2>

More connections = larger attack surface = tasty target for APT/NSH

CISA - Cybersecurity QB, implement & adopt tech, research attackers, and the ways they attack

63% of top CISOs have reported a cloud data breach that included customer information

82% plan to expand security spending

(Research new information about Solarwinds attack)

May presidental decleration of increased security - <https://www.whitehouse.gov/briefing-room/presidential-actions/2021/05/12/executive-order-on-improving-the-nations-cybersecurity/>

CISA released maturity architectural model - <https://www.cisa.gov/publication/zero-trust-maturity-model>

CISA Cybersecurity Summit - <https://www.cisa.gov/cybersummit2021>

Trusted Internet Connections - <https://www.cisa.gov/trusted-internet-connections>

JCDC - <https://www.cisa.gov/jcdc>

CyberSec is a team sport, no one group could do it alone.

Cyber Hygiene - <https://www.cisa.gov/cyber-hygiene-services>

CyberSec Awareness Month - <https://www.cisa.gov/cybersecurity-awareness-month>

Standards remove complexity, complexity is the most reliable attack surface

<h2> Panel Discussion: Key Priorities & Challenges in a Digitally Transforming Business World </h2>

Andy Kirkland - Starbucks CISO

2nd largest payment processor (Apple #1)

Day 0 -> Day 30 -> Day 60 -> Day 90 -> Day 180 all present different challenges, and control begins to slip away.

Being honest about the risks to the leadership is essential

Good communication lines with legal will make your life easier, you are on the same team

Pete Chronis - CTO @ CSA

Easier to invest in new, than to fix and support the old

Understand what the business is going through, security is a part, but knowing the entire landscape establishes common ground

The more bad stuff you find, the better. You can't fix what you don't know.

Just because it's secure today, doesn't mean it's secure tomorrow (Read the news)

Market doesn't demand vendor products secure by default, so CyberSec must audit

Be transparent about what you're not doing, and why

Aravind Swaminathan - Co-chair of CyberSec & Privacy @ Orrick

Legacy = Juicy attack surface (Data breaches almost always hit legacy)

Low hanging fruit is the most common issue to deal with, no matter which client

3 most common problems;

Patch management

Insecure resources

Vuln assessment - Product team thought security was scanning, security thought it was product team's responsibility

<h2> Cloud Native Security & Policy Management </h2>

Cloud Native Computing Foundation Security Advisory Group - <https://github.com/cncf/tag-security>

CNS Whitepaper - <https://github.com/cncf/tag-security/blob/main/security-whitepaper/CNCF_cloud-native-security-whitepaper-Nov2020.pdf>

Kyverno - <https://kyverno.io/>

XACML - <https://en.wikipedia.org/wiki/XACML>

K8s policies are a digital contract between Dev & SecOps

<h2> Fireside Chat: Mark Russinovich </h2>

Cloud is more secure than just distributed systems

Cloud security is fundamentally an IAM issue

Mutually authenticated with TLS

Ransomware can be defeated by lifting and shifting inside the cloud assuming frequent and assured backups

Segmentation stops lateral movement once initial access has been established

The future is password-less - <https://www.microsoft.com/security/blog/2021/09/15/the-passwordless-future-is-here-for-your-microsoft-account/>

OSSF - <https://openssf.org/>

We are in a golden era of CyberSec, let's look how to make it even better

<h2> Panel Discussion: Giving Zero Trusts About Cloud Security </h2>

Zero Trust - Remove inherent trust internally and externally

Lianne Caetano - Senior Director @ Lookout

ZT is a mindset that uses already established policies, while still maintaining security

Identify and prioritize your data/applications/services and monitor those

User experience should not degrade because of ZT, should improve

Shawn Harris - Director of Information Security @ Starbucks

ZT is a journey, you have to make continuous decisions

Ensure users can access their systems, with the absolute minimum of privileges

<https://www.checkpoint.com/cyber-hub/cloud-security/what-is-cspm-cloud-security-posture-management/>

ZT is a strategic direction

ZT starts with identity management

Watchout for config drift

Sameer Malhotra - CEO @ TrueFort

ZT is a process that is constantly has to adjust to a changing environment

Get small successes, publicize them, and build into bigger wins

Do you have the info you need? Do you understand it? Continuous assessment

<h2> Trust in Security Automation – The Key to Defending the Expanding Threat Landscape </h2>

Technology is changing, skills are stagnating, the gap still exists (Cloud migrations perfect example)

Do we trust our assets? (know your asset - all the time)

Security shouldn't find out about something new because of an expense report

CSAM - CyberSecurity Asset Management;

Where is my asset?

What role is it playing?

What software is it running? Is it supported? Is it authorized?

CSAM automation - Always UTD architecture, Trigger enforcement response

Trust in patching - recycling VM not always best solution, need to prioritize and keep out of siloing, or face prolonged exposure to risk

<h2> Top Threats Modeling </h2>

<https://cloudsecurityalliance.org/artifacts/top-threats-egregious-11-deep-dive/>

<https://cloudsecurityalliance.org/artifacts/top-threats-to-cloud-computing-egregious-eleven/>

<https://cloudsecurityalliance.org/artifacts/cloud-penetration-testing-playbook/>

<https://cloudsecurityalliance.org/artifacts/cloud-threat-modeling>

<https://docs.google.com/spreadsheets/d/1jveymeQHsvRG_Xai6hhkjtV84re1X4PjDCcaRbS3uIw/edit#gid=1887970851>

<h2> Fireside chat with Christopher Krebs </h2>

3.5 years of testing, war games, and adjusting posture, still couldn't plan for everything

Identify the absolute worse case, and build to mitigate 

ZT is resilience 

Save receipts 

2016 - Ukrainian power grid attack | 2017 - Wannacry/NotPetya/BadRabbit | 2018 - Cloudhopper | 2019 - Solamani Strike | 2020 - Solarwinds | 2021 - Kaseya

Supply chain attacks will continue to be the future until we do enough to stop it

We continue to not learn from prior events

Security board to review events, outside resources, re-affirm best practices and procedures

CISA should not be part of DHS

The future of CISA should be in the field 

When you communicate clearly, you can create a culture of security 

<h2> Supply Chain Attacks: The Rise of Ransomware and How to Reduce Your Risk </h2>

Critical software - Software with a direct dependency on one or more components that has elevated privs, can control access to data, performs critical trust functions, or operates outside of normal trust boundaries 

Threat model - Automated testing - Static analysis - Dynamic analysis - Check included software - Fix bugs

TPRM Tips & Tactics;

Ransomware is a risk, even if you're not the target

TPRM Lifecycle - Onboard vendor -> Due diligence -> Assess/Review -> Mitigate risks -> Report & Visualize -> Monitor & Offboard 

Email and open critical ports still most common ransomware vectors

Attacks are more aggressive and sophisticated

Can your third party pay? Will they pay? Do they have cyber insurance? Have they tested their policies and plans for IR?

How will you continue to operate if a key supplier is hit by ransomware?

Understand your data tree, who are your 4th parties? How are they being verified with your 3rd parties?

<h2> Panel Discussion: Adapting Security Strategies for the Modern Enterprise </h2>

Joan Ross - CIO @ Insight Cyber

Attacks are innovating at the same rate or faster than defense

So much of security ends up being taking care of vendor issues

Rick Doten - CISO @ Carolina Complete Health

Application security != Application vulnerability management, but instead a full lifecycle 

Business can put security at risk by wanting to be fast/efficient/cheap

Kelly Bissell - Security Lead @ Accenture 

Most of the biggest attacks are still taking advantage of bad hygiene 

We didn't invent the shipwreck, just the ship

<h2> Zero Trust Frameworks: The Major Approaches </h2>

ZT is;

Philosophy or set of principles based on a realistic assumption

A means to an end

Inclusive of many standards of security 

ZT is not limited to insider threats, or a single product (silver bullet)

Internal networks should be considered as vulnerable as internet facing networks/services

ZT is here to deal with the ever growing attack surface, the blurring of perimeter, helping deal with the inevitable intrusion.

NIST SP800-207 <https://csrc.nist.gov/publications/detail/sp/800-207/final>

1. All data sources and computing services - resources
2. All comm is secured regardless of network location
3. Access is granted on a per-session basis
4. Access is determined by a dynamic policy
5. Monitor/measure security posture of all assets at all times
6. Authentication and auth are dynamically and strictly enforced
7. Collect data about assets, infra, communications and analyze them 

Forrester ZTX (Costs $$$)

1. Data encryption - Encrypted data slows down attacks
2. Networks - Secure all networks the same
3. People - The weak link in security no matter what, insider threats are real. People have to adjust based on your policies and implementation 
4. Automation - You can automate your downfall without testing/auditing
5. Visibility - You can't stop what you can't see
6. Devices - Devices must be secure or they can wreak havoc
7. Workloads - Knowing what's happening and who is doing it

Google BeyondCorps <https://cloud.google.com/beyondcorp>

1. Managed Device - If you're not on the list, you aren't getting in
2. User Identification - The crux of all access 
3. Networks - Be aware of what's happening
4. Access Control - Only what you're allowed to, nothing else ever

<h2>Is Bug Bounty Right For You?</h2

The purpose of BB is to turn attackers into allies

Bug Bounties can be the signal of war, and you have to be prepared 

BB is not a pen test, nor is it supposed to be 

BB introduces the grey, and removes the "good" & "bad" (Imagine a 3rd party vuln is found, how do you solve it?)

Communicate with your internal teams, make them understand the why 

Who validates the finding? Communicates with the researcher?

Consider the whole lifeline of finding a bug, what happens next? Who is responsible for ensuring communication internally?

Review the findings, and consider the effect (Engage SOC/IR Team)

Policy/scope sets the rules of engagement

Before you start, make sure you take care of the low hanging fruit

Private BB is a thing, consider it

<h2> Misc. Notes </h2>

<https://cloudsecurityalliance.org/cxo-trust/>

<https://www.cisa.gov/cyber-essentials>