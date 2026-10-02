<div align="center">
  <a href="https://www.mindovermachine.dk">
    <img src="https://raw.githubusercontent.com/mindovermachine-dev/docs.mindovermachine/main/astro/src/assets/mom-logo-text-transparent.png" alt="Mind over Machine logo" width="400"/>
  </a>

  <h1>Mind over Machine</h1>
  <p><em>The Foundation for Regenerative Software Development</em></p>

  [![Documentation](https://img.shields.io/badge/docs-mindovermachine.dk-blue?style=flat-square)](https://docs.mindovermachine.dk)&nbsp;
  [![Documentation](https://img.shields.io/badge/www-mindovermachine.dk-green?style=flat-square)](https://www.mindovermachine.dk)&nbsp;
  [![Documentation](https://img.shields.io/badge/mindovermachine-matrix.org-red?style=flat-square)](https://matrix.to/#/#mindovermachine:matrix.org)

</div>

---

## What We Are

**Mind over Machine** is a combined **think tank**, **laboratory** and **Community of Practice**.

We are a not-for-profit commercial foundation — registered as such ([DK46659287](https://datacvr.virk.dk/enhed/virksomhed/46659287)) with the Danish Business Authority and recognized as such by the department of civil affairs under the Danish Ministry of Justice. Consequently, our Software Foundation is eligible as [**OSS Stewards**](https://www.mindovermachine.dk/writings/why-oss-stewardship/) as the role is defined in EUs' Cyber Resilience Act.

Based on long-term systems thinking, we explore and test principles and techniques that can turn software and development processes into regenerative systems. **Regenerative** defined as a complex system in balance, one that doesn't run wild and the doesn'ty slow down. Like a balanced ecosystem.

- **The Think Tank** 
  - Reachable on: [hey@mindovermachine.dk](mailto:hey@mindovermachine.dk)
  - Vocal on: [www.mindovermachine.dk](https://www.mindovermachine.dk)
- **Community of Practice**
  - Reachable on [`#mom-office-hours:matrix.org`](https://matrix.to/#/#mom-office-hours:matrix.org)
  - Vocal on: [mindovermachine.dk/events](https://www.mindovermachine.dk/events)
- **Laboratory**
  - Reachable on: [`#mom-tech-talks:matrix.or`](https://matrix.to/#/#mom-tech-talks:matrix.org)
  - Vocal on: [docs.mindovermachine.dev](docs.mindovermachine.dev)

In the Laboratory, we develop concrete Open Source Software systems and serve as formal _OSS Steward_ for the code that is supported by our [**MoM FOSS Alliance**](https://www.mindovermachine.dk/membership/). As a member of this alliance you can support our work and also uti our staff and Community of Practice .

## Our Mission

**To search for and spread a new model for how software can contribute to a regenerative paradigm, which overall contributes _positively_ to people and the world.**

Are you a software developer — or someone operates in the realm of software development — then ask yourself this:

> _"Am I part of the Solution? or am I part of the problem?"_

We strive toi give software developers — and those who depend on software developer's work — a set of tool and principles where everyone can answere clearly – _"Solution! ...I'm par of the solution!"_
We aim to create value, and expand the term to _also_ include the value that is not priced in conventional economic models — the value software creates for **society**, **organizations**, **companies**, **end-users** and **developers** alike.

## Our Principles

- **We reject manipulative models** that consider end users as a product to be exploited.
- **We eliminate digital waste and technical debt** through end-user involvement, accessibility, high quality, and conscious generic and reusable design.
- **We build systems that serve people's general needs** rather than commercial interests. We believe in transparency and integrity.
- **Software is part of people's cultural heritage**, not just companies' intellectual property. The systems and knowledge we develop are Open Source and CopyLeft.
- **We improve the personal experience of developing software** — not only with a focus on capital interests, but on people's lived lives.
- **Long-term systems thinking** is prioritized over short-term or immediate benefits.

## How We Work

We practice and advocate for a set of modern, regenerative software development methods:

| Practice | Description |
|----------|-------------|
| **No Estimates** | Deliver value continuously rather than spending time on inaccurate predictions |
| **Trunk-based Development** | All developers commit to a shared branch daily; the trunk is always ready for release |
| **Shift Left** | Quality control and testing happens early, directly at the source |
| **Participatory Design** | End users are actively involved in the design process |
| **Collaboration with AI Agents** | AI agents work alongside developers under the same strict quality standards |
| **Individually Releasable Components** | Small, independent components that can each be developed, tested, and released separately |
| **Open Source** | All our work is open and available for anyone to _study, use, modify, and share_ |
| **Configuration Management** | All of development environments, test-data, dependencies, deploys, releases and documentation is locked in and stable |


## Open Source stewardship

The FOSS projects we drive are run by the same standards, ensuring that moving from one project to another feels completely familiar. Here are the standards you can expect from all `matured` FOSS projects we steer:

- [x]   **Semantic Versioning:** Strict adherence to Semantic Versioning (SemVer) for predictable releases.
- [x]   **Containerized Development:** Development environments are containerized (typically utilizing Dev Containers or similar setups).
- [x]   **Containerized Pipelines:** CI/CD pipelines are containerized and fully executable directly from within the local development environment (supporting a true shift-left paradigm).
- [x]   **Trunk-Based Development:** Full support for trunk-based development (Pull Requests are supported and welcomed, but optional).
- [x]   **Non-Blocking Reviews:** Support for non-blocking reviews (reviews are enabled and required for formal releases, but not for merging to the trunk).
- [x]   **Full Traceability:** All commits on `main` are tied to tracked issues, and all generative AI chats/results utilized in development are fully documented and tied to issues.
- [x]   **Agentic AI Ready:** Comprehensive support for Collaborative Agentic AI through rich, actionable, and structured instructions, skills etc.
- [x]   **Cryptographic Security:** Built-in support and requirement for GPG-signed commits.
- [x]   **Detroit-Style Testing:** A strong preference for "Detroit school" (classical/stateful) unit testing over a mock-heavy "London school" approach. This ensures tests are stable, intuitive, and level the playing field for both humans and AI agents.
- [x]   **Managed Test Data:** All test data required to run the test suite is actively maintained, stable, and version-controlled.
- [x]   **Highly Componentized:** Codebases are highly modular, actively striving for feature-completeness to support low-cost stewardship and prevent "token-run-wild" budgets on bloated codebases.
- [x]   **Open Project Management:** Projects are managed openly using an upstream Kanban board (representing the roadmap) and downstream boards (designed to minimize Work in Progress).
- [x]   **Dedicated User Voice Channels:** A dedicated end-user voice channel is always available (typically GitHub Discussions), paired with a clear, active issue-assignment workflow.
- [x]   **Modern Distribution:** Built-in support for seamless installation via standard package managers.

## Finding your way around on our GitHub organization.

Our organization works as _one big pile_ of all repositories. To make sense of it all you can filter on repo properties:

### Product lines
A custom repo property `Product` is set on repos that are included in a specific controlle project. To use this filter, in the [repository search bar](https://github.com/orgs/mindovermachine-dev/repositories) a list of valid options will show as dropdown when you type:

```
props.Product:
```
Examples:

- [`Decision Driven Design`](https://github.com/orgs/mindovermachine-dev/repositories?q=props.Product:"Decision+Driven+Design")
- [`Takt`](https://github.com/orgs/mindovermachine-dev/repositories?q=props.Product:"TakT")
- [`Policy System`](https://github.com/orgs/mindovermachine-dev/repositories?q=props.Product:"Policy+System")

### Maturity level
To prevent market confusion between experimental code and production-grade tools, every repository is categorized with a `Maturity` grade.

To use this filter, in the [repository search bar](https://github.com/orgs/mindovermachine-dev/repositories) a list of valid options will show as dropdown when you type:

```
props.Maturity:
```

- [**Mature**](https://github.com/orgs/mindovermachine-dev/repositories?q=props.Maturity:Mature) Full MoM standards enforced, CRA Article 24 Compliant (OSS Steward).
- [**Incubating**](https://github.com/orgs/mindovermachine-dev/repositories?q=props.Maturity:Incubating)  Active development, most MoM standards implemented. Released for field testing (Beta).
- [**Experimental**](https://github.com/orgs/mindovermachine-dev/repositories?q=props.Maturity:Experimental)  Experimental	lab	Internal experiments. MoM standards may apply - or they may not. R&D code released for friendly testing (Alpha)
- [**Exploring**](https://github.com/orgs/mindovermachine-dev/repositories?q=props.Maturity:Exploring)  Unknown state, no promises made, most likely not released (Default).

## Onboarding

You are more than welcome to join ranks and participate. Easiest approach is:

1. Find us on Matrix [`#mom-general:matrix.org`](https://matrix.to/#/#mom-general:matrix.org) (New to Matrix? - start [here](https://www.mindovermachine.dk/writings/new-to-matrix))
2. Join our weekly open [office hours](https://www.mindovermachine.dk/events/mom-officehours/) (Tuesdays 8:15  CET) Open to all, great way to be introduced to the Foundation!
3. Join our weekly open [tech talks](https://www.mindovermachine.dk/events/mom-techtalks/) (Thursdays 13:00 CET) Open to all, a great way to be onboarded as contributor to our code base.


