# 2024 - 2029 Strategic Plan

## Executive Summary
This document outlines the 2023-2028 strategic plan for the Astrogeology Science Center software section. The plan describes four overlapping thematic areas of effort: Cloud & Software as a Service, Sensor Models & Photogrammetric Control, Improved Usability & Independently Identified Capabilities, and Documentation & User Training. Within each thematic area, individual capabilities are organized as must-have, should-have, and could-have within the next five years.

This document also describes the intended audience and proposes that this document be used to support the development and related funding decisions of the ASC software portfolio over the coming five years. The process used to generate this document is described to provide context to the reader about from whom information was sourced and how this document was drafted. This document describes how funding is currently organized. Finally, a plan for the longer-term maintenance and update cadence of the document is provided.

## Intended Audience and Use
This document is intended for contributors to the ASC software portfolio who may be proposing new work, contributors seeking to make changes to component of the software portfolio under existing work agreements, software management as a tool to help prioritize proposed efforts under larger funding agreements, and users with an interest in the long-term trajectory of software within the ASC portfolio. This document describes the methods used for information gathering and the organizational approach used. This documented also provides context for how tasks have historically been categorized under previous funding agreements and provide forward guidance for the approximate distribution of tasks during future fiscal years. 

The ASC development team and ASC technical management are more than happy to collaborate with and support the broader contributing community that may wish to propose to a funding opportunity to make improvements or modifications on software within the ASC software portfolio. This document should serve as a community organized guide to the capabilities and thematic areas for development that have been identified as high value. 

## Development and Organization
This document is a snapshot of work initiation in July 2021 to collect ideas, input, and direction from the ASC software development team, contributors to ASC software development projects, the ISIS Technical Committee, and the broad ISIS user base. The members of these groups participated in close to a dozen in-person brainstorming and context building sessions in order to build a framework from which this LTP has been developed. 

The ASC software lead has been tasked with collating the information gathered from the contributor and user community. Once collated, the identified thematic development areas have been brought into alignment with some of the driving planetary science community documents (e.g., [NASA Planetary Decadal (2013-2022)](https://science.nasa.gov/science-red/s3fs-public/atoms/files/Planetary_DS.pdf), [NASA PDE Recommendations and Findings (2021)](https://science.nasa.gov/files/science-red/s3fs-public/atoms/files/PDE%20IRB%20Final%20Report.pdf), [ISIS SAT Review (2018)](https://github.com/USGS-Astrogeology/softwaremanagement/tree/master/SpecialActionTeam_Review), [NASA Strategy for Data Management and Computing  for Groundbreaking Science 2019-2024](https://science.nasa.gov/science-red/s3fs-public/atoms/files/SDMWG%20Strategy_Final.pdf), [OMB M-13-13, Open Data Policy - Managing Information as an Asset](https://obamawhitehouse.archives.gov/sites/default/files/omb/memoranda/2013/m-13-13.pdf), [OMB M-16-21](https://obamawhitehouse.archives.gov/sites/default/files/omb/memoranda/2016/m_16_21.pdf)) and with the long-term planning documents from other ASC sections. Specifically, many of the photogrammetric control and sensor model improvements are linked to product generation priorities that have been drawn from documents such as the [Lunar Critical Data Products SAT report](https://www.lpi.usra.edu/mapsit/standup-committees/LCDP-SAT-REPORT-20211110.pdf), the [Artemis  III SDT draft report](https://lunarscience.arc.nasa.gov/artemis-sdt/downloads/Artemis_III_SDT_DRAFT_Report_STM.pdf), and the previously linked decadal. Capability prioritization (described below) was ultimately done by the ASC software lead, with significant input from the aforementioned group of people during brainstorming and context building sessions.

The breadth of capability development desired by the user community and development team exceeds the capabilities of the ASC software development team. This is one indicator that a thriving software portfolio exists with high user engagement. One organizational approach would be to be exclusive and remove tasks or development areas which are likely outside the reasonable scope of effort or expertise of the core development team (primarily ASC employees). Instead, this document is organizing capabilities first into larger thematic areas and then into must-do, should-do, and can-do categories with the understanding that can-do activities are likely to no be completed by the ASC development team in the next five years unless (a) unforeseen changes occur that move capabilities into different categories or (b) the addition of can-do capabilities are a natural and low effort addition to other higher priority work. In our view, it is important to explicitly describe the organizational structure and limitations of time in order to maintain shared expectations with all readers.

Capabilities identified in this document are presented in a form like a traditional user story. The general form is 'In five years, <user> will be able to <activity> to <outcome>'.  This form is being used because it is exceptionally concrete. A reader is immediately aware of the capability that a user will be using and anyone wishing to develop said capability has at least a minimal definition of done for their proposed task. Where appropriate, this document identified precursor work, but this document is neither prescient nor inclusive. Readers should feel free to identify necessary pre-work and [open an issue] to discuss those ideas with others.

Finally, this document makes every effort to explicitly link capabilities to identified use cases to ensure the highest likelihood of adoption of capabilities. As a development group, we have found the highest user satisfaction comes from tight integration and high communication during the development process. It is important to support the high communication development model at all levels of the development process, from this document to the fix of a bug.


## Thematic Development Areas

### Cloud and Software as a Service
##### Context and Description:

##### In the next five years, the ASC software portfolio must:
1. include cloud enabled services with well documented APIs that are accessible by end users. One example of this is the current work to cloud enable the SPICE server with support for USGSCSM and ISIS style sensor models. These services should be documented such that they can be deployed by anyone to the same cloud hosting provider that ASC deploys them to [^clouddeploy].
    - Projects using this capability: (1) most, if not all, internal users transitioning to using the remote, cloud enabled SPICE service, (2) control projects using AutoCNet transitioning to using cloud SPICE services, (3) STAC search, data/metadata management, and catalog APIs, (4) nomenclature capabilities as more accessible APIs, and (4) other unidentified cloud enabled services which should be able to link to at least one project or user community that will make use of the service.
    - Supporting community policy and finding documents:
        - OMB M-13-13 Build information systems to support interoperability and information accessibility; (a) the system must be scalable and flexible.
        - SAT Finding 9: Found that the code is being developed openly, as requested. The natural extension to this finding is to provide open and accessible SaaS and APIs.
        - SAT Finding 20: Broadening the SPICE web server
        - NASA PDE Recommendation 10: The prioritization of cross organizational APIs, as opposed to individually developed APIs, benefits the community.
        - NASA SDMCGS 2.3: Support the use of commercial cloud capabilities for open science to make data accessible to a diverse et of users.

1. provide user accessible data necessary to use libraries in the software portfolio via the cloud.
    - Projects using this capability: (1) all users performing an installation of our code base.
    - Supporting community policy and finding documents:
      - SAT Finding 8: Increase code modularity
      - NASA PDE Findings 40, 41, 42: Cloud and HPC are enabling technologies, pending adoption of data interoperability and usability concerns (as identified within the PDE findings). Software should be available and immediately usable as data issues are incrementally addressed.
      - NASA SDMCGS 2.3: Support the use of commercial cloud capabilities for open science to make data accessible to a diverse et of users.

##### In the next five years, the ASC software portfolio should:

1. release a cloud deployed AutoCNet with *qnet* style point/measure visualization and analysis. This need not be an AutoCNET SaaS solution for users and can rather be components such that users can (re)create the same processing environment.
    - Projects using this capability: (1) any remote (over-the-wire, where data are not local) control work can make use of a *qnet* style visualization solution, (2) control work using AutoCNet, (3) other SaaS solutions identified in the future can make use of the lessons learned.
    - Supporting community policy and finding documents:
      - NASA PDE Findings 40, 41, 42: Cloud and HPC are enabling technologies, pending adoption of data interoperability and usability concerns (as identified within the PDE findings). Software should be available and immediately usable as data issues are incrementally addressed.

1. provide explicit descriptions attached to each ASC software portfolio library describing if said library can be cloud enabled and if the library has been cloud enabled.
    - Projects using this capability: All users and developers and the bringing the lifecycles into alignment with expectations supports everyone.
      -  CSM Stack Software 

    - Supporting community policy and finding documents:
      - OMB M-16-21 5.2.D & 5.2.F: Community engagement and project documentation require descriptions of project status and agency engagement levels.
        
##### In the next five years, the ASC software portfolio could:
1. Develop and maintain services, software to support interoperable standards and cloud optimized data streaming. 
    - Projects using this capability: An users wishing to move from desktop to HPC environments.
    - Supporting community policy and finding documents:
        - OMB M-1313 (Build information systems to support interoperability and information accessibility; (a) the system must be scalable and flexible.)

### Sensor Models & Photogrammetric Control
##### In the next five years, the ASC software portfolio must:
1. have fully adopted ALE, SpiceQL, and the updated ISIS ingestion programs. This includes the deprecation of currently deployed capabilities across **all** sensor models. This also incudes the development, testing, and deploy of CSM sensor models for past, current, and future missions.
    - Projects using this capability: All ISIS users will be using this capability. Implementation of this capability removes the dual maintenance burden that currently exists by having two (legacy and new) implementations concurrently supported.
    - Supporting community policy and finding documents:
      - SAT Finding 8: Increase code modularity. (This work, once completed, executes the modularization plan for SPICE data management and usage within the ISIS code base.)

1. provide automated solutions for ground control point selection using varied ground truth data sets such as LiDAR.
    - Projects using this capability: All control projects include, but not limited to Kaguya TC, CTX, etc.
    - Supporting community policy and finding documents:
      - SAT Finding 19: Automated image matching and feature recognition

1. include tools of workflows for adding observations to existing control projects.
    - Projects using this capability: THEMIS, CTX, LROC-NAC, Europa Clipper (presumptive)
    - Supporting community policy and finding documents:
      - SAT Finding 19: Automated image matching and feature recognition


##### In the next five years, the ASC software portfolio should:
1. create prototype examples of CSM sensor models for (1) multi- and hyper-spectral spectrometers and (2) incredibly long exposure time observations when one wants fine grained timing control.
    - Projects using this capability: Continued CSM development efforts as this capability completes demonstration of the CSM across all major sensor types we encounter. 
    - Supporting community policy and finding documents:
        - OMB M-13-13 Build information systems to support interoperability and information accessibility.
        - OMB M-19-15 Implementation Update 3.2: the computer code for custom analysis of data (in this case sensor models), should be made available for subsequent analysis by the public (i.e., open source sensor models)

1. include tools for improved interoperability between the NASA Ames Stereopipeline, ISIS, and SocetGXP using the Community Sensor Model (CSM).
    - Projects using this capability: ASC APPL group DTM generation
    - Supporting community policy and finding documents:
      - OMB M-13-13 Build information systems to support interoperability and information accessibility.

1. enhance the existing bundle adjustment library to support sequential photogrammetric control estimation and adjustment.
    - Projects using this capability: Large global solutions, regional solutions with high resolution data (LROC NAC or HiRISE control), and missions with sequentially updated data (e.g., THEMIS IR or to be acquired Europa Clipper data).
    - Supporting community policy and finding documents:
      - See ASC products LTP. Specifically, the need to develop large spatial extent foundational data products for the Moon and Mars.

##### In the next five years, the ASC software portfolio could:
1. support simultaneous photogrammetric control solutions for Lidar and image observation data.
    - Projects using this capability: Control projects where lidar data are available.
    - Supporting community policy and finding documents:
      - See ASC products LTP. Specifically, the need to develop foundational data products for the Moon.

1. improve GIS footprint generation
    - Projects using this capability: control projects and analysis ready data generation pipelines all benefit from improvements in GIS ready footprint generation.
    - Supporting community policy and finding documents:
      - ??

1. support adding increased metadata to points and measures within control networks including, but not limited to photometric and/or image resolution metadata.
    - Projects using this capability: Photogrammetric control projects
    - Supporting community policy and finding documents:
      - ??

1. provide additional capabilities for control network analysis leveraging weighted image overlap graphs.
    - Projects using this capability: Photogrammetric control projects
    - Supporting community policy and finding documents:
      - ??

### Improved Usability & Independently Identified Capabilities

##### Context and Description:
##### In the next five years, the ASC software portfolio must:
1. release one or more versions of ISIS making use of a standard and stand-alone Input/Output library (either off-the-shelf or homegrown) with support for performance enhancing capabilities (e.g., image pyramids).
    - Projects using this capability: All ISIS users benefit from this capability due to improved performance, reduced maintenance costs (intended consequence), and standardization that should improve interoperability.
    - Supporting community policy and finding documents:
        - OMB M-13-13: III.1.a Use machine-readable and open formats and prioritize the the use open, non-proprietary data formats with no usage restrictions.
        - NASA PDE Recommendation 51: tools should be developed translate common planetary formats and standards to support adoption by other science communities.

1. provide consistent installation experiences for users on explicitly supported packages including improved dependency management, installation instructions, and installation tooling.
    - Projects using this capability: Given the complex dependency versioning interactions on the ISIS project, this the prime candidate for removing installation friction though all ASC projects would benefit from lessons learned.
    - Supporting community policy and finding documents:
      - SAT Finding 12 & 13: Broadly identify installation concerns and the need for an ever improving installation experience.

1. standardize onto a single set of web technologies and frameworks to support data accessibility, discoverability, and access by users such that data access portals can be developed at lower costs across project areas
    - Projects using this capability: All ASC Data section releases seeking custom online solutions (e.g., terrestrial analogs data portal, nomenclature, PDS web mapping and processing portal, geologic mapping data portal, etc.)
    - Supporting community policy and finding documents:
      - OMB M-16-16 III.1.a Open data must be available in accessible, searchable, and convenient formats
      - NASA PDE Finding 50 / Recommendation 36: Terrestrial analog data do not have a primary repository. (This effort tangentially addresses this through the development and support of a clearing house of terrestrial analog data.)
  

##### In the next five years, the ASC software portfolio should:

1. provide an updated method for unique observation identification (i.e., serial numbers).
    - Projects using this capability: Described in the context of control. Needs additional project linkages if work is undertaken.
    - Supporting community policy and finding documents:
      - ??

1. provide improved photometric modelling capabilities including examples of off-the-shelf tools for large data visualization and analysis, and support for the inclusion of atmospheric and/or band information in the analysis process.
    - Projects using this capability: Improved generation of cosmetically appealing image mosaics
    - Supporting community policy and finding documents:
      - See ASC products LTP. Specifically, the need to develop large spatial extent foundational data products for the Moon and Mars.

1. begin supporting remote data visualization and analysis include, but not limited to observation and control network data and metadata. 
    - Projects using this capability: AutoCNet based control solutions will immediately benefit from this work. Any remote workers and users wishing to setup remote (perhaps on HPC resources) solutions.
    - Supporting community policy and finding documents:
      - ??

1. package off-the-shelf and/or custom solutions for the generation of analysis ready data and associated metadata including tooling for processing, metadata generation, and metadata management. Metadata management includes the need to update metadata and manage sematic linkages between data sets.
    - Projects using this capability: All analysis ready data (ARD) releases.
    - Supporting community policy and finding documents:
      - OMB M-16-16: I.Open Data.Described Open / III.1.d data are fully described so that consumers can assess their usability through common core and extensible  metadata. 
      - OMB M-19-15: Implementation Update 2.2 Agencies should provide users with adequate data documentation to support a user's determination of fitness-for-use
      - NASA PDE Recommendation 32: Recommends that NASA should develop archives for analysis ready data (ARD). This work is facilitating technology for building one such archive.
      - NASA PDE Recommendation 53: Recommends that data linkages and types are clearly documented. This work is facilitating technology.

##### In the next five years, the ASC software portfolio could:
1. provide tools for the extraction of limb profiles and limb topography to improve photogrammetric control capabilities and improve shape estimation, primarily for flyby missions.
    - Projects using this capability: Science investigations
    - Supporting community policy and finding documents:
      - ??

1. update the ISIS library be callable using Unix style command line interfaces, (e.g., man spiceinit) in order to improve the sematic interoperability between ISIS tools and other standard Unix command line tools.
    - Projects using this capability: No projects explicitly use this capability. Instead, all users would potentially benefit from logical consistency across tools.
    - Supporting community policy and finding documents:
      - NASA PDE Finding 61: Many PDE elements are designed for expert users and should be made moe accessible. (This effort would align the use of the ISIS code base with unix standards, thereby removing the custom structure of current commands.)

1. include increased adoption of targeted parallelization efforts in order to improve single machine performance for tasks with long runtimes.
    - Projects using this capability: Potential benefit across a range of users
    - Supporting community policy and finding documents:
      - SAT Finding 16: Software optimization



### Documentation & User Training
##### Context and Description:
Documentation is a foundational piece of any software with a user base broader than the person who wrote the code. Documentation can take many forms, from the published manuals and books of old to a series of blog posts or YouTube videos demonstrating example usages. Currently, the ASC software portfolio maintains many different documentation types across an equally large number of locations. The documentation and user training thematic area for future work focuses first and foremost on centralizing the current offerings and future offerings. Centralization is not just a matter of having a single remote accessible location to discover and access documentation, but also the adoption of a standard organizational schema to ensure continuity in documentation across individual projects within the portfolio.

The overriding philosophy is that documentation needs to be pervasive across the above thematic areas so that technical and non-technical users can adopt our libraries and tools. 

The highest priority capabilities that must be realized over the next five years focus on improving the discoverability and readability of ASC documentation, as well as the democratization of said documentation by enabled (and ultimately soliciting) contributions from all users. Having this framework in place adds significantly to the value of work done under the should and could categories as that work will ultimately be more accessible. Capabilities that should be added in the next five years complement the existing documentation and make use of ASC published software as components in larger processing and/or analysis pipelines more accessible to users. Efforts that should be undertaken also support adoption of ASC services and the improved communication of expectations between developers and users by explicitly describing library maturity [^maturity]. Finally, capabilities that could be added in the next five years include usage tracking metrics and in-person trainings. This latter capability warrants a small amount of additional discussion.

The person-time cost to generate in-person learning experiences, particularly by persons without pedagogical training is quite high. The scope of impact from in-person training opportunities is limited by the number of persons in attendance and then further limited by the follow-on opportunities for those attendees to practice the skills learned. The development time of high quality, asynchronously accessible tutorials and learning examples, backed by a thriving question and answer community, for example via a Q&A website, can also be high. The ability for learners to not only use, but also asynchronously interact with other learners and project contributors is why this document prioritizes this type of documentation and learning over in-person activities.

This section does not link explicitly to projects that benefit because improved documentation is broadly impactful. This section also enumerates specific documentation tasks that are more granular than the policy and findings documents that explicitly support this effort. Therefore, instead of inlining references to those documents alongside each capability, those linkages are enumerate here:

- OMB M-16-21: 5.2F Provide documentation that includes the software status, intended purpose, expected activity cadence, license details, and technical usage details.
- OMB M-16-21: 5.2B Engage in open software development that includes making source code available and engaging the community to improve development outcomes
- SAT Finding 6: Task based workflow tutorials should be made available.
- NASA PDE Recommendation 10: NASA should prioritize the use of data/metadata standards including APIs. By extension, these standards and APIs need to be well documented, ideally using documentation standards (e.g., the OpenAPI specification), in order to be usable beyond the authors and/or maintainers of the API.
- NASA PDE Recommendation 50: The development of educational and documentation materials is essential to meet high priority user needs.
- NASA PDE Recommendation 54: Developer advocacy that includes means for developers to learn about API usage to support their work.
- NASA PDE Finding 67 / Recommendation 64: There are inadequate training opportunities for software users. This section addresses this finding directly.

##### In the next five years, the ASC software portfolio must:
1. work to increase adoption of CSM sensor models beyond SocetGXP in order to create a robust planetary user community around this standard.

##### In the next five years, the ASC software portfolio could
1. select off-the-shelf or develop and deploy metrics tracking for adoption of remotely accessible APIs (i.e., services).

1. initiate efforts to actively train novice users across communities (with a focus on reaching traditionally underserved communities) through workshops, office hours, or other face-to-face (digital or in-person) efforts. 

## Organization of Funding
Historically, the software development efforts at the ASC have been divided into three areas: Maintenance and Maintainability (M&M), Value-Adding, and Research. Maintenance and Maintainability tasks have accounted for between fifty-five and sixty percent of the overall work effort each year. These tasks include the release of our software portfolio to the community, maintenance of software library data areas, support sprints for our customers, Open-Source community development around ASC libraries, and iterative improvements to the code base such as migration of the ISIS tests to GTest or the modularization of the ISIS PVL and Blob classes into independently compilable libraries. Value-Adding tasks have accounted for between twenty-five and thirty-five percent of the overall work effort. These tasks have included efforts such as the development of Community Sensor Model (CSM) sensors, PDS4 support, and development and release of the Abstraction Library for Ephemerides (ALE). Finally, Research tasks account for between five and fifteen percent of the overall work effort in any given year. These tasks focus on developing and testing prototype capabilities that may or may not become a standard part of the ASC software portfolio. In previous fiscal years, tasks have included change detection, automated control network generation, bundle adjustment using the CSM, and photometric data analysis and correction capabilities.

Significant improvements to the development process by the ASC development team and wider community of contributors have supported the gradual reduction in the total cost of M&M tasks while improving both the developer and end-user experience. Our goal is to continue to seek strategic process efficiencies in order to either accelerate M&M tasks (such as the continued reduction in testing data volumes which in turn better supports robust software deploys and non-ASC developer participation) or to slowly transition work to the Value-Adding area. In other words, by automating a non-trivial amount of daily work, adopting industry norms for many development processes, and normalizing user expectations for maintenance and release cadence work, we can and will reallocate those work hours to other tasks.

The Research area of the portfolio has been successful in incubating capabilities that have successfully transitioned into our Value-Adding area. Therefore, the plan is to maintain five to fifteen percent of total work effort in those tasks. In contrast to the current model, moving forward research tasks will be time limited to at most ~5% of the total work effort. The goal is to increase the diversity of research tasks. The downside to capping research tasks is that the timeline for transitioning from research to production may be extended, but the increased diversity should provide the ASC development group with improved flexibility to meet ever evolving community needs. Note also that research tasks can and should span the breadth of our portfolio and are not limited to traditional science only research operation. Research into new development, release, or data sharing processes, development frameworks, or other technical solutions are all valuable research contributions.

## Intended Long Term Plan Maintenance
In contrast with the previous software LTP, this document is intended to be updated annually with the following goals:
  - Do no harm. The current trajectory of multi-year efforts should be maintained, and projects should be fully completed unless a significant, program level change has been identified or a project scope has grown to an untenable level.
  - Maintain agility in strategic execution by supporting the movement of development goals between the must-do, could-do, and should-do categories on an annual basis.
  - Develop and maintain a sixth-year backlog of development ideas that are agilely incorporated into existing thematic areas / categories, or cycle off as a tool for seeding the annual updating of this document.

[^clouddeploy]: In our experience, generalized deploy anywhere including cloud solutions are frequently homegrown making them hard to maintain. Even a 'simple' solution like making a  Docker container available to users that is deployed to Amazon EKS (a Kubernetes cluster) causes friction on the deployer side (as they are not using some cloud native infrastructure they might want to use) and on the user side (as we would not be making the K8 configuration files available to end users.
[^maturity]: The description of library maturity also supports better classification of our releases as per USGS software release guidelines and brings the ASC software portfolio into full compliance with our release requirements.