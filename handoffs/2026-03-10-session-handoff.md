
---

## `handoffs/2026-03-10-session-handoff.md`

```markdown
# Session Handoff — 2026-03-10

This document captures the full operational state of the active Brian Bills engineering / recruiting campaign as of March 10, 2026.

The purpose is to allow a new session or assistant to become productive immediately without re-deriving the context from scratch.

---

## Executive Summary

Brian Bills is actively running a combined:

- engineering portfolio build-out
- Apple application campaign
- Zscaler interview campaign
- infrastructure lab build
- future FloridaSOS / BizRanker recovery plan

A major theme of the current strategy is shifting away from low-quality vendor-recruiter dependence and toward:

- direct applications
- internal referrals
- a strong public GitHub engineering portfolio
- demonstrable platform / SRE artifacts

The current direction is deliberate and already producing better positioning.

---

## Apple Campaign

### Internal Contact
The inside contact at Apple is:

- **John Viatella**

Important context:

- personal connection through AA
- same home group as Brian
- attends the same Friday night men's meeting
- has been receiving role numbers and updated resumes for internal visibility and possible referral support

### Apple Account Recovery
Brian successfully restored access to the Apple account used for Apple Careers.

Relevant Apple-related Gmail/account identity:

- `brian.bills.dev@gmail.com`

This was important because the prior Apple Careers access had become blocked / inconsistent, and restoring the account enabled direct application activity again.

### Apple Roles Submitted
These roles have already been submitted:

1. **Kubernetes Platform Engineer**
   - Role Number: `200623799-0836`
   - Cupertino
   - Silicon Technologies Group
   - Strong match based on Kubernetes, Terraform, GitOps, infrastructure automation, and platform operations

2. **Sr. Site Reliability Engineer**
   - Role Number: `200633415-3401`
   - Apple Cloud network infrastructure / Core Services
   - Strong fit based on CI/CD, observability, networking, incident response, Linux, Kubernetes, and cloud reliability

3. **Senior Site Reliability Engineer**
   - Role Number: `200630731`
   - Media Platforms SRE
   - Cupertino
   - Apple Services Engineering
   - Strong fit based on DevOps, reliability engineering, Kubernetes modernization, automation, and large-scale service support

### Apple Communication Already Sent to John
John has already been sent emails containing role numbers and supporting context for the submitted roles.

Future Apple-related work should continue to:
- send exact role numbers
- use concise, respectful notes
- mention updated resume where relevant
- keep internal visibility warm without becoming repetitive

### Apple Skills Matrix
A very large Apple skills matrix was completed and tuned to look credible rather than inflated.

General rating logic used:

- Expert (5): true core strengths
- Advanced (4): strong applied experience
- Proficient (3): meaningful but not primary
- Basic (2): touched but not core

Key expert-level signals emphasized:
- Kubernetes
- Linux
- Jenkins
- CI/CD
- build pipelines
- Terraform
- infrastructure automation
- troubleshooting runtime issues
- production incident response
- site reliability
- production release

Important note:
The current thread contains a lot of detailed skill-level decisions. Those should be treated as already-established and not needlessly re-litigated unless Apple asks for a new matrix.

---

## Zscaler Campaign

### Key Recruiter
- **Ken McKoon**
  - internal recruiter at Zscaler

### Role Context
- FedRAMP-related
- additional interview expected / rescheduling underway

### Strategic Framing for Zscaler
Brian should continue to emphasize:

- regulated infrastructure
- GovCloud / security-minded operations
- CI/CD governance
- reliability engineering
- Linux / cloud / automation
- production troubleshooting
- enterprise operations maturity

The Zscaler track remains important and active.

---

## GitHub Portfolio Status

### Goal
Transform `bizranker` into a serious engineering portfolio that Apple, Zscaler, and similar teams can respect.

### Repos already positioned as strong public artifacts

- `bizranker-infra`
  - backup automation
  - S3 recovery
  - disk monitoring
  - Slack alerting

- `diff-overlays`
  - Kubernetes / ArgoCD image drift detection
  - operational reporting
  - GitOps-aware automation

- `distributed-storage-monitor`
  - multi-host storage monitoring
  - disk usage reporting
  - top-consumer detection
  - management reporting
  - large enterprise operations tooling

- `linux-provisioning-automation`
  - Kickstart / Preseed
  - DHCP / DNS automation
  - rollback-aware host provisioning
  - zero-touch provisioning story

- `process-samples`
  - advanced Bash / awk / Unix-style data processing
  - binary parsing
  - command-line tooling

- `florida-sos`
  - Flask-based data automation platform
  - currently less emphasized because public live environment is down

### Pinned Repo Logic
The profile should prioritize strong SRE / platform signals.

Preferred current pin set:

- `orchard-lab`
- `bizranker-infra`
- `diff-overlays`
- `distributed-storage-monitor`
- `linux-provisioning-automation`
- `process-samples`

### Why BizRanker is temporarily de-emphasized
Because the public BizRanker / FloridaSOS live demo is currently impacted by DigitalOcean payment issues, it is strategically better to emphasize:
- live engineering credibility
- clean infra repos
- Orchard Lab

rather than direct visitors toward a currently unstable public fintech demo link.

---

## Orchard Lab

### Current State
No repo existed initially, but the local Terraform files were located here:

`C:\Users\brian\OrchardLab\aws-micro-lab\infra`

A new clean structure has been created for:

`C:\Users\brian\Documents\GitHub\orchard-lab`

### Current Orchard Lab File Layout
The cleaned repo structure includes:

- `infra/acm.tf`
- `infra/acm_wildcard.tf`
- `infra/alb_tls.tf`
- `infra/bootstrap.ps1`
- `infra/ec2.tf`
- `infra/main.tf`
- `infra/providers.tf`
- `infra/sg_web.tf`
- `infra/variables.tf`
- `infra/.terraform.lock.hcl`
- `infra/terraform.tfvars.example`
- archived alternates under `infra/archived/`

State files were intentionally excluded.

### Strategic Decision
Orchard Lab is now intended to become the **public flagship repo** because it best demonstrates:

- Terraform
- AWS
- VPC thinking
- TLS / ACM / ALB patterns
- reproducible infrastructure
- platform engineering direction

### Current Next Step for Orchard Lab
- finalize `.gitignore`
- finalize `README.md`
- create GitHub repo `bizranker/orchard-lab`
- push local repo
- pin it on profile

---

## FloridaSOS / BizRanker Recovery

### Current Status
FloridaSOS / BizRanker is not the immediate focus for public GitHub profile emphasis.

Reason:
- live site issue due to DigitalOcean payment problem
- recovery work would involve:
  - app restore
  - database restore
  - cron recreation
  - account/permission recreation
  - deployment target choice (likely AWS EC2)
- this can easily become a derailment while Apple / Zscaler momentum is active

### Important Fact
A working backup exists, including:
- working app copy
- database contents

So recovery is feasible, just intentionally deferred.

---

## Recruiter / Contact Philosophy

Brian is intentionally moving away from:
- third-rate recruiter spam
- vendor-blast dependency
- low-quality W2 contract churn

And toward:
- direct applications
- internal referrals
- visible engineering portfolio
- clean infrastructure credibility

This strategic shift should be preserved.

Any future advice that tries to pull the campaign back into low-grade recruiter chaos should be treated skeptically.

---

## Important Engineering Stories to Preserve

### HP / 3PAR / Enterprise DevOps Operations
Brian worked in a large enterprise environment involving:
- HP / 3PAR storage
- private MPLS-like inter-campus links
- synchronized DevOps environments across multiple campuses
- onboarding/offboarding hundreds of developers per month
- very high ticket throughput
- storage governance and automation
- scripts to identify top storage consumers and move non-compliant data to scratch with rollback safeguards

This is a very strong story for platform / SRE credibility.

### DocMagic
Important themes from DocMagic:
- Kubernetes / Rancher / ArgoCD environment familiarity
- overlay/image drift detection
- production support
- CI/CD support
- high-volume mortgage / financial platform environment
- reliability and operational tooling

### GitHub Philosophy
Portfolio should emphasize:
- timeless engineering artifacts
- operational maturity
- automation discipline
- observability
- infrastructure reliability
- systems thinking

Avoid showcasing artifacts that look outdated in a way that weakens modern platform credibility.

Example:
Older one-size-fits-all Kubernetes cluster bootstrap scripts may be archived privately rather than promoted publicly.

---

## Immediate Next Actions

1. Finish standing up `career-ops` as the continuity repo
2. Push Orchard Lab to GitHub as `bizranker/orchard-lab`
3. Pin Orchard Lab on GitHub profile
4. Continue checking and responding to key recruiter / Apple / Zscaler messages
5. Return to Orchard Lab completion work
6. Later revisit FloridaSOS recovery when it will not derail active campaign momentum

---

## Instruction to Future Session / Assistant

Do not act like this is a cold start.

Treat the following as already established:

- Brian Bills is a senior DevOps / SRE / platform-minded engineer
- Apple campaign is active with 3 submitted roles already
- John Viatella is the internal Apple contact
- Ken McKoon is the Zscaler internal recruiter
- Zscaler role is FedRAMP-related
- GitHub portfolio is actively being curated under `bizranker`
- Orchard Lab is the current flagship repo-in-progress
- FloridaSOS recovery is important but intentionally deferred
- detailed reasoning has already been done for many directional choices

The correct behavior is to continue execution, not restart discovery.
