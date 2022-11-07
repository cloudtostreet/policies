# Change Management

All changes to production systems, such as changes to service deployments, cloud configuration, database migrations, and provisioning of cloud infrastructure, should be assessed as part of the change management policy.

Cloud to Street employees who intend to make such a change must first assess the risk. Unless otherwise noted, routine changes can be considered "low risk," and need no approval from the rest of the team. For higher risk changes, such as database migrations that could result in downtime or data loss, developers should confer with a tech lead, their manager, or a peer developer before performing the change.

Developers performing a high risk change should take reasonable steps to limit downtime, data loss, and other forms of business interruption. Some steps might be:

- Ensure that a backup of the data is available
- Ensure that the changes can be rolled back quickly
- Inform internal and external users who may be affected by the change
- Perform the change during off-peak hours where users are less likely to be affected by the change
- Perform the change in a staging environment first
