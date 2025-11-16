# CTI_Assignment_Keshav_Prashar

Task 3: Extract Diamond Model Elements
Vertex	Information
Adversary	AeroBlade
Infrastructure	During the 2022–2023 campaigns, AeroBlade used a C2 infrastructure. Anonymous domains and IPs accessed over port 443 are two examples. "Network Infrastructure: C2 server on port 443" is evidence.
Capability	Weaponized Word documents, remote template injection (T1221), VBA macros, DLL reverse shell, anti-disassembly, API hashing, anti-sandbox checks, AES-encrypted static configuration, and persistence via Task Scheduler are just a few of the advanced techniques used by AeroBlade. Proof: "A DLL that functions as a reverse shell is the ultimate payload. Strongly encoded, anti-disassembly, encrypted static setup perseverance via Task Scheduler."
Victim	The primary victim is the U.S. aerospace industry, specifically one aerospace company in the United States. Evidence: “targeting an aerospace industry company in the U.S.” and “Targets: Aerospace industry in the United States.”

Task 5: Threat Actor Profile Summary
AeroBlade Threat Actor – Profile Summary

BlackBerry founded AeroBlade, a previously unknown threat organization that has been active since September 2022 and has been seen to continue expanding its toolkit through mid-2023. The U.S. aerospace industry was the target of both attack waves, suggesting that it was a focused and persistent approach that was probably driven by campaigns. The attack was majorly happened through spear-phishing emails, the operator distributed weaponized Microsoft Word documents that downloaded on the systems and ran a covert custom DLL reverse shell by using encoded VBA macros and remote template injection.

Its payload was already displaying sophisticated anti-analysis features that enabled the avoidance of detection by utilizing such techniques as control flow hidden API hashing, and bespoke sandbox detection routines.The continuous improvement and levels of investment in the operator indicate that the attacks were continuously being enhanced and that it was operated by a well-funded team.

The campaign's specialty and the complexity of its tradecraft suggest a group committed to stealing competitive or sensitive commercial intelligence from American aerospace targets, however connection is still unknown.

Task 6: Reflection Questions
How does the Diamond Model help in understanding threat actors?

It breaks down an incident into four parts: attacker, victim, capabilities, and infrastructure. Which makes the users visualize relationships and explain the way each component is related to another.

What challenges did you face in identifying each vertex?

The hardest thing was attribution since the opponent in the report is unknown with little information, other than details of activities. Infrastructure and capability also had some overlap, tools (such as malicious docs) are hosted on enemy infrastructure.

How could this model support proactive defense strategies?

By determining the actions of attackers, defenders are able to discover an attack path, which occurs repeatedly, such as spear-phishing or conservative C2 communication characteristics, prioritize defenses by their importance (such as hardened email gateways, macro blocking, and effectiveness of egress restrictions), and detect indicators of any such activity in their own networks.
