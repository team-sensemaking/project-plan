# Project Coevolution - Project Plan

Team Sensemaking, 2016-08-05

## Project Goal

Create an internal tool to share and manage data for Fiserv. This tool will by developers and testers to increase productivity when managing different environments.

## Major Capabilities

- Store internal app credentials, URLs, notes, etc. for each bank.
- Search using keywords.
- Edit or flag outdated information.
- Ensure Mobile Friendly. Look up data on mobile screens. Hence, it needs to be responsive and work with a resolution >=480x800.

## Backlogs

Our backlogs can be found on [Favro](https://favro.com/organization/9a8d7cde93cfc910cfff3f87/f99db07e3a605fd307e43513). The product backlog is in priority order.

## Git Repo

https://github.com/Ofekw/internal-data-share

## Meeting Times

Customer always available over group Skype chat.

Official planning and review meetings with the customer on Mondays at midday. Standups Friday morning, retrospectives Friday afternoon. This makes our sprint period Monday to Friday.

## Practices Used

- Sprints
- Sprint planning
- Sprint reviews
- Sprint retrospectives
- Weekly standups
- Product and sprint backlogs
- Pair programming
- Code standards
- Code reviews
- Test driven development

## Risk Assessment

Risk | Likelyhood | Severity | Mitigation | Response
---|---|---|---|---
Compatibility issues | Low | Medium | Communication with customer to understand their systems, test on all browsers, use highly supported technologies. | Adapt solution to their system.
Misunderstanding customer goals | Medium | Low | Stay in communication with customer to clarify ambiguity. | Face to communication when needed.
Customers misunderstanding their own goals | Low | High | Constantly verify requirements to make sure they know what they want. | Be prepared to adapt product to shifting requirements
Scope creep | High | High | Prioritised backlog, ensure customer understands how much work we are able to commit. | Work with customer so that they understand the situation.
Codebase maintainability issues | Medium | High | Stick to coding standards, define team standards. Pair programming, code reviews so that multiple people understand codebase. | Refactor or rewrite the code.
Performance/scalability issues | Medium | Low | Clarify expected use case (amount of users etc.) | Identify and address bottlenecks
Deployment issues | High | Low | Test on production environment early. | Adapt infrastructure to support customer environment.
Internal team conflicts | High | Medium | Team building activities, pub trips. | Mediate with lecturers if required.
Issues with new technologies | High | Medium | Use spikes (throw away code people used to learn with). | Have the courage to change technologies if they are not working for us.
Lost work due to technical issues | Low | Low | Distributed version control. Good git workflow. | Restore from local copies of repos.

## Tentative Roles in Team

Member  | Role
--- | ---
Dean    | Backend
Ofek    | Frontend
Frano   | Backend
Patrick | Backend
Greg    | Frontend
Saren   | Frontend
Yubo    | Frontend
Alex    | Backend
