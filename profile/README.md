# VerityOps

### Trust the outcome, not just the automation.

VerityOps is building an independent verification layer for automated IT operations.

As businesses increasingly rely on automation to manage critical IT infrastructure, knowing whether an operation actually succeeded is becoming just as important as executing it.

VerityOps aims to close that gap by independently verifying outcomes, identifying failures, and providing evidence that automated operations achieved their intended results.

---

## The Problem

IT teams and Managed Service Providers (MSPs) depend on automation to handle repetitive and increasingly complex operations.

But an automation reporting success doesn't necessarily mean the job was completed correctly.

- An account might be created without the correct license.
- Required permissions might never be assigned.
- An onboarding workflow might only partially complete.
- An automation might fail silently.
- Execution logs might report success without confirming the actual system state.

As automation becomes more widespread, relying solely on execution logs and success messages creates operational risk.

**IT teams need confidence in the outcomes of their automation, not just confirmation that a script ran.**

## Our Solution

VerityOps is developing a vendor-neutral platform designed to independently verify automated IT operations.

Rather than simply trusting the system that performed an action, VerityOps aims to inspect the resulting state of connected systems and compare it against expected outcomes.

Our approach focuses on three things:

1. **Independent verification** — Check what actually happened, independently of the automation that performed the operation.
2. **Evidence-backed results** — Provide traceable evidence supporting every verification result.
3. **Failure detection** — Identify incomplete, incorrect, or unverifiable outcomes before they are mistakenly treated as successful.

## How It Works

An example of our initial use case: Microsoft 365 employee onboarding.

<escape>1.</escape> **Request:** An employee onboarding request is approved.

<escape>2.</escape> **Execution:** An existing automation or technician provisions the employee's Microsoft 365 account.

<escape>3.</escape> **Verification:** VerityOps independently checks the resulting account state.

<escape>4.</escape> **Comparison:** Actual system state is compared against the expected configuration.

<escape>5.</escape> **Evidence:** VerityOps produces a report showing what passed, what failed, and what could not be verified.

### Verification Results

| Status | Meaning |
|---|---|
| PASS | All required conditions were independently verified. |
| FAIL | One or more required conditions were not met. |
| UNKNOWN | There was insufficient evidence to determine the result. |

**An unknown result is never treated as a successful result.**

## Initial Focus

Our initial product research is focused on Managed Service Providers (MSPs) that manage Microsoft 365 environments and rely on scripts, integrations, and automated workflows.

We are investigating how independent verification could help teams:

- Validate employee onboarding and offboarding.
- Confirm account and license configurations.
- Verify group memberships and permissions.
- Identify incomplete automation workflows.
- Reduce manual verification work.
- Improve operational visibility and accountability.

## Our Principles

- **Independence:** Verification should not blindly trust the system performing the operation.
- **Accuracy:** Results should be based on actual observations and deterministic checks.
- **Transparency:** Every result should have supporting evidence.
- **Security:** Read-only access and least-privilege permissions by default.
- **Reliability:** Incomplete verification must never be represented as success.
- **Interoperability:** Work toward supporting multiple automation providers and IT platforms.

## Long-Term Vision

We envision VerityOps becoming a trusted verification layer across the IT automation ecosystem.

Our long-term direction includes:

- Microsoft 365 and identity management.
- Endpoint and device management.
- IT service management.
- RMM and PSA platforms.
- Cross-platform automation verification.
- Enterprise IT operations.

Our goal is to make independently verified automation a standard part of modern IT operations.

## Project Status

<escape>**Early-stage development and customer discovery.**</escape>

VerityOps is currently exploring the problem, validating customer needs, researching the competitive landscape, and evaluating technical feasibility.

The product concept and market opportunity have not yet been validated. We are actively investigating whether existing solutions adequately address this problem and where meaningful differentiation may exist.

## Get Involved

We are interested in connecting with:

- MSP owners and operators.
- IT technicians and service delivery managers.
- Developers building IT automation.
- People working on IT infrastructure and operations.

If you work with IT automation and have experience verifying its results, we'd be interested in hearing about your challenges and workflows.

For now, please use GitHub Issues or Discussions to share feedback and ideas.

---

**VerityOps**

*Trust the outcome, not just the automation.*
