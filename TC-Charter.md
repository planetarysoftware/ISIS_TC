# ISIS Technical Committee (TC) Charter

## Section 1. Guiding Principle.

The Integrated Software for Imagers (ISIS) Technical Committee will operate
transparently, openly, inclusively, collaboratively, and ethically.
Project proposals, timelines, and status must not merely be open, but also
easily visible to outsiders.

## Section 2. Evolution of ISIS Software Project Governance.

Most large, complex open source communities have both a business and a
technical governance model. ISIS’s technical leadership
is the Technical Committee (“TC”). ISIS’s business
leadership is comprised of the USGS ASC Management Team.

This Technical Committee Charter reflects carefully constructed balanced roles
for the TC and the ASC Management Team in the governance of the ISIS Software
Package. The charter amendment process is the means by which the TC
proposes changes to this charter using simple majority of the full TC, the
proposed changes being subject to review and approval by the ASC Management
Team. The ASC Management Team may additionally make amendments to the TC
charter at any time, though the ASC Management Team will not interfere with
day-to-day discussions, votes or meetings of the TC.

## Section 3. ASC Management Team’s Role in Setting the ISIS Software Project’s Strategic Direction.  

The ASC Management Team will set the overall TC Policy. The policy will
describe the overarching scope of the ISIS Software Project initiative,
ISIS’s technical vision and direction and project release expectations in
the form of expected cadence and intent. The ASC Management Team will use
the TC as a delegate body for governing technical implementation,
individual project scope and direction while they remain within the scope
and direction of the policies as described in the TC Policy document and
approved by the ASC Management Team.

In setting overall technical vision and direction, the ASC Management Team
will maintain final judgement on the inclusion of capability within the ISIS
Software Package. Capability can be code, processing pipelines, or services
to be added to an existing top level project or as a new top level project
under the ISIS Software Project. The TC will provide guidance to
the ASC Management Team concerning the technical feasibility and
maintainability of projects to support the ASC Management Team in making
an informed decision.

## Section 4. Establishment of the TC.

TC memberships are not time-limited. There is no maximum size of the TC.
The size is expected to vary in order to ensure adequate coverage of important
areas of expertise, balanced with the ability to make decisions efficiently.
The TC must have at least three members.

There is no specific set of requirements or qualifications for TC
membership beyond these rules. The TC may add additional members to the
TC by a standard TC motion and vote. A TC member may be removed from the
TC by voluntary resignation, by a standard TC motion, or in accordance to the
participation rules described below.

Changes to TC membership should be posted in the agenda, and will be then discussed
at the next TC meeting. Any vote to change the TC membership must remain open
for at least a month.

The TC may, at its discretion, invite any number of non-voting observers to
participate in the public portion of TC discussions and meetings.

The TC shall meet regularly using tools that enable participation by the
community (e.g. monthly on a Google Hangout On Air, or through any other
appropriate means selected by the TC). The meeting shall be directed by
the TC Chairperson. Responsibility for directing individual meetings may be
delegated by the TC Chairperson to any other TC member. Minutes, or an
appropriate recording, shall be taken and made available to the community
through accessible public postings.

TC members are expected to regularly participate in TC activities.

In the case where an individual TC member -- within any three-month period --
attends fewer than 25% of the regularly scheduled meetings, does not
participate in TC discussions, *and* does not participate in TC votes, the
member shall be automatically removed from the TC. The member may be invited
to continue attending TC meetings as an observer.

## Section 5. Responsibilities of the TC.  

Subject to such policies as may be set by the ASC Management Team, the TC is
responsible for all technical development within the ISIS Software Project,
including:

* Setting release dates.
* Release quality standards.
* Technical direction.
* Project governance and process (including this policy).
* GitHub repository hosting.
* Conduct guidelines.
* Maintaining the list of additional Collaborators.
* Development process and coding standards.
* Mediating technical conflicts between Collaborators.

The TC will define the ISIS Software Project's release vehicles and serve as
ISIS Software Project’s primary technical liaison body with external open
source projects, consortiums and groups.

## Section 6. ISIS Software Project Operations.

The TC will establish and maintain a development process for ISIS Software
Package's Projects. The development process will establish guidelines
for how the developers and community will operate. It will, for example,
establish appropriate timelines for TC review (e.g. agenda items must be
published at least a certain number of hours in advance of a TC
meeting).

There will be multiple Projects under the ISIS Software Project organized by
modules or subsystems. The TC is responsible for organizing the Project
structure, including possibly the creation and alignment of sub-Projects.
Each Project must be within such policies as may be set by the ASC
Management Team, have a well-defined scope and must work within that scope.
The development process will provide for Projects to follow the lifecycle
process as described in the [Project Lifecycle][] document. The development
process will include a process for the TC to oversee and approve changes
in the lifecycle of a Project, which will include consideration of the
following criteria:

* Cleanliness of code base
* Ample and diverse Contributors and Collaborators to assure vitality of
the project.
* Stability (e.g. presence of test suites, stable APIs and use of an
  appropriate source-code control system).
* Predictability of releases
* Alignment with ISIS Software Project’s goals and priorities.

The TC and entire technical community will follow any processes as may
be specified by the ASC Management Team relating to the intake and license
compliance review of contributions.

## Section 7. Voting

For internal project decisions, Collaborators shall operate under Lazy
Consensus. The TC shall establish appropriate guidelines for
implementing Lazy Consensus (e.g. expected notification and review time
periods) within the development process.

The TC follows a [Consensus Seeking][] decision making model. When an agenda
item has appeared to reach a consensus the moderator will ask "Does anyone
object?" as a final call for dissent from the consensus.

If an agenda item cannot reach a consensus a TC member can call for
either a closing vote or a vote to table the issue to the next meeting.
The call for a vote must be seconded by a majority of the TC or else the
discussion will continue.

For all votes, a simple majority of all TC members for, or against, the issue
wins. A TC member may choose to participate in any vote through abstention.

Note that, in addition to requiring a simple majority vote of the TC, all
changes to this charter are also subject to approval from the ASC
Management Team.

## Section 8. Project Roles

The ISIS Software Project Git repository is maintained by the TC and
additional Collaborators who are added by the TC on an ongoing basis.

Individuals making significant and valuable contributions,
“Contributor(s)”, are made Collaborators and given commit-access to the
project. These individuals are identified by the TC and their addition
as Collaborators is discussed during the monthly TC meeting.
Modifications of the contents of the Git repository are made on a
collaborative basis as defined in the development process.

Collaborators may opt to elevate significant or controversial
modifications, or modifications that have not found consensus to the TC
for discussion by assigning the `tc-agenda` tag to a pull request or
issue. The TC should serve as the final arbiter where required. The TC
will maintain and publish a list of current Collaborators by Project, as
well as a development process guide for Collaborators and Contributors
looking to participate in the development effort.

## Section 9. Definitions

* **Contributors**: contribute code or other artifacts, but do not have
the right to commit to the code base. Contributors work with the
Project’s Collaborators to have code committed to the code base. A
Contributor may be promoted to a Collaborator by the TC. Contributors should
rarely be encumbered by the TC and never by the ASC Management Team.

* **Project**: a technical collaboration effort, e.g. a subsystem, that
is organized through the project creation process and approved by the
TC.

[Project Lifecycle]: https://github.com/USGS-Astrogeology/ISIS_TC/blob/master/Project-Lifecycle.md
[Consensus Seeking]: http://en.wikipedia.org/wiki/Consensus-seeking_decision-making
[Condorcet]: http://en.wikipedia.org/wiki/Condorcet_method
[Single Transferable Vote]: http://en.wikipedia.org/wiki/Single_transferable_vote
