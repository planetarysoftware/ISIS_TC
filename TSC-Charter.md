# Technical Steering Committee (TSC) Charter

## Section 1. Guiding Principle.

The USGS Astrogeology Science Center (ASC) Software Organization will operate transparently, openly, inclusively,
collaboratively, and ethically. Project proposals, timelines, and status
must not merely be open, but also easily visible to outsiders.

## Section 2. Evolution of ASC Software Governance.

Most large, complex open source communities have both a business and a
technical governance model. ASC’s technical leadership
is the Technical Steering Committee (“TSC”). ASC’s business
leadership is comprised of the USGS ASC Management Team.

This Technical Steering Committee Charter reflects carefully
constructed balanced roles for the TSC and the ASC Management Team in the governance of
the ASC Software Organization. The charter amendment process is the means by which the TSC
proposes changes to this charter using simple majority of the full TSC, the proposed
changes being subject to review and approval by the ASC Management Team. The ASC Management Team may
additionally make amendments to the TSC charter at any time, though the
ASC Management Team will not interfere with day-to-day discussions, votes or meetings
of the TSC.

## Section 3. ASC Management Team’s Role in Setting the ASC Software Organization’s Strategic Direction.  

The ASC Management Team will set the overall TSC Policy. The policy will describe the
overarching scope of the ASC Software Organization initiative, ASC’s technical vision and direction and project release
expectations in the form of expected cadence and intent. The ASC Management Team will
use the TSC as a delegate body for governing technical implementation,
individual project scope and direction while they remain within the scope
and direction of the policies as described in the TSC Policy document and
approved by the ASC Management Team.

In setting overall technical vision and direction, the ASC Management Team will maintain final judgement on the inclusion of capability within the ASC managed community. Capability can be code, processing pipelines, or services to be added to an existing ASC Software Organization project or as a new project under the ASC Software Organization. The TSC will provide guidance to the ASC Management Team concerning the technical feasibility and maintainability of projects to support the ASC Management Team in making an informed decision.

## Section 4. Establishment of the TSC.

TSC memberships are not time-limited. There is no maximum size of the TSC.
The size is expected to vary in order to ensure adequate coverage of important
areas of expertise, balanced with the ability to make decisions efficiently.
The TSC must have at least three members.

There is no specific set of requirements or qualifications for TSC
membership beyond these rules. The TSC may add additional members to the
TSC by a standard TSC motion and vote. A TSC member may be removed from the
TSC by voluntary resignation, by a standard TSC motion, or in accordance to the
participation rules described below.

Changes to TSC membership should be posted in the agenda, and will be then discussed
at the next TSC meeting. Any vote to change the TSC membership must remain open
for at least a month.

The TSC may, at its discretion, invite any number of non-voting observers to
participate in the public portion of TSC discussions and meetings.

The TSC shall meet regularly using tools that enable participation by the
community (e.g. monthly on a Google Hangout On Air, or through any other
appropriate means selected by the TSC). The meeting shall be directed by
the TSC Chairperson. Responsibility for directing individual meetings may be
delegated by the TSC Chairperson to any other TSC member. Minutes, or an
appropriate recording, shall be taken and made available to the community
through accessible public postings.

TSC members are expected to regularly participate in TSC activities.

In the case where an individual TSC member -- within any three-month period --
attends fewer than 25% of the regularly scheduled meetings, does not
participate in TSC discussions, *and* does not participate in TSC votes, the
member shall be automatically removed from the TSC. The member may be invited
to continue attending TSC meetings as an observer.

## Section 5. Responsibilities of the TSC.  

Subject to such policies as may be set by the ASC Management Team, the TSC is
responsible for all technical development within the ASC Software Organization,
including:

* Setting release dates.
* Release quality standards.
* Technical direction.
* Project governance and process (including this policy).
* GitHub repository hosting.
* Conduct guidelines.
* Maintaining the list of additional Collaborators.
* Development process and coding standards.
* Mediating technical conflicts between Collaborators or ASC Organization
projects.

The TSC will define ASC Software Organization's release vehicles and serve as
ASC Software’s primary technical liaison body with external open
source projects, consortiums and groups.

## Section 6. ASC Software Organization Operations.

The TSC will establish and maintain a development process for ASC Software Organization's Projects. The development process will establish guidelines
for how the developers and community will operate. It will, for example,
establish appropriate timelines for TSC review (e.g. agenda items must be
published at least a certain number of hours in advance of a TSC
meeting).

There will be multiple Projects under the ASC Software Organization organized by
modules or subsystems. The TSC is responsible for organizing the Project
structure, including possibly the creation and alignment of sub-Projects.
Each Project must be within such policies as may be set by the ASC Management Team,
have a well-defined scope and must work within that scope. The
development process will provide for Projects to follow the lifecycle
process as described in the [Project Lifecycle][] document. The development
process will include a process for the TSC to oversee and approve changes
in the lifecycle of a Project, which will include consideration of the
following criteria:

* Cleanliness of code base
* Ample and diverse Contributors and Collaborators to assure vitality of
the project.
* Stability (e.g. presence of test suites, stable APIs and use of an
  appropriate source-code control system).
* Predictability of releases
* Alignment with ASC Software’s goals and priorities.

The TSC and entire technical community will follow any processes as may
be specified by the ASC Management Team relating to the intake and license compliance
review of contributions.

## Section 7. Voting

For internal project decisions, Collaborators shall operate under Lazy
Consensus. The TSC shall establish appropriate guidelines for
implementing Lazy Consensus (e.g. expected notification and review time
periods) within the development process.

The TSC follows a [Consensus Seeking][] decision making model. When an agenda
item has appeared to reach a consensus the moderator will ask "Does anyone
object?" as a final call for dissent from the consensus.

If an agenda item cannot reach a consensus a TSC member can call for
either a closing vote or a vote to table the issue to the next meeting.
The call for a vote must be seconded by a majority of the TSC or else the
discussion will continue.

For all votes, a simple majority of all TSC members for, or against, the issue
wins. A TSC member may choose to participate in any vote through abstention.

Note that, in addition to requiring a simple majority vote of the TSC, all
changes to this charter are also subject to approval from the ASC Management Team.

## Section 8. Project Roles

The ASC Software Organization Git repository is maintained by the TSC and
additional Collaborators who are added by the TSC on an ongoing basis.

Individuals making significant and valuable contributions,
“Contributor(s)”, are made Collaborators and given commit-access to the
project. These individuals are identified by the TSC and their addition
as Collaborators is discussed during the monthly TSC meeting.
Modifications of the contents of the Git repository are made on a
collaborative basis as defined in the development process.

Collaborators may opt to elevate significant or controversial
modifications, or modifications that have not found consensus to the TSC
for discussion by assigning the `tsc-agenda` tag to a pull request or
issue. The TSC should serve as the final arbiter where required. The TSC
will maintain and publish a list of current Collaborators by Project, as
well as a development process guide for Collaborators and Contributors
looking to participate in the development effort.

## Section 9. Definitions

* **Contributors**: contribute code or other artifacts, but do not have
the right to commit to the code base. Contributors work with the
Project’s Collaborators to have code committed to the code base. A
Contributor may be promoted to a Collaborator by the TSC. Contributors should
rarely be encumbered by the TSC and never by the ASC Management Team.

* **Project**: a technical collaboration effort, e.g. a subsystem, that
is organized through the project creation process and approved by the
TSC.

[Project Lifecycle]: https://github.com/USGS-Astrogeology/TSC/blob/master/Project-Lifecycle.md
[Consensus Seeking]: http://en.wikipedia.org/wiki/Consensus-seeking_decision-making
[Condorcet]: http://en.wikipedia.org/wiki/Condorcet_method
[Single Transferable Vote]: http://en.wikipedia.org/wiki/Single_transferable_vote
