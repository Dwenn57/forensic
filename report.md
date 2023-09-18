<h1>Introduction</h1>

<p>The purpose of the project is to teach us how to work with a vulnerable virtual machine. Therefore, we must:
Set up the VM: which should contain a known and exploitable vulnerability.
Exploit it: by replicating a proof of concept (POC).
Analyze the exploitation evidence: by examining the logs generated during the attack.
Fix the vulnerability/Enhance the defenses of the vulnerable machine.
For my part, I chose to set up a WordPress site on a Windows 7 machine. (All resources are provided at the end of the report in the "Resources" section.) You will find links to the OVA file of the exploited machine as well as snapshots (before and after exploitation). This machine is attacked by a Kali Linux machine.</p>

La CVE choisie est la suivante : 
<br><li>
CVE-2020-9043
Description : Improper Access Control Lead to Privilege Escalation
Plugin affecté : wpCentral
Version du plugin :  ≤ 1.5.0
CVSS Score : 8.8</li>

test
