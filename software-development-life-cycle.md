# Software Development Life Cycle

The Cloud to Street software development life cycle follows a plan, build, test, deploy, maintain cycle.

### Planning

Planning is conducted ad hoc depending on the scope of the change. Developers should write implementation plans for larger changes. Implementation plans should be reviewed by the engineering team and relevant stakeholders before proceeding with a project.

### Build & test

In the "build" and "test" phases, developers make commits to feature branches using Git. Developers then open a pull request on GitHub.

Pull requests must describe how the author tested the change. Pull requests that change production services require review and approval by at least one other developer before they can be merged into the main branch.

Continuous integration tests run on every pull request. Developers should not merge a pull request that has failing continuous integration tests. The feature or the test should be corrected before merging. In exceptional circumstances, such as when it is necessary to fix an urgent production bug, developers may merge a branch that has failing continuous integration tests.

### Deploy

Services are deployed either automatically through a tool like GitHub Actions or triggered manually by a developer.

### Maintain

Services should be maintained through monitoring and alerting tools, like Sentry or GCP Cloud Error Reporting. Alerts from these services should be triaged by the engineering on-call member.
