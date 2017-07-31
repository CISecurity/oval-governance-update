> _Work in Progress: this document is a work in progress. If you have feedback, please let us know._

# OVAL Language Release Instructions

This document defines the OVAL community release streams, schedules and related processes.

## OVAL Language Release Streams
There are four distinct release streams used to balance varying stakeholder needs for langauge stability and agility. These streams are envisioned as being implemented as long-lived git branches:

* **Extensions:** Proposals that are made available as an Unofficial Extension after not being adopted by the community.
* **Development:** all adopted Proposals awaiting a Second Implementation or release to the Stable release stream.
* **Stable:** all adopted Proposals that have a confirmed Second Implementation as of the most recent Stable release data on February 1st and August 1st of each year.
* **Official:** a Stable Release that the OVAL Board selects as the Official release at least once a year.

### Extensions

The Extensions release stream includes Proposals that were not adopted, but have been made available as unofficial extensiosn to the OVAL language. Extensions enable community members to publicly document schemas that are not adopted by the community.

#### Extention Release Process

1. A Proposal is not adopted (e.g. fails due to an objection or an alternative proposal being selected)
  - _Note: we should probably require that Extensions are valid XSDs, have documentation, at least once implementation, examples, and etc. Perhaps we could indicate a subset of our Proposal Acceptance Guidelines and/or Proposal Instructions that are required for Extensions?_
2. Any community member requests that the Proposal is published as an Extension by adding a comment to the rejected Proposal
3. The relevant Area Supervisor publishes the Proposal to the Extensions release stream

### Development

The Development release stream includes all adopted Proposals that are awaiting a Second Implementation or the next scheduled Stable Release.

#### Development Release Process

1. A Proposal is adopted via the standard community process
2. The relevant Area Supervisor publishes the Proposal immediately to the Development release stream

### Stable

The Stable release stream includes all Proposals that have been adopted by the community via the standard Proposal process and have a confirmed Second Implementation as of the semi-annual Stable release dates, February 1st and August 1st of each year.

#### Stable Release Process

1. A Proposal in the Development release stream receives a confirmed Second Implementation
2. On February 1st and August first of each year, Area Supervisors publish all such Proposals to the Stable release stream

### Official

The Official release stream is a Stable release selected by the OVAL Board at least once per year to be the Offical release.

#### Official Release Process

1. The OVAL Board selects the Official release via vote at a regular meeting TBD.
