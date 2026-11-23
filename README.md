# Shivam Chopra

**Senior enterprise software engineer · C# / .NET · Enterprise modernization**

I work on enterprise software, APIs and distributed systems. My focus is maintainable design, reliable integration and clear architectural tradeoffs. I'm extending that foundation toward Azure/cloud architecture, trustworthy applied AI and broader solution architecture and technical leadership responsibilities.

## Featured Project

### [Enterprise Case Intelligence](https://github.com/shivamchopra/enterprise-case-intelligence)

I built this .NET 10 reference application to explore how a case moves from intake to closure. In the ASP.NET Core workspace, you can find a synthetic case, set its priority and move it through review. Once it closes, a deterministic brief cites the case status and the history entry that records when it closed.

EF Core Code First and SQLite keep case changes and their status history together. If a client loses the creation response, it can retry with the same key and recover the original result. A separate records intake command pulls closures from the local demo and saves receipts and a checkpoint in its own SQLite file, so the next run can resume where it stopped.

You can run the demo locally or configure OpenID Connect for Reader and Caseworker access. I verified both roles and session revocation locally with Microsoft Entra. Public hosting remains pending while I assess whether the deployment can run at $0 recurring out-of-pocket cost.

[Try the browser workflow](https://github.com/shivamchopra/enterprise-case-intelligence/blob/main/docs/usage/local-case-workflow.md#browser-workspace) · [Run the records intake](https://github.com/shivamchopra/enterprise-case-intelligence/blob/main/docs/usage/local-records-intake.md) · [Explore the implementation and tests](https://github.com/shivamchopra/enterprise-case-intelligence#current-implemented-scope)

## Current Focus

- Enterprise modernization and API/distributed-system design with C# / .NET.
- Azure/cloud architecture development and trustworthy enterprise AI integration.
- Solution design, architectural decision-making and technical leadership development.
