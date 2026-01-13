L1 analysts receive the alerts in a SIEM, EDR, or a ticket management platform. Most of the alerts are closed as False Positives or are handled on L1 level, but complex and threatening ones are sent to L2 that remediate most breaches.

To send the alerts further, we need to learn three new terms: reporting, escalation, and communication.

#Five Ws approach for report:

1) Who: Which user logs in, runs the command, or downloads the file
2) What: What exact action or event sequence was performed
3) When: When exactly did the suspicious activity start and ended
4) Where: Which device, IP, or website was involved in the alert
5) Why: The most important W, the reasoning for your final verdict

#Communication Cases

1) You need to escalate an urgent, critical alert, but L2 is unavailable and does not respond for 30 minutes.
Ensure you know where to find emergency contacts. First, try to call L2, then L3, and finally your manager.

2) The alert about Slack/Teams account compromise requires you to validate the login with the affected user.
Do not contact the user through the breached chat - use alternative contact methods like a phone call.

3) You receive an overwhelming number of alerts during a short period of time, some of which are critical.
Prioritise the alerts according to the workflow, but inform your L2 on shift about the situation.

4) After a few days, you realise that you misclassified the alert and likely missed a malicious action.
Immediately reach out to your L2 explaining your concerns. Threat actors can be silent for weeks before impact.

5) You can not complete the alert triage since the SIEM logs are not parsed correctly or are not searchable.
Do not skip the alert - investigate what you can and report the issue to your L2 on shift or SOC engineer.


