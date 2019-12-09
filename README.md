# The Integrated Software for Imagers and Spectrometers Technical Committee

The Integrated Software for Imagers and Spectrometers Technical Committee (TC)
is the technical governing body of the ISIS Software Package. It is described
in the [TC Charter][].

## TC Scope

**The TC is responsible for the ISIS project, a number of projects
depended upon by ISIS project, and a number of adjacent projects.**

The TC exercises autonomy in managing its responsibilities and seeks agreement
from the ASC Management Team on any change to the scope of those
responsibilities as defined below.

### ISIS

*ISIS* is defined as the contents of the repository located at
<https://github.com/USGS-Astrogeology/ISIS3>. This is the location of the ISIS
low-level API and applications. As the ASC continues to modularize ISIS and
explores potential name changes this document will be updated appropriately.

### Dependent Projects

Additional projects fall within the TC's scope of responsibility which are
dependencies of ASC Core in that they are **required** to plan, test, build,
document and ship ASC Software releases.

These projects are located in the following repositories:

* https://github.com/USGS-Astrogeology/isis3_dependencies

### Adjacent Projects

The TC is responsible for a number of projects that are not strictly required
to plan, test, build, document and ship ISIS releases. Projects that are
_adjacent_ are either created from within the technical organization managed by
the TC or are adopted into that organization from outside.

In the case of adopting existing projects, once the TC has decided that
adoption appropriate, it should seek agreement from the ASC Management Team
for such adoption as it impacts the scope of technical activities.

If the ASC Management Team wishes to adopt an existing project, it must
seek agreement from the TC that such adoption is appropriate and that any
changes to scope that it entails are acceptable.

Current adjacent projects that are within the TC's scope of responsibility
include:

### List of TC Responsibilities

The TC exercises autonomy in setting up and maintaining procedures, policies,
and management and administrative structures as it deems appropriate for the
maintenance and operation of these projects and resources.

Included in the responsibilities of the TC are:

* Managing code and documentation creation and changes for the listed projects
  and resources
* Setting and maintaining standards covering contributions of code,
  documentation and other materials
* Managing code and binary releases: types, schedules, frequency, delivery
  mechanisms
* Making decisions regarding dependencies of the ISIS project,
  including what those dependencies are and how they are bundled with source
  code and releases
* Setting overall technical direction for the ISIS project, including
  high-level goals and low-level specifics regarding features and functionality
* Setting and maintaining appropriate standards for community discourse via the
  various mediums under TC control
* Setting and maintaining governance rules for the conduct and make-up of the
  TC, Working Groups and other bodies within the TC's domain

Many of these responsibilities will be delegated by the TC to appropriate
bodies such as the Working Groups.

## TC Members

TC members are responsible for top level technical community concerns. The role
is mostly administrative and is responsible for admitting new Top Level
Projects, Top Level Working Groups, and advocating for any needs in the
technical side of the foundation to the ASC Management Team.

TC members can nominate new members at any time. A [current list of TC members](https://github.com/USGS-Astrogeology/ISIS_TC/blob/master/Members.md)
is maintained in the main TC repository.

## Strategic Initiatives

At any one time the ASC Software projects have a number of strategic initiatives
underway.  The goal of the TC is to have a champion for each of these
initiatives and to support the initiatives in order to enable their
success.

For more information look here:
[Strategic Initiatives](https://github.com/USGS-Astrogeology/ISIS_TC/blob/master/Strategic-Initiatives.md)

## Top-Level WGs and TLPs

* [Working Groups](WORKING_GROUPS.md)
* Top-Level Projects
 * Core TLP
  * Core WGs (for example, streams)

## Policy Change Proposal Process

The TC is chartered to oversee the technical governance of all Top
Level Projects and Working Groups under the ISIS Software Package. The TC
establishes the default governance, conduct, and licensing policies for all Top
Level Projects. Top Level Projects and Working Groups have broad powers of
self-governance.

To propose a change or addition to policies or processes that are intended to
cover all Top Level Projects and Working Groups in the foundation, a PR should
be opened in the `USGS-Astrogeology/ISIS_TC` repository.

The pull request can be labeled `tc-agenda` to request that it be put on the
agenda for the next TC meeting.

The ASC Management Team retains certain rights (especially legal considerations).
If the TC endorses a proposal, they will escalate this proposal
to the ASC Management Team when required to do so.

In some cases, existing individual groups have the right to refuse changes to
their charters. The TC cannot mandate existing working groups alter their
charters. If such a situation arises, the TC may decide to revoke the group's
charter.

[TC Charter]: https://github.com/USGS-Astrogeology/ISIS_TC/blob/master/TC-Charter.md
[Project Lifecycle.md]: ./Project-Lifecycle.md
