---
title: Platform
permalink: /platform/
eyebrow: Platform
lede: Govnr is designed as civic infrastructure for groups of any size, from clubs and communities to institutions and large-scale democratic spaces.
---

Govnr is being designed around a stable civic core: organisations, spaces, membership, petitions, motions, voting, results, decisions, and verification.

## Core Lifecycle

The first platform lifecycle is deliberately simple:

```text
Group -> Membership -> Petition -> Motion -> Vote -> Result -> Decision
```

Members can raise ideas, gather support, deliberate, vote, and preserve the outcome as an official record.

## Architecture

The core platform is being rebuilt around a clean domain model:

- `domain`: civic concepts and rules.
- `application`: use cases and policies.
- `infrastructure`: adapters for persistence, workers, AI, auth, queues, and ledger implementation.
- `api`: public API and client-facing contracts.

The web app, admin app, verification tool, and future mobile app consume the core API rather than embedding civic rules themselves.

## Scale

Govnr should work for a book club, sports club, enterprise, civic institution, city, country, or future global democratic process. The same principles should apply across those contexts: clear rules, equal participation by default, auditability, and accessible participation.

