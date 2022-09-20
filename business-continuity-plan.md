# Business Continuity Plan

Cloud to Street's business continuity plan (BCP) outlines the processes used to continue or resume delivery of products and services after a disruptive event. The [incident response process](/incident-response.md) is one tool for ensuring business continuity.

### Backups

All production data that is required in order to deliver Cloud to Street's products should be backed up to a secondary, reliable data store.

### Outage detection

An incident could be detected internally by monitoring tools, by an employee in their course of work, or reported by a third party including customers.

### Outage response and remediation

If a suspected outage or other business continuity incident is detected, it should be responded to following the [incident response process](/incident-response.md).

### Example: Delayed production of flood maps

Consider the scenario where Cloud to Street has committed to a service-level agreement (SLA) requiring the delivery of flood maps within 2 business days of the acquisition of the necessary satellite imagery.

Cloud to Street should have:

1. backups of the flood maps and the systems required for the delivery of the flood maps
2. outage detection systems to identify when the creation of flood maps is at risk of being delayed 2 days
3. an employee who is on-call to respond to outages
