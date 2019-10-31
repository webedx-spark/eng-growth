### Holistic Ownership - Senior Software Engineer (L4)
In addition to the responsibilities of an L3, L4 engineers *demonstrate strong ownership *by:
* Owning complex components on the team and driving changes to make them simpler to understand and maintain. They make good trade-offs between supporting more varied use cases and making the system more complex.
* Taking ownership of failures around their component and drive solutions to prevent them from happening again.
* Maintaining strong ownership of their component by reviewing all changes to the component or specifying best practices others should observe when contributing to their component.
* Proactively making recommendations for their component to improve the health of the component.
* Maintaining component health by contributing fixes to upstream components that they don’t own while following the practices published by the owner.
* Managing debt strategically in their component in a measured way, isolating tech debt as needed.
* Contributing to the design and development of the team's components outside of their immediate responsibility.

Here are some examples of behaviors that L4s at Coursera have demonstrated:
* They advocated for ID verification (typing patterns) to be deleted due to low impact to Coursera business value and high maintenance cost.
* They had a P0 bug in their component, so they took ownership of the bug and drove changes to avoid repeating the same larger pattern of mistakes.
* They decoupled sessions code into a schedule service to make ownership of sessions clearer.
* They wrote a detailed document on Certificates architecture which had significant historical complexity and proactively recommended improvements to the whole system.
* They added isolated tech debt for a feature that was only used by UoL that was easy to maintain.
* They simplified their search infrastructure by considering all trade-offs including cost of maintenance and ease of use, and then using Algolia.
* They improved ownership of a monolith service on their team by making low-effort splits on the service, which resulted in better ownership.
* They improved code coverage and re-wrote parts of payments bundle by writing good quality tests, thereby increasing confidence in deploys.
* Though they are in the product team, they made a fix in assembler service by following the practices of the infrastructure team.
* They wrote fine-tuned monitors and alerts for the assessment system, helping us catch and fix issues before our users see them.
* They identified the technical and systemic problems preventing Android UI tests from being effective. Because the tests were slow, they were not being run frequently enough. They fixed the slowness issue by parallelizing the tests to make them run in 1/4th the time, and fixed the reliability of the tests by replacing flaky checks with more robust ones.
* They led an on-call training for new engineers on the team to exemplify how to deal with various alerts.
* They wrote API tests for workspaces to ensure that the contracts within workspaces are not broken.
* They own a component spanning mobile and backend, helping them ship a calendar sync feature across the stack showing considerable breadth.
* The own a component spanning frontend and backend, enabling them to design, estimate, and lead a project across the stack.
* They proactively worked with Marketing to set up launch guides and expectations for publishing new degrees.
* They worked closely with marketing to identify various different problems they were facing in sending push notifications and fixed them so that it became a reliable medium for retargeting.
* When working on an enterprise feature, they added good documentation to Confluence and worked closely with the Implementation Managers to make sure the launch is smooth for customers.
* They contributed to the design and development courservice components by splitting up the microservice even though they did not own many parts of it.
* When working on fixing availability for program-home, identify errors in monitoring and fix them.
* Work with infra to improve logging and debugging of graphQL errors so it’s easier to identify root cause of errors.
* Remove dependency on payments for some enterprise flows since it was identified as a source for errors and data inconsistency. When doing that, write a detailed doc on impact and get buy in from product.
* They helped estimate, sequence and identify blockers for multiple projects in the team including the ones they don’t directly own.
* They worked closely with data engineering and infra to fix critical data inconsistencies in the platform. They added appropriate monitoring and alerting to prevent these from happening in the future.
<hr>