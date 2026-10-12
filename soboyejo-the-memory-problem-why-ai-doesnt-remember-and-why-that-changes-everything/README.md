# The Memory Problem: Why AI Doesn't Remember and Why That Changes Everything

Sho Soboyejo &mdash; *Life Learner, Technologist, Speaker & Machine Learning Practitioner*

- [LinkedIn](https://www.linkedin.com/in/shofola)
- [X (Twitter)](https://twitter.com/ShoReason)
- [Website](http://www.shoreason.com)

## Bio

Synthesizing information and making connections is at the heart of most of what I do. I love connecting the dots across so many domains.

From building apps that focus on connecting people and their data to writing articles or speaking at conferences, I use any medium at my disposal to achieve this aim.

You can catch me in my free time using SciKit Learn and PyTorch to tackle NLP challenges. The only thing that tops that is spending time being a husband and father of three amazing kids

## Abstract

Every AI demo is impressive on the first pass. However, production deployment eventually hits one key question: “How does it remember what I need it to?”

Much of this is really a consequence of the architecture. LLMs can reason remarkably well within a context window but they don't accumulate knowledge or trust over time. On the other hand, users are increasingly expecting exactly that.

At Breadkrumb, an AI-powered travel platform, memory is core to our architecture. Building that in production surfaced problems no demo prepares you for. An agent's own suggestions nearly leaked into “user preference” through a feedback loop. A retention policy quietly deleted the evidence a key metric depended on. And memory without visibility eroded trust faster than no memory at all.

The lesson? Memory isn't storage, it is policy.

From RAG, to vector stores, to knowledge graphs, and persistent user models. They all are complementary patterns for different memory problems.

This talk offers a practical framework for evaluating memory across three dimensions:

- Identity (who or what is being remembered and who may access it)
- Continuity (what persists vs expires)
- Trust (how memory is earned and gets surfaced)

Whether you're building agents, copilots or AI-native applications, this session will help you move beyond demos and think more rigorously about systems that don't just generate better answers, but build continuity and trust over time.

- **Level**: Introductory and overview
- **Tags**: Career Growth, Leadership
