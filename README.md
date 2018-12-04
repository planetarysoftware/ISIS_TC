# The ASC Software Organization Technical Steering Committee

The ASC Software Organization Technical Steering Committee (TSC) is the technical
governing body of the ASC Software Organization. It is described in the
[TSC Charter][].

## TSC Scope

**The TSC is responsible for the ASC Core (ISIS3) project, a number of projects
depended upon by ASC Core (ISIS3) project, and a number of adjacent projects.**

The TSC exercises autonomy in managing its responsibilities and seeks agreement
from the ASC Management Team on any change to the scope of those
responsibilities as defined below.

### ASC Core

*ASC Core* is defined as the contents of the repository located at
<https://github.com/USGS-Astrogeology/ISIS3>. This is the location of the ISIS3 low-level API and applications. As the ASC modularized ISIS3 and explores potential name changes this document will be updated to point to the ASC core software capabilities.

### Dependent Projects

Additional projects fall within the TSC's scope of responsibility which are
dependencies of ASC Core in that they are **required** to plan, test, build,
document and ship ASC Software releases.

These projects are located in the following repositories:

* https://github.com/USGS-Astrogeology/isis3_dependencies
* https://github.com/USGS-Astrogeology/TSC
* https://github.com/USGS-Astrogeology/eal - currently under incubation

### Adjacent Projects

The TSC is responsible for a number of projects that are not strictly required
to plan, test, build, document and ship ASC Core releases. Projects that are
_adjacent_ are either created from within the technical organization managed by
the TSC or are adopted into that organization from outside.

In the case of adopting existing projects, once the TSC has decided that
adoption appropriate, it should seek agreement from the ASC Management Team
for such adoption as it impacts on the scope of technical activities of the
Foundation.

If the ASC Management Team wishes to adopt an existing project, it must
seek agreement from the TSC that such adoption is appropriate and that any
changes to scope that it entails are acceptable.

Current adjacent projects that are within the TSC's scope of responsibility
include:

* https://github.com/USGS-Astrogeology/CSM-CameraModel
* https://github.com/USGS-Astrogeology/csm
* https://github.com/USGS-Astrogeology/CSM-Swig
* https://github.com/USGS-Astrogeology/autocnet
* https://github.com/USGS-Astrogeology/plio
* https://github.com/USGS-Astrogeology/PyHAT
* https://github.com/USGS-Astrogeology/ISIS3_mission_processing_scripts

### List of TSC Responsibilities

The TSC exercises autonomy in setting up and maintaining procedures, policies,
and management and administrative structures as it deems appropriate for the
maintenance and operation of these projects and resources.

Included in the responsibilities of the TSC are:

* Managing code and documentation creation and changes for the listed projects
  and resources
* Setting and maintaining standards covering contributions of code,
  documentation and other materials
* Managing code and binary releases: types, schedules, frequency, delivery
  mechanisms
* Making decisions regarding dependencies of the ASC Core project,
  including what those dependencies are and how they are bundled with source
  code and releases
* Creating new repositories and projects under the _USGS-Astrogeology_ GitHub organization
  as required
* Setting overall technical direction for the ASC Core project, including
  high-level goals and low-level specifics regarding features and functionality
* Setting and maintaining appropriate standards for community discourse via the
  various mediums under TSC control
* Setting and maintaining governance rules for the conduct and make-up of the
  TSC, Working Groups and other bodies within the TSC's domain

Many of these responsibilities will be delegated by the TSC to appropriate
bodies such as the Working Groups.

## TSC Members

TSC members are responsible for top level technical community concerns. The role
is mostly administrative and is responsible for admitting new Top Level
Projects, Top Level Working Groups, and advocating for any needs in the
technical side of the foundation to the ASC Management Team.

TSC members can nominate new members at any time. Candidates for membership tend
to be people who have a competancy for community management and a high tolerance
and patience for process minutiae as the TSC delegates most of its responsibilities
to other projects and working groups.

A [current list of TSC members](https://github.com/USGS-Astrogeology/TSC/blob/master/Members.md)
is maintained in the main TSC repository.

## Strategic Initiatives

At any one time the ASC Software projects have a number of strategic initiatives
underway.  The goal of the TSC is to have a champion for each of these
initiatives and to support the initiatives in order to enable their
success.

For more information look here:
[Strategic Initiatives](https://github.com/USGS-Astrogeology/TSC/blob/master/Strategic-Initiatives.md)

## Top-Level WGs and TLPs

* [Working Groups](WORKING_GROUPS.md)
* Top-Level Projects
 * Core TLP
  * Core WGs (for example, streams)

## Policy Change Proposal Process

The ASC TSC is chartered to oversee the technical governance of all Top
Level Projects and Working Groups under the ASC Software Organization. The TSC
establishes the default governance, conduct, and licensing policies for all Top
Level Projects. Top Level Projects and Working Groups have broad powers of
self-governance.

To propose a change or addition to policies or processes that are intended to
cover all Top Level Projects and Working Groups in the foundation, a PR should
be opened in the `USGS-Astrogeology/TSC` repository.

The pull request can be labeled `tsc-agenda` to request that it be put on the
agenda for the next TSC meeting.

The ASC Management Team retains certain rights (especially
legal considerations). If the TSC endorses a proposal, they will escalate to the
ASC Management Team when required to do so.

In some cases, existing individual groups have the right to refuse changes to
their charters. The TSC can not mandate existing working groups alter their
charters. If such a situation arises, the TSC may decide to revoke the group's
charter.

[TSC Charter]: https://github.com/USGS-Astrogeology/TSC/blob/master/TSC-Charter.md
[Project Lifecycle.md]: ./Project-Lifecycle.md
