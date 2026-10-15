# Awesome-AI-Coding-Agent-Orchestration

# Top AI Coding Agent Orchestration Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Agent Fleets, Lifecycle Hooks, Campaign Orchestration, CI/CD + Coding Agents & Multi-Agent Coordination*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Coding Agent Orchestration**. These systems coordinate one or many coding agents—managing sessions, parallel work, lifecycle hooks, skills, quality gates, and delivery into existing CI/CD and developer workflows.

**Examples** include Harness, GitLab AI, GitHub Actions, CircleCI, TeamCity Cloud, Azure DevOps, Bitbucket Pipelines, Octopus Deploy, Codefresh, and Jenkins Enterprise (the category leaders in pipeline and delivery orchestration, increasingly extended with AI agents).

**Open-source emphasis**: Orchestrating coding agent fleets is an emerging open area. **Citadel**, **OpenHands**, and related harnesses provide lifecycle hooks, skills, parallel agents, and campaign persistence without proprietary lock-in. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Harness](https://www.harness.io/)**  
  Modern software delivery platform with CI/CD, feature flags, and growing AI-assisted orchestration capabilities for pipelines and agents.

- **[GitLab AI / GitLab CI](https://about.gitlab.com/)**  
  Integrated DevSecOps platform combining pipelines, AI features, and merge-request workflows that can host and trigger coding agents.

- **[GitHub Actions](https://github.com/features/actions)**  
  Native CI/CD and automation on GitHub; widely used to run coding agents, PR bots, and multi-step AI workflows on repository events.

- **[CircleCI](https://circleci.com/)**  
  Cloud CI/CD platform that teams extend with AI coding agents and automated quality/repair jobs in pipelines.

- **[TeamCity Cloud](https://www.jetbrains.com/teamcity/)**  
  JetBrains CI/CD server (cloud and self-hosted options) used to orchestrate builds, tests, and agent-driven steps.

- **[Azure DevOps](https://azure.microsoft.com/en-us/products/devops)**  
  Microsoft’s pipelines, boards, and repos platform; commonly used to schedule and govern AI coding agent workloads.

- **[Bitbucket Pipelines](https://bitbucket.org/product/features/pipelines)**  
  Atlassian’s CI/CD offering integrated with Bitbucket repositories for running automated and agent-based workflows.

- **[Octopus Deploy](https://octopus.com/)**  
  Deployment automation platform focused on release orchestration; can sit downstream of agent-produced artifacts.

- **[Codefresh](https://codefresh.io/)**  
  Kubernetes-native CI/CD and GitOps platform used to orchestrate complex delivery pipelines that may include AI agents.

- **[Jenkins Enterprise / CloudBees](https://www.cloudbees.com/)**  
  Enterprise distributions of Jenkins for large-scale pipeline orchestration, increasingly extended with AI-assisted jobs.

## Open-Source GitHub Projects
- **[Citadel](https://github.com/SethGammon/Citadel)**  
  Open-source agent orchestration harness for Claude Code and Codex — orchestrates coding agent fleets with lifecycle hooks, skills, campaign persistence, parallel worktrees, and quality gates.

- **[OpenHands](https://github.com/OpenHands/OpenHands)**  
  Open-source platform for running autonomous coding agents end-to-end (plan → code → test → PR), with self-hosted control and multi-agent support.

- **[Aider](https://github.com/Aider-AI/aider)**  
  Open-source terminal coding agent; often orchestrated via scripts or CI for repeated, scoped coding tasks.

- **[OpenCode](https://github.com/anomalyco/opencode)**  
  Open-source coding agent with terminal and desktop surfaces that can be driven as part of larger orchestration setups.

- **[Cline](https://github.com/cline/cline)**  
  Open-source coding agent with headless/CLI modes suitable for CI and scheduled agent runs.

- **[SWE-agent](https://github.com/SWE-agent/SWE-agent)**  
  Open-source agent designed to solve GitHub issues autonomously; typically orchestrated per-issue or in batch campaigns.

- **[Temporal](https://github.com/temporalio/temporal)**  
  Open-source durable workflow engine frequently used to orchestrate long-running agent campaigns and multi-step coding pipelines.

- **[Prefect](https://github.com/PrefectHQ/prefect)**  
  Open-source workflow orchestration for Python that can schedule and monitor coding agent jobs and fleets.

- **[Argo Workflows / Argo CD](https://github.com/argoproj/argo-workflows)**  
  Kubernetes-native open-source workflow and GitOps tools used to run and deploy agent-produced changes at scale.

- **[Documentation and harness guides](https://sethgammon.github.io/Citadel/)**  
  Resources on lifecycle hooks, fleet coordination, skills, and operating coding agents as a controlled system.

### Additional Strong Open-Source Options
- Full fleet + lifecycle orchestration with **Citadel** on top of Claude Code or Codex.
- Autonomous end-to-end coding loops via **OpenHands**.
- Wiring open agents into **GitHub Actions**, **GitLab CI**, or self-hosted Jenkins/Argo pipelines.
- Using **Temporal** or **Prefect** as the durable control plane for multi-agent campaigns.
- Combining worktree isolation, discovery sharing, and quality hooks for safe parallel agents.
- Accepting that commercial CI/CD and delivery platforms (Harness, GitLab, GitHub Actions, CircleCI, Azure DevOps, etc.) still lead in enterprise scale, compliance, and turnkey pipeline management.

**Frameworks for building custom systems**: Install **Citadel** (or similar harness) → define skills and lifecycle hooks → run single agents or parallel fleets → feed results into open or commercial CI/CD. Suitable for teams that want durable, observable coding agent campaigns. Many organizations still orchestrate agents primarily through existing commercial pipeline platforms.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Orchestrated coding agents can modify code and trigger deployments. Use isolation (worktrees/sandboxes), approvals, and tests. This list is not security or operations advice.

---
**Made for platform engineers, agent operators, and open-source builders.**
Let's keep coding agent orchestration reliable, observable, and as open as practical.
