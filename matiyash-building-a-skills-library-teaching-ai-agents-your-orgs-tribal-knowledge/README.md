# Building a Skills Library: Teaching AI Agents Your Org's Tribal Knowledge

Vitaliy Matiyash &mdash; *Staff Software Engineer, Builder, Problem Solver.*

- [LinkedIn](https://www.linkedin.com/in/VitaliyMatiyash/)
- [X (Twitter)](https://twitter.com/vitaliymatiyash)
- [Website](http://vitaliymatiyash.com/)

## Bio

Vitaliy Matiyash is Software Engineer from Columbus, Ohio, working on both front end and back end technologies with focus on web accessibility, Java and microservices. In his spare time he enjoys working on various DIY projects, biking, hiking Central Ohio trails and cooking from scratch.

## Abstract

AI coding assistants like GitHub Copilot are impressive at generating code. But ask one to "create a Jira story under the Platform epic with BDD acceptance criteria following our team's format" and it falls apart — because it doesn't know your org.

Over the past year, I've built and maintained a skills library — a structured collection of reusable knowledge modules that transform a general-purpose AI assistant into a domain-aware engineering partner. Each "skill" encodes a specific capability: how to call our Jira API, our Azure DevOps patterns, our production support runbooks, our API design standards, even our commit message conventions.

In this talk, I'll cover the architecture: the SKILL.md format (instructions + references + scripts + examples), how skills compose into agents (specialized personas with scoped tools), and how a single conversation can go from "implement this Jira ticket" to a pushed branch with tests — what we call the "one-shot" workflow.

I'll demo three real skills live: a Jira CLI skill that creates governed work items from natural language, a spec-driven development workflow that generates implementation plans from ticket descriptions, and a production support skill that knows our Kubernetes namespaces, API endpoints, and escalation paths.

We'll also cover the hard parts: preventing hallucinated API calls, enforcing guardrails (read-only in production), handling tool failures gracefully, and keeping skills maintainable as your systems evolve.

This pattern isn't GitHub-specific — it works with any agentic AI system. You'll leave with a template to start encoding your own team's knowledge into reusable, composable AI skills.

- **Level**: Intermediate
- **Tags**: AI - Dev Tools, Process & Delivery, Software Craftsmanship
