# ATP022 — OpenBao

An Astrona **training path**: a course track that groups training series
(`ATSxxx`) as its domains. Each stage in `path.yaml` is one domain and points
at the repository that teaches it. There is no official OpenBao certification
exam, so the domains and weights are Astrona's own and `examPreparation` is
off. Everything is written for OpenBao v2.7.1.

| Stage | Domain | Weight | Content | Status |
| --- | --- | --- | --- | --- |
| STG001 | Fundamentals, Architecture & CLI Operations | 10 % | [ATS112](https://github.com/astrona-io/ATS112) | Draft, written, not yet run |
| STG002 | Authentication Methods & Identity Management | 20 % | [ATS113](https://github.com/astrona-io/ATS113) | Draft, written, not yet run |
| STG003 | Secrets Engines & Dynamic Credential Lifecycle | 25 % | [ATS114](https://github.com/astrona-io/ATS114) | Draft, written, not yet run |
| STG004 | Access Control Policies, Leases & Audit Devices | 15 % | [ATS115](https://github.com/astrona-io/ATS115) | Draft, written, not yet run |
| STG005 | OpenBao Agent, Proxy & Application Integration | 15 % | [ATS116](https://github.com/astrona-io/ATS116) | Draft, written, not yet run |
| STG006 | Enterprise Operations, Auto-Unseal & HA Clusters | 15 % | [ATS117](https://github.com/astrona-io/ATS117) | Draft, written, not yet run |

The site picks it up through [astrona-content](https://github.com/astrona-io/astrona-content):
a file in `courses/` that points at this repository, and the content sync
builds the course — one section per stage, with the readings, playgrounds and
labs each stage repository lists in its `astrona.yaml`. That course file does
not exist yet; add it when the first stage is ready to show.
