# Holistic Ownership

## Why does holistic ownership matter?
We believe in team [ownership](https://martinfowler.com/bliki/CodeOwnership.html) and it is important for teams to have control over the quality and impact of their product areas. Strong ownership also helps us scale our organization as independent teams become strong owners of their components. Holistic ownership matters because it is important to think about all aspects of ownership that eventually help us drive business value for Coursera.

Managing many aspects of a domain is key to demonstrating holistic ownership. **Good quality** encompasses both functional correctness and meeting service-level objectives (SLO) like availability and latency requirements. In addition, setting explicit **interfaces and guidelines** for other engineering teams ensures that these teams can take the optimal route to unblocking themselves, while respecting the practices of the domain owner. More broadly, **documenting** the areas of ownership reduces bus factor risk, which is an important factor in component health. Finally, strong owners will be effective at **estimating timelines** for their product areas, which allows them to effectively drive a **long-term vision** for the component.

## Which [engineering values](https://webedx-spark.github.io/eng-values/) and/or [leadership principles](https://coursera.atlassian.net/wiki/spaces/PEP/pages/268763323/Coursera+Leadership+Principles) align with this category?
*Engineering values*
* **Maximize impact: use debt strategically** -- though we may choose to incur some technical debt when it makes sense for the business, this should be a conscious, informed choice backed by knowledge of the consequences. Along the same lines, strong ownership means we should flag debt, especially when it affects velocity.
* **Seek clear ownership: aim for clear and quantified ownership** -- ownership extends beyond just code work. As part of being a strong owner, we should seek appropriate bus factor, and if a component is not in a good state, we should either rebuild healthy ownership or deprecate the component.
* **Decide and commit: turn decisions into actions** -- as part of turning decisions into actions, we need to communicate the execution plan and keep stakeholders informed, which are important aspects of holistic ownership.
* **Make quality a habit: write valuable tests** -- though much of this value aligns with technical excellence, a strong owner will maintain both the production code and the associated tests, in order to ensure that they stay valuable. This can involve fixing flaky tests.

## What does progression look like?
As levels progress, the following dimensions improve:
* **Maintainability:** as you grow, you will make components you own easier to maintain, e.g. guarding against regressions via automated tests instead of manual testing. In this way, you are able to effectively own more components.
* **Complexity****:** advanced engineers will own and manage more complex parts of the Coursera system. Wherever possible, they minimize the complexity of solutions to problems with many complex concerns.
* **Proactiveness:** greater proactiveness about the health of the component allows us to address problems with them before they become urgent, which reduces both user impact and interruptive, reactionary work. Includes awareness of health indicators like bus factor, being able to effectively knowledge transfer.
* **Organizational impact**: mature engineers are able to manage broader areas of ownership, with concerns spanning multiple teams or engineering at large.
* **Breadth:**** **with the ability to work cross-stack or to dive into new areas of code, engineers with greater breadth are better able to contribute to areas that are not directly owned while following best practices of ownership. This ability allows them to independently resolve upstream issues, which in turn helps them maintain the health of their own components.
<hr>