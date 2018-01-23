# Updating the OVAL Language Development Process
This repository is the working area as members of the OVAL Board work to define an updated language development process. This work is based largely on an initial effort memorialized in [working_doc.md](https://github.com/CISecurity/oval-governance-update/blob/master/working_doc.md).

This entire effort is a ***work in progress***. We are starting at the higher levels of abstraction, gaining feedback from the wider Board, and iterating to lower levels of abstraction until we arrive at an implementable process.

We are tracking a variety of issues [here](https://github.com/CISecurity/oval-governance-update/issues), and are on a weekly meeting schedule to iterate through the process, so that we can address each of these issues (many of which were the direct feedback of various Board members).

We have also created a simple project to track actions that may not be specifically releated to issues [here](https://github.com/CISecurity/oval-governance-update/projects/1).

# Project Goals
1. Provide a central place of record for versions of the OVAL specification
2. Provide mechanisms for the OVAL community to revise and augment the specification in order to maintain current capabilities and expand capabilities within current use cases
3. Provide forums for the OVAL community (language developers, content producers, content users) to discuss OVAL-related topics
4. Provide a mechanism for listing tools that support the OVAL specification
6. Be transparent and open to the public
    1. Issues
    2. Language proposals
    3. Decisions
    4. Governance process and execution
    5. Board membership
    6. Schema supervisor assignments
8. Coordinate the hosting of online and/or offline events
9. Encourage contributions from the public
10. Adopt policies and practices that allow language development speed and agility while maintaining respectable stability.
11. OVAL Language specifications and schemas must be provided under licensing terms that are commercially friendly and not overly prohibitive.

# Abstract Process Framework

This process framework describes various roles played in, and the gist of, our ideas for governing OVAL Language Development, with most of the details being contained in various [process artifacts](https://github.com/CISecurity/oval-governance-update/process_artifacts).

![Process Diagram](https://github.com/CISecurity/oval-governance-update/blob/master/graphics/png/language-development-0.5.png)

The diagram above (also available in [PDF form](https://github.com/CISecurity/oval-governance-update/blob/master/graphics/pdf/language-development-0.5.pdf)) contains process steps with dotted-line boundaries. This symbol indicates a step that is, or will need to be, further described - in other words, this symbol denotes a proper sub-process more than a simple step. For example, the box labeled with "Release" is certainly more complicated than simply releasing, and will likely have it's own process diagram to aid in explaining how the ultimate release process goes.

The document shapes (with the bent upper right corners) represent artifacts relied upon by the associated process step. A filled in arrow in the upper left of one of these symbols would represent an output artifact, whereas a clear (white) arrow would represent an input artifact. For example, the "Release" step of the process presently requires two process artifacts: Proposal Acceptance Guidelines, and Release Instructions.

The rest of the symbols should be largely self-explanatory, but if clarifications are needed, please create a [new issue](https://github.com/CISecurity/oval-governance-update/issues/new), so that we may address it.

## The Process

### Overview

The process described here is one that we intend to use not only to streamline and make more rigorous development of the OVAL language, but also one that will govern changes to any related artifact, be it documentation, a diagram, or a schema. Thus, the process will encompass managing changes to our rules for governing the OVAL language, which areas of responsibility we have in place, and roles and responsibilities, in addition to the language schemas proper.

This process is streamlined from the way OVAL is presently managed, in that many of the day-to-day activities are pushed down to where the work is happening, which frees the Leadership Board from such details. This process is more rigorous in that OVAL has never enjoyed the level of process control we are proposing here.

Our intent is to store everything about OVAL in a GitHub repository, similar to what [The OVAL Project](https://github.com/OVALProject) has organized. Because everything about OVAL will be in a GitHub repository, the process described here can either simply be applied or be slightly modified to accommodate change proposals to _anything_ OVAL. If we don't have an [Area Supervisor](https://github.com/CISecurity/oval-governance-update/blob/master/process_artifacts/areas-of-responsibility.md) or role covering a specific change proposal, we'll create one or agree to assign an existing role to cover the proposal.

There are three major roles to be played in this process, beyond the community at large. These are:

* [Leadership Board](https://github.com/CISecurity/oval-governance-update/blob/master/process_artifacts/roles-and-responsibilities-bod.md): Steers the OVAL mission and use cases, assists (when needed) with consensus calls, and is instrumental in updating design principles.
* [Sponsor](https://github.com/CISecurity/oval-governance-update/blob/master/process_artifacts/roles-and-responsibilities-sponsor.md): Mainly handles logistics for managing OVAL resources, managing area supervisor appointments, operating the OVAL Repository, and so on.
* [Area Supervisors](https://github.com/CISecurity/oval-governance-update/blob/master/process_artifacts/roles-and-responsibilities-area-supervisor.md): Responsible for specific areas concerned with OVAL, as segmented [here](https://github.com/CISecurity/oval-governance-update/blob/master/process_artifacts/areas-of-responsibility.md).

### Process Details
#### Create GitHub Issue
Anyone can create a GitHub Issue for the OVAL Language. Those submitting an issue should follow the [issue instructions](https://github.com/CISecurity/oval-governance-update/blob/master/process_artifacts/issue_instructions.md). After an issue is submitted, there's at least a seven day comment period, during which time the issue may be resolved. If the issue is not resolved, then someone (the issue submitter or a third party) may submit a first proposal to resolve the issue by modifying the OVAL language.

#### First Proposal
Creating the first proposal in response to an unresolved issue requires knowledge of the following process artifacts:

* [Pull Request Instructions](https://github.com/CISecurity/oval-governance-update/blob/master/process_artifacts/pull_request_instructions.md)
* [Proposal Acceptance Guidelines](https://github.com/CISecurity/oval-governance-update/blob/master/process_artifacts/proposal_acceptance_guidelines.md)
* [OVAL Design Principles](https://github.com/CISecurity/oval-governance-update/blob/master/process_artifacts/design_principles.md)

A proposal is considered, created, and then submitted as a GitHub pull request, at which time it enters the consensus building step of the process. Note that if there is no activity on the proposal for 45 days, the proposal automatically goes into the consensus call step of the process.

#### Consensus Building
Consensus building is a subprocess in its own right, as depicted below (also in [PDF](https://github.com/CISecurity/oval-governance-update/raw/master/graphics/pdf/consensus-building-0.1.pdf)).

![Consensus Building](https://github.com/CISecurity/oval-governance-update/blob/master/graphics/png/consensus-building-0.1.png)

During the consensus building subprocess, anyone can raise issues about the submitted pull request. Such issues may be handled in one of several ways, but we expect them to be categorically handled as being questions needing answers, or objections to the proposal on specific grounds (i.e. on the grounds that the proposal is contrary to a design principle). From time to time we expect that certain objections may in fact trigger consideration for updating the design principles.

##### Update Design Principle
Updating design principles will likely come as a direct result of a proposal objection on the grounds of a principle not yet covered in the documented [design principles](https://github.com/CISecurity/oval-governance-update/blob/master/process_artifacts/design_principles.md). Updating the design principles document is not necessarily a difficult process, but it does involve the Leadership Board, applicable [Area Supervisor](https://github.com/CISecurity/oval-governance-update/blob/master/process_artifacts/areas-of-responsibility.md), Proposer, and the Community at large.

![Update Design Principle](https://github.com/CISecurity/oval-governance-update/blob/master/graphics/png/update-design-principle-0.1.png)

The gist is that we all review the proposal and suggest changes to the design principles. At some point, the Leadership Board feels the change is ready for a consensus call, and the consensus call is held to determine the disposition of the proposed change, which will be carried or not.

#### Consensus Call and Consensus Call Support
Updating design principles is not the only place consensus calls are used. In general, a consensus call is in place to give an opportunity for any late comers to opine, and to add a little more rigor to the process of making updates to the OVAL language, governance rules, and process. The consensus call for a given proposal, which happens either 45 days after the first proposal (with no subsequent activity) or when consensus building is winding down, relies on the [proposal acceptance guidelines](https://github.com/CISecurity/oval-governance-update/blob/master/process_artifacts/proposal_acceptance_guidelines.md) and [OVAL design principles](https://github.com/CISecurity/oval-governance-update/blob/master/process_artifacts/design_principles.md). From time to time the Leadership Board may be called in to help judge consensus, but we anticipate this circumstance to be rare.

See our [consensus guidelines](https://github.com/CISecurity/oval-governance-update/blob/master/process_artifacts/proposal_consensus_guidelines.md) for specific details on judging consensus.

#### Release and Logistical Support
A proposal that gains consensus will then move into to the release subprocess, which follows the [proposal acceptance guidelines](https://github.com/CISecurity/oval-governance-update/blob/master/process_artifacts/proposal_acceptance_guidelines.md)  and relies upon the [release instructions](https://github.com/CISecurity/oval-governance-update/blob/master/process_artifacts/release_instructions.md). Depending on the nature of the change and the implementation support enjoyed by the proposal, a release will go into one of four release streams: Extensions, development, stable, or official (these streams are described [here](https://github.com/CISecurity/oval-governance-update/blob/master/process_artifacts/release_instructions.md)).

#### Release Announcement
When an update to any stream is released, the Sponsor will be responsible for announcing the release according to the [announcement guidelines](https://github.com/CISecurity/oval-governance-update/blob/master/process_artifacts/release-announcement-checklist.md).
