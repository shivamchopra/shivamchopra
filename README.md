# Shivam Chopra

**Senior enterprise software engineer · C# / .NET · Enterprise modernization**

I work on enterprise software, APIs and distributed systems. My focus is maintainable design, reliable integration and clear architectural tradeoffs. I'm extending that foundation toward Azure/cloud architecture, trustworthy applied AI and broader solution architecture and technical leadership responsibilities.

## Featured Project

### [Enterprise Case Intelligence](https://github.com/shivamchopra/enterprise-case-intelligence)

My primary public technical project: a .NET 10 reference implementation exploring enterprise case modernization.

**EF Core Code First · durable, retry-safe case workflow.** Create, browse, retrieve and progress synthetic cases through an ASP.NET Core API backed by SQLite, with status filters and bounded pagination. Case changes and recorded history commit together and survive API restart with the same intact store.

Optional durable creation keys let a client recover the original creation result after a lost response or restart, without creating another case. Retrieving the case shows its current status.

C# models, Fluent API and scaffolded EF migrations define new schema. Explicit offline upgrades preserve retained cases, histories and creation keys. Older cases without history receive clearly labeled baselines; their earlier transitions are not reconstructed.

Domain unit tests, HTTP/SQLite integration tests and process-recovery tests cover the workflow, atomic writes and interrupted upgrades. CI checks formatting, Release builds, EF model/migration consistency and tests; architecture decision records explain the design choices.

This is a local demonstration using one API process and one SQLite file, with synthetic data only. Authentication, Azure deployment, event-driven integration and AI-assisted workflows remain future capabilities.

[Try the local workflow](https://github.com/shivamchopra/enterprise-case-intelligence/blob/main/docs/usage/local-case-workflow.md) · [Explore the code](https://github.com/shivamchopra/enterprise-case-intelligence/tree/main/src) · [Review the tests](https://github.com/shivamchopra/enterprise-case-intelligence/tree/main/tests) · [Read the architecture decisions](https://github.com/shivamchopra/enterprise-case-intelligence/tree/main/docs/adr)

## Current Focus

- Enterprise modernization and API/distributed-system design with C# / .NET.
- Azure/cloud architecture development and trustworthy enterprise AI integration.
- Solution design, architectural decision-making and technical leadership development.
