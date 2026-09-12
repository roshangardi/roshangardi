# Roshan Gardi

Hi, I'm Roshan, a software engineer at AWS working on safety and reliability for autonomous AI agents. I build guardrails for agents that run with real permissions, real data, and real budgets.

My day job is building permission governance and data protection into production AI agent platforms. It is the same engineering I spent years doing for cloud control planes: assume the component will misbehave, and bound what it can do, what it can access, and how much damage it can cause before you let it run.

## Projects

**[Levee](https://github.com/levee-ai/levee)** is my nights-and-weekends project: a Go proxy that sits between agents and LLM providers and enforces hard spending limits. It estimates the cost of each call before allowing it through and rejects calls when the agent has reached its budget. Actual costs settle afterward from provider usage numbers, with accounting kept in microdollars.

I record design decisions as ADRs and use the issue tracker to document known problems and open questions.

## Contributions

My current upstream focus is:

- **[Strands Agents](https://github.com/strands-agents/harness-sdk)** (`harness-sdk`), the sandboxing, hooks, interrupt, and cancellation paths.
- **[LangChain](https://github.com/langchain-ai/langchain)**, the agent middleware for controlling tool calls, protecting sensitive data, and requiring approval for higher-risk actions.

## Connect

[![LinkedIn](https://custom-icon-badges.demolab.com/badge/Roshan_Gardi-0A66C2?logo=linkedin-white&logoColor=white)](https://www.linkedin.com/in/roshangardi/)
[![Substack](https://img.shields.io/badge/AI_Under_Oath-FF6719?logo=substack&logoColor=white)](https://aiunderoath.substack.com)
[![Follow on GitHub](https://img.shields.io/badge/Follow-181717?logo=github)](https://github.com/roshangardi)
