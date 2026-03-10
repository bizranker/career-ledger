# career-ops

Operational continuity repository for Brian Bills' active engineering, recruiting, and portfolio campaign.

This repository exists to preserve working context across long ChatGPT sessions, thread handoffs, recruiter follow-ups, infrastructure planning, and portfolio decisions.

Its purpose is simple:

- prevent loss of momentum
- preserve decisions and rationale
- track recruiter activity and job IDs
- maintain continuity across sessions
- serve as a runbook for the current career and engineering campaign

---

## Primary Active Tracks

### 1. Apple SRE / Platform Campaign
Brian is actively applying to Apple Site Reliability Engineering and Platform Engineering roles.

Recent Apple submissions include:

- **Kubernetes Platform Engineer** — Role Number `200623799-0836`
- **Sr. Site Reliability Engineer** — Role Number `200633415-3401`
- **Senior Site Reliability Engineer** — Role Number `200630731`

Internal Apple contact:

- **John Viatella**
  - Personal connection through AA
  - Same home group
  - Attends the Friday night men's meeting
  - Has been receiving role numbers and updated resume for internal visibility / referral support

### 2. Zscaler Track
Brian is actively engaged with Zscaler.

Key recruiter:

- **Ken McKoon**
  - Internal recruiter at Zscaler

Role context:

- FedRAMP-related role
- Additional interview expected / being rescheduled with hiring manager
- Preparation should emphasize:
  - GovCloud / regulated environments
  - CI/CD governance
  - infrastructure automation
  - security-minded DevOps / SRE practices

### 3. GitHub Portfolio Build-Out
The `bizranker` GitHub account is being curated into a serious SRE / Platform Engineering portfolio.

Important live repos include:

- `bizranker-infra`
- `diff-overlays`
- `distributed-storage-monitor`
- `florida-sos`
- `linux-provisioning-automation`
- `process-samples`
- `orchard-lab` (to become flagship lab repo)

### 4. Orchard Lab
Orchard Lab is now the preferred public-facing flagship infrastructure lab until BizRanker / FloridaSOS is restored to a stable public environment.

Reasoning:

- cleaner engineering story
- easier to complete quickly
- less tied to current DigitalOcean billing issues
- stronger direct relevance for Apple / Zscaler / platform roles

### 5. FloridaSOS / BizRanker Recovery
Recovery of FloridaSOS / BizRanker remains important but is intentionally deferred so it does not derail the immediate Apple / Zscaler / Orchard Lab momentum.

The app previously worked in production and a backup copy exists, along with database contents. Restoration is expected to involve AWS EC2, recreated cron, and service-level recovery.

---

## Repo Structure

```text
career-ops/
├ README.md
├ handoffs/
├ recruiters/
├ projects/
└ decisions/
