# OVAL Specification Moderation
## A Community-Driven Approach
### Goals
1. Provide a central place of record for versions of the OVAL specification
2. Provide mechanisms for the OVAL community to revise and augment the specification in order to maintain current capabilities and expand capabilities within current use cases
3. Provide forums for the OVAL community (language developers, content producers, content users) to discuss OVAL-related topics
4. Provide a listing of tools that support the OVAL specification
5. Coordinate the hosting of online and/or offline events
6. Be transparent and open to the public
7. Adopt policies and practices that favor: a) progress towards closing gaps between current capabilities and full realization of OVAL use cases; and b) ongoing incremental improvement over stability and completeness when there is a conflict between the former and latter.
8. OVAL Language specifications and schemas must be provided under licensing terms that are commercially friendly and not overly prohibitive.

### Open Questions
* General: We’re open to any and all feedback! Is this even the right approach? If not, be blunt! Let’s figure out something that makes sense to everyone.

### Processes & Organization Notes
* Administration Roles
   * Project Sponsor: CIS
      * Responsibilities
         * Account Owner: own all project resources such as GitHub account containing repos, mailing list accounts, etc.
         * May dissolve Supervisors as described below
      * Change Process
         * Project Sponsors can be changed by agreement of the outgoing Project Sponsor, the incoming Project Sponsor and a majority of the Supervisors
   * OVAL Leadership Board: TBD
      * Makeup: 5+ individuals or organizations represented by one or more individuals, based on interest
      * Change Processes
         * Qualifications: guidelines TBD by the Board after formation
         * Initial Makeup: current, interested OVAL Board members
         * Term and Termination: Board Members
            * Members serve two-year terms, no term limits
            * Members may step down at any time by sending a Notice to the community.
            * Members may not be removed during a term other than by stepping down
            * Members may begin serving part of the way through a term, in which case they serve out the rest of that term on a pro-rata basis
         * Dissolving the Board
            * The Project Sponsor may dissolve the entire Board at any time. Process TBD.
         * Appointment
            * Nomination: any Community Member may nominate themselves or another Community Member or organization by sending a Notice
            * Second: any other Community Member may second the nomination by sending a Notice
            * Acceptance: a seconded nominee may accept the nomination by sending a Notice within 7 days of the Second
            * Appointment: by a majority vote of the Leadership Board.
      * Areas of Responsibility
         * The Board will be responsible for maintaining the OVAL Mission, Use Cases and other key strategic documents including a set of Core Criteria that will be applied to all Proposals such as:
            * OVAL capabilities must comply with the OVAL Use Cases
            * OVAL capabilities must be read-only
         * Members will be expected to monitor project activities and weigh in on issues facing the Community, especially in areas in which they have special expertise
         * Members will be expected to offer guidance to the Community when called on by the Supervisors and/or Community Members, especially in areas in which they have special expertise, subject to their availability
         * Members will be expected to engage in online and in-person events subject to their availability
         * Members will be expected to advocate on behalf of the project to the general public when appropriate
      * Activities
         * Quarterly calls, minutes to be published to the website
   * Supervisors: TBD
      * Makeup: 5-12 individuals, based on interest
      * Change Processes
         * Term and Termination: Individual Supervisors
            * Supervisors serve two-year terms, no term limits
            * Supervisors may step down at any time by sending a Notice to the community.
            * A Supervisor may be removed by a supermajority of the Supervisors. Process TBD.
         * Dissolving the Supervisors
            * The Project Sponsor may dissolve the entire Supervisors at any time. Process TBD.
         * Election
            * Nomination: any Community Member may nominate themselves or another Community Member by sending a Notice, provided there are fewer than the number of  current primary Supervisory positions required.
            * Second: any other Community Member may second the nomination by sending a Notice
            * Acceptance: a seconded nominee may accept the nomination by sending a Notice within 7 days of the Second
            * Additional candidates may be added as long as they are Nominated, Seconded and Accepted before the Election
            * The Election will start 7-10 days after the initial candidate’s Acceptance as the discretion of the Content and Rules Supervisor. Voting process, rules, etc. to be simple, transparent and TBD.
      * Areas of Responsibility
         * Each team member will be designated a “Supervisor” of one or more of the following Supervisory Areas and a “Secondary Supervisor” of one or more other Supervisory areas by the Supervisors. 
         * Each Supervisory Area must always have exactly one Supervisor and must have one or more Secondary Supervisors. 
         * Designations to be handled informally by the Supervisors via the Proposals change process.
         * Initial Supervisory Areas:
            * Core, Common, Independent, Results, Variables and Directives Schemas
            * Android Schemas
            * Apple Schemas (iOS, Macintosh)
            * Cisco Schemas (ASA, CatOS, IOS, IOS XE, PixOS)
            * FreeBSD Schemas
            * HP-UX Schemas
            * IBM AIX Schemas
            * Linux Schemas
            * UNIX Schemas
            * Sun Solaris Schemas
            * Juniper JunOS Schemas
            * NETCONF Schemas
            * Microsoft Windows and SharePoint Schema
            * Vmware ESX Schemas
            * OVAL Extensions
            * OVAL Support Declarations
            * OVAL Events
            * Notices, Content and Rules (i.e. other website content including tutorials, general information about the project, Supervisors makeup, notices, mailing lists, minutes from activities and the governing rules of the organization)
            * Note: if a Proposal results in adding a new Schema, this list should be revised to include it via the Proposal Process.
         * Where Supervisors of an Area are charged to make a decision the Supervisor will do so. Supervisors are encouraged to consult with Secondary Supervisors, the Supervisors and the Community in general, but there is no requirement to.
         * If and when a Supervisor is unavailable to make a decision (i.e. vacation, etc.) for any reason, the Supervisor will delegate a Secondary Supervisor to serve as Supervisor. This will be handled informally within the Supervisory, but at no time will a Secondary Supervisor serve as a Supervisor (i.e. make a Supervisor decision) without being delegated to do so by the Supervisor.
         * Appeal. Anytime there is a decision made by a Supervisor, it may be appealed by any Community Member that is a party to the decision (e.g. a Proposal Author or Collaborator) by emailing the list within 3 days of the decision (exact process TBD). There are two ideas for the Appeals Process:
            * Supervisor Team Vote: call for an Appeal vote on the Supervisory Mailing list. Supervisors have 7 days to vote. A decision is overruled if a majority of Supervisors vote to overrule. (note: an abstention is functionally a vote to sustain) 
            * Consensus Call: an Appeal triggers a call for consensus in which a Secondary Supervisor emails the list asking the Community to weigh in on the issue. The Secondary Supervisors will engage in the conversation if necessary, endeavouring to ensure that the various positions are itemized and thoughtfully responded to. After 14 days, the Secondary Supervisor(s) assess whether or not there is rough consensus (guidelines TBD) and make a final decision.
         * Note: changes to Areas of Responsibility (add, edit, remove, combine, etc.) and designations will be handled via Proposals change process detailed below.
         * Note: should we allow multiple Supervisors per area? If so, will we need additional rules to determine who is responsible for Area-specific actions and how to resolve conflicts?
   * Community Members
      * Anyone who is a member of a mailing list or who has forked the repo
* Project Resources
   * Mailing Lists (Notices will be sent to all)
      * OVAL/SCAP Developers
      * OVAL/SCAP Usage        
      * Leadership Board
      * Supervisors
   * Central Repository (GitHub)
      * Repo: there will be 1 public repository hosted on GitHub 
      * Permissions: Supervisors will have read and write access. The Project Sponsor will have admin/owner access.
      * Branches: there will be 2 enduring branches:
         * core-development: pending updates to the core
         * master: the current release 
      * Folder Structure
         * Schemas: the schema definition files (XSDs)
         * Specifications: the specifications
         * Sample Content: sample content and result files
         * Extensions: schemas and/or schema versions that one or more Community Members support but were not “adopted”
         * Website: public website content via github.io (domain tbd, see current)
            * Introductory Home Page TBD
               * General Information, Use Cases, Tutorials, etc. TBD
               * Community Rules & Procedures
               * Supervisors: Designated Areas of Responsibilities, Minutes, etc. TBD
               * Voting Process, Ballots, etc?
            * Generated Documentation, Specifications, Versioning Policy
            * OVAL/SCAP Support Declarations
            * Events, Mailing Lists and other activity information
            * Top Contributors to the OVAL Repo
         * Tools: 
            * XSL to generate docs, schematrons (for content), best practices schematron (for schemas) TBD, etc.
            * Schema QA Shell Script: python script to schema validate XSD and schematron validate schemas and check that sample content and result files exist and are valid, etc. TBD.
* Proposals (Change Process)
   * Note: these notes are oriented towards Schema changes, but the intention is to use the same (or nearly the same) processes for changes to any other Resources (i.e. Extensions, website content -- including these rules! --  etc.).
   * Note: notifications to Community may be made via GitHub or mailing list TBD
   * Raise an Issue
      * Any Community Member may Raise an Issue by creating a GitHub issue describing the problem or enhancement
      * The Issue should be tagged with exactly one Area of Responsibility. If the Issue does not fall under a clear Area of Responsibility (i.e. proposing a new platform), the Contributor should pick the most relevant Area. 
      * Guidelines for Issue title, tagging and content TBD
   * Make a Proposal
      * Community Members are encouraged to allow an Issue to remain open for 7 days before Making a Proposal that addresses it in order to solicit feedback from the community before committing to a solution
      * Any Community Member may Contribute a Proposal to resolve an open Issue as follows:
         * Fork: fork the Central Repo
         * Branch: create a feature branch:
            * If a core Proposal, then the branch from core-development
            * If a non-core Proposal (Platform, Extension, Website, etc.) then branch from master
            * Name the branch: [descriptive identifier]-issue-#[Issue Number]
         * Revise: make changes or additions on the feature branch
            * Add sample content and sample result to the sample content folder named [branch-name]-sample-[content|result].xml (guidelines TBD) 
         * QA: run the Schema QA Shell Script and resolve any issues
         * Commit: commit changes to the fork
         * Pull Request: make a pull request to the core-development (if a core proposal) or master branch (if non-core) of the Central Repo including a reference to the Issue (i.e. “fixes #[Issue Number]”) and description of Proposal (guidelines TBD).
      * Note: only pull requests from members of the Supervisors will be accepted for changes to the Supervisory areas of the website (i.e. to minutes, Areas of Responsibility, etc.)
      * Note: should we require “running code” (i.e. a working implementation)?
   * Amend a Proposal: there are two ways to amend a Proposal
      * Amend with Contributor: all Community Members are encouraged to comment on the pull request and collaborate with the Contributor to amend the Proposal and update the pull request. Community Members may also fork the Contributor’s fork, amend the Proposal and make a pull request to the Contributor which the Contributor may or may not accept at their discretion.
      * Amend without Contributor: any Community Member may make an alternative Proposal by following the instructions for Making a Proposal above. This will result in multiple active pull requests all ending with the same -#[issue #], collectively know as the Alternative Proposals. When there are Alternative Proposals, the Community and especially the appropriate Area Supervisor are strongly encouraged to provide feedback in order to help build consensus around 1 Proposal.
   * Proposal Objection
      * Any Community Member may register an Objection to a Proposal on the basis that it does not comply with one or more of the Core Criteria (see above)
      * If the Area Supervisor accepts the Objection, the Proposal will be denied. Note: it may be added to Extensions if it meets the Extensions criteria. 
   * Proposal Adoption & Release
      * Proposals will be Adopted assuming they are valid and complete (exact guidelines TBD, see current guidelines) and
         * None of the Alternative Proposals’ pull requests have been updated for 14 days OR
         * Any of the Alternative Proposals were initiated more than 45 days ago and by a majority vote of the Supervisors (regardless of whether or not there have been recently Amendments)
         * Note: consider adding Extra Time mechanism whereby a Contributor can request an extra 14 once per pull request update and that can be granted by the Supervisor if deemed appropriate.
      * Alternative Proposals
         * The Area Supervisor will select amongst Alternative Proposals. Process TBD involving an announcement, short comment period, opportunity to appeal to entire Supervisors which can overrule by majority vote.
      * Platform Proposals
         * Upon adoption, the Team Supervisor will Release the Proposal by accepting the pull request into the master branch and tagging the master branch to indicate the platform schema version number
         * The Team Supervisor will also close the relevant ticket and reject any Alternative Proposals (pull requests)
      * Core  Proposals
         * Upon adoption, the Team Supervisor will accept the pull request into the core-development branch
         * The Team Supervisor will also close the relevant ticket and reject other Alternative Proposals
         * Adopted Proposals will be Released February 1, June 1 and October 1 of each year, at which time the Core Area Supervisor will merge the core-development branch into the master branch
         * Upon Release, the Core Team Supervisor will also increment all version numbers as per current process
* Extensions (Change Process)
   * Purpose: Extensions is an area to host any schemas or schema revisions that:
      * are complete, valid, documented, etc.
      * are supported by at least one Community Member
      * were not entered into the Proposal process OR were entered but not adopted
      * may or may not fall under OVAL use cases
   * Submission: any Extension meeting the criteria above will be accepted by the area Supervisor
   * Revision: any Extension may be revised by the initial submitter at any time
   * Removal: any extension may be removed by the following process:
      * Any Community Member nominates an extension for removal and is Seconded
      * No Community Member objects to the removal for 90 days
* OVAL Support Declaration
   * This area of the public website would list tools that support OVAL and specify, for each, which versions of each schema are supported (perhaps a listing and matrix)?
   * Only authorized representatives of a vendor would be able to declare on behalf of their tool(s)
   * Actual support would not be verified by any 3rd party
* OVAL Events
   * TBD
* Transition Process
   * TBD if and when there is some momentum behind adopting this proposal.