# SCP Pilot Program

**Supervisory Control Plane — Context as a Service**

**Version:** 1.0 DRAFT
**Date:** January 2026

---

## Overview

The SCP Pilot Program is a 90-day engagement designed to validate governed AI context in your environment. We deploy SCP, help you create governance bundles for your use case, connect your AI agents to the context service, and measure the results.

**Objective:** Prove that structured, governed context improves AI agent behavior—with measurable outcomes in policy adherence, auditability, and operational consistency.

---

## What's Included

### Phase 1: Context Development (Weeks 1-3)

**We will:**
- Conduct discovery session to understand your AI use case, policies, and compliance requirements
- Create a sample governance bundle package tailored to your domain (e.g., prior authorization, clinical documentation, claims processing)
- Validate bundle structure against SCS specification
- Version and lock the bundle for deployment

**Deliverable:** Production-ready governance bundle (YAML) containing your policies, constraints, and compliance requirements in structured context format.

---

### Phase 2: Deployment & Integration (Weeks 4-6)

**We will:**
- Deploy SCP Control Plane in **your environment** (your infrastructure, your data stays with you)
- Load your governance bundle into the Bundle Registry
- Work with your engineering team to connect up to **5 AI agents** to the Context Service
- Configure agent registration (roles, allowed intents)
- Verify context streaming is working end-to-end

**Deployment note:** SCP is deployed within your infrastructure. Your policies, context, and agent data never leave your environment. This ensures compliance with data residency and confidentiality requirements.

**Deliverable:** Working SCP deployment with your agents receiving governed context.

---

### Phase 3: Testing & Validation (Weeks 7-10)

**We will:**
- Define test scenarios that exercise your governance rules
- Run agents with governed context, capture outputs
- Compare behavior with/without context (before/after analysis)
- Document policy citations, audit trail completeness, and behavioral differences

**Deliverable:** Test results report showing measured impact of governed context.

---

### Phase 4: Metrics & Readout (Weeks 11-12)

**We will:**
- Use Control Plane API to gather usage metrics
- Compile pilot summary: what worked, what didn't, recommendations
- Conduct executive readout session
- Provide go-forward recommendation (expand, adjust, or not a fit)

**Deliverable:** Pilot summary report and executive presentation.

---

## Pilot Scope

| Item | Included |
|------|----------|
| Governance bundles | 1 bundle package (up to 10 SCDs) |
| AI agents connected | Up to 5 agents |
| SCP deployment | Single environment (test/staging) |
| Integration support | Up to 20 hours of engineering collaboration |
| Duration | 90 days |

**Out of scope (additional cost):**
- Production deployment
- More than 5 agents
- Multiple environments
- Custom integrations beyond standard API/gRPC
- Ongoing support beyond pilot period

---

## Customer Responsibilities

To ensure pilot success, the customer will:

1. **Provide a test application** with no more than 5 AI agents ready for integration
2. **Assign a technical point of contact** available for weekly syncs and integration work
3. **Provide access** to relevant policy documents, compliance requirements, and domain knowledge for bundle creation
4. **Allocate engineering time** (estimate: 10-20 hours total) to integrate agents with Context Service
5. **Participate in discovery** and readout sessions

---

## Timeline

| Week | Phase | Activities |
|------|-------|------------|
| 1 | Discovery | Kickoff, use case deep-dive, policy review |
| 2-3 | Context Development | Bundle creation, validation, versioning |
| 4-5 | Deployment | SCP deployment, registry setup |
| 6 | Integration | Agent connection, configuration |
| 7-9 | Testing | Test execution, result capture |
| 10 | Analysis | Before/after comparison, metrics gathering |
| 11-12 | Readout | Summary report, executive presentation, recommendations |

---

## Success Criteria

The pilot is considered successful if:

1. **Governed context is delivered** — Agents receive context from SCP at runtime
2. **Behavior change is measurable** — Documented difference between with/without context
3. **Audit trail exists** — Can prove what context each agent had at any decision point
4. **Customer team is enabled** — Your team understands how to create and deploy bundles

---

## Investment

| Pilot Package | Price |
|---------------|-------|
| SCP Pilot Program (90 days, up to 5 agents) | **$15,000** |

**Payment terms:**
- 50% at signing ($7,500)
- 50% at pilot completion ($7,500)

**Reference requirement:**
As part of the pilot agreement, we ask for permission to use your company as a reference and/or case study (subject to your approval of any published materials).

**Important:** The pilot license is valid for 90 days. At the conclusion of the pilot, the customer must either convert to a production license or discontinue use of SCP.

**Production pricing:**
Following a successful pilot, production licensing is based on agent count and deployment scope. Volume discounts available. We'll discuss production terms during the pilot based on your specific needs.

---

## What Happens After the Pilot?

The pilot license expires at 90 days. Before expiration:

**If it works:**
We discuss production licensing based on your agent count and deployment needs. Your pilot fee credits toward your first-year license.

**If it doesn't:**
You keep the bundles we built (YAML files, documentation, learnings). SCP access ends at 90 days. No further obligation.

---

## Next Steps

1. **Discovery call** — Discuss your use case, agents, and timeline
2. **Proposal** — We provide a customized pilot proposal
3. **Kickoff** — Sign agreement, schedule kickoff, begin Phase 1

**Contact:**
info@ohana-tech.com

---

## About SCP

**Supervisory Control Plane (SCP)** is managed infrastructure for streaming governed context to AI agents in real-time. Built on the open **Structured Context Specification (SCS)**, SCP enables organizations to:

- Define policies, constraints, and compliance requirements as versioned bundles
- Stream context to agents based on role and intent
- Update all agents instantly without code changes
- Prove what context was active at any point in time

Learn more: [supervisoryplane.com](https://supervisoryplane.com) | [structuredcontext.dev](https://structuredcontext.dev)

---

*© 2026 Ohana AI Strategy & Systems Architecture. All rights reserved.*
