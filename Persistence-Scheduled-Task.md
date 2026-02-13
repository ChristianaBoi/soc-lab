Persistence Simulation - Scheduled Task

Technique: MITRE ATTACK T1053

Description:
A scheduled task was created using schtasks.exe to simulate persistance.

Evidence:
Process execution of schtasks.exe observed
Task file creation confirmed
Events logs recorded task creation activity

SOC Analysis:
This behaviour indicates persistence via Windows Scheduled Tasks, a common attacker technique to maintain access to a system.

Conclusion:
No malicious payload executed. Activity was part of a controlled lab simulation.
