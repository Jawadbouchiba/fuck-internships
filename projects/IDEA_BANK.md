# Project Idea Bank

Use this bank when you want concrete ideas to build quickly.

## Community idea submissions (add your own)

Anyone can add ideas to this file through a PR.

### Submission steps

1. Fork the repo and create a branch.
2. Copy the template in **Idea entry template** below.
3. Add your idea under the correct section (`CS + Software Engineering` or `Cybersecurity`).
4. Use a new ID:
   - `IB-CSSE-XX` for CS + Software Engineering
   - `IB-CY-XX` for Cybersecurity
5. Open a PR titled `Add idea: <your idea title>`.
6. In the PR description, include:
   - problem this idea solves,
   - why it is beginner/intermediate/advanced,
   - what proof a contributor can show after finishing it.

### Idea quality checklist (required)

- [ ] Clear scope for first PR
- [ ] Concrete deliverable list
- [ ] Evidence/portfolio output is explicit
- [ ] Useful to students in real job preparation
- [ ] Safe, legal, and ethically appropriate

### Idea entry template

```md
### IB-<TRACK>-<NN>: <Idea title>

- Level: L1 / L2 / L3
- Build: <What contributors are building>
- First PR: <Small first deliverable>
- Next PRs: <How contributors can expand it>
- Evidence: <What they can show recruiters>
- Skills: <Top skills demonstrated>
```

## How to use this file

1. Pick one idea with scope you can finish.
2. Open an issue using the idea title and ID.
3. Keep first PR small (single deliverable).
4. Expand in follow-up PRs.

## CS + Software Engineering ideas

### IB-CSSE-01: Algorithm visualization docs pack

- Level: L1
- Build: interactive or static walkthrough of sorting/search algorithms.
- First PR: one algorithm page with complexity + edge cases.
- Next PRs: add tests, examples, and benchmark comparison.
- Evidence: merged docs PR + complexity notes + sample walkthrough output.
- Skills: technical communication, algorithmic reasoning.

### IB-CSSE-02: Bug-to-test challenge set

- Level: L1-L2
- Build: small bug scenarios where each fix requires a regression test.
- First PR: create one reproducible bug scenario + one fix.
- Next PRs: add more scenarios and testing patterns.
- Evidence: bug reproduction + passing regression test.
- Skills: debugging, testing discipline.

### IB-CSSE-03: API reliability starter kit

- Level: L2
- Build: API skeleton with health checks, validation, and error handling conventions.
- First PR: add one endpoint + validation + tests.
- Next PRs: observability, rate limits, and docs.
- Evidence: test output + endpoint usage examples.
- Skills: API engineering, reliability mindset.

### IB-CSSE-04: CI pipeline hardening

- Level: L2
- Build: robust CI checks (lint, test, docs quality).
- First PR: introduce one missing check.
- Next PRs: optimize runtime, add caching, improve failure messages.
- Evidence: CI workflow run showing added check.
- Skills: DevOps workflow, automation.

### IB-CSSE-05: Refactor lab

- Level: L2-L3
- Build: focused refactor examples with before/after quality explanation.
- First PR: refactor one function/module and add tests.
- Next PRs: document patterns and anti-patterns.
- Evidence: maintainability before/after summary + regression-safe tests.
- Skills: code quality, maintainability.

## Cybersecurity ideas

### IB-CY-01: Secure coding playbook

- Level: L1
- Build: vulnerability prevention checklists (auth, input validation, secrets).
- First PR: one category with examples and mitigations.
- Next PRs: add language/framework-specific variants.
- Evidence: guideline page + vulnerable vs safe pattern examples.
- Skills: secure coding awareness.

### IB-CY-02: Threat-model template toolkit

- Level: L1-L2
- Build: easy template for identifying assets, threats, and mitigations.
- First PR: base template + one filled sample.
- Next PRs: multiple project examples and review rubric.
- Evidence: filled threat model artifact.
- Skills: risk analysis, threat modeling.

### IB-CY-03: Dependency risk monitor workflow

- Level: L2
- Build: guidance + workflow for dependency scanning and triage.
- First PR: basic scan integration docs.
- Next PRs: triage automation and severity response playbook.
- Evidence: sample vulnerability triage record.
- Skills: security operations, prioritization.

### IB-CY-04: Security review challenge issues

- Level: L2
- Build: issue set with intentionally weak patterns to audit.
- First PR: one challenge issue with expected findings format.
- Next PRs: add remediation walkthroughs.
- Evidence: audit report + remediation suggestion.
- Skills: code review, vulnerability identification.

### IB-CY-05: Incident response mini-sim

- Level: L3
- Build: simulation docs for handling a mock security incident.
- First PR: one scenario and response checklist.
- Next PRs: post-incident analysis and communication template.
- Evidence: mock incident timeline + postmortem.
- Skills: incident handling, security communication.

## Picking the right first idea

- If new to contributions: pick `IB-CSSE-01` or `IB-CY-01`.
- If comfortable with code: pick `IB-CSSE-02` or `IB-CSSE-03`.
- If interested in security operations: pick `IB-CY-03` or `IB-CY-05`.
