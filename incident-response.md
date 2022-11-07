# Incident Response

Cloud to Street's customers are dependent on our services operating as normal. Our incident detection and response practices support the confidentiality, integrity, and availability of our services.

### Incident detection

An incident may be detected by any employee in their course of work. Incidents may also be reported by end users and other third parties.

All Cloud to Street employees should report suspected incidents affecting confidentiality, integrity, or availability of our services. Incidents can be reported to the Slack channel [#eng-crossteam](https://cloudtostreet.slack.com/archives/C019BM0G9K6).

Cloud to Street reviews and responds to potential third-party reports of security issues to [support@cloudtostreet.info](mailto:support@cloudtostreet.info) promptly.

### On-call rotations

Cloud to Street should use on-call rotations to ensure that someone is available to respond to urgent system issues.

### Incident response and remediation

If a suspected incident is detected, it should be responded to following the incident response process. Detailed employee-only internal documentation on the process is available [here](https://cloudtostreet.atlassian.net/wiki/spaces/PT/pages/577765385/Incident+Response+SEVs+and+Post+Mortems).

An overview of the process is provided below for external purposes:

1. When any employee discovers the incident, they report it via Slack to the Slack channel [#eng-crossteam](https://cloudtostreet.slack.com/archives/C019BM0G9K6). The engineering on-call member is responsible for responding to these incidents.
2. The on-call assesses and validates the accuracy of the reported incident. If the on-call is unable, they assign another person to investigate.
3. If the on-call confirms that the incident merits immediate remediation, they escalates the issue in a process known as "opening a SEV." The on-call is the "SEV owner" unless they delegate this responsibility to someone else who is better suited to managing the incident.
4. The SEV owner creates a new Slack channel for the purpose of addressing the incident. All members of the engineering team and anyone across the company who could assist in addressing the incident is added to the channel.
5. In the channel, the SEV owner explains their understanding of the severity of the SEV, coded as SEV 1: critical, SEV 2: major, or SEV 3: minor.
6. The SEV owner is responsible for ensuring that progress is being made in mitigating the issue.
7. After the incident has been mitigated, the SEV owner drafts a post mortem document, solicits edits and contributions from others involved in the incident, and then schedules a post mortem meeting.
8. In the post mortem meeting, the timeline and impact of the incident are reviewed. High priority and low priority follow-up tasks are identified. The high priority follow ups must be addressed in a timely manner.
9. When all high priority follow ups are completed, the SEV can be closed. The SEV owner does this by changing the SEV status in the SEV Slack channel.
