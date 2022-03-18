# Process Overview

## Scope
This document was created to provide a quick overview of the `[Organization_Name]` Process. It highligts the most important aspects of the `[Organization_Name]` Process. For further details, please  use the links provided.

## Introducion
The `[Organization_Name]` Process, also called **The Way We Work**, it is described on the following documents:
* **[Rules of Engagement](./rules_of_engagement.md)** provides a detailed explanation of the rules that formed the `[Organization_Name]` Process:
  * [[Organization_Name] Governance](./rules_of_engagement.md#governance)
  * [Membership Benefits](./rules_of_engagement.md#membership-benefits)
  * [[Organization_Name] Roles](./rules_of_engagement.md#what-to-expect-from-the-organizataion-roles)
  * [Development Proces](./rules_of_engagement.md#process)
  * [Documentation - Versioning](./rules_of_engagement.md#documentation)
  * [Copyright Rules](./rules_of_engagement.md#copyright)
  * [Licensing Policy](./rules_of_engagement.md#licenses)

* **[Guidelines for Working Group Chairs](./guidelines-for-wg-chairs.md)** is a document that contains details on specific tasks of the `[Organization_Name]` Process that is normally  enforced by the Working Group Chairs. It contains procedures such as:
  * [Technical Decision Making](./guidelines-for-wg-chairs.md#technical-decision-making)
  * Using Supermajority vote to achieve agreement
  * [[Organization_Name] Approval Process](./guidelines-for-wg-chairs.md#omp-approval-process) which is used to approve contributions presented to the Working Groups 
  * [[Organization_Name] Work Flow](./guidelines-for-wg-chairs.md#github-flows)

* **[Working Group Chair Check List](./wg-chair-check-list.md)** as it name indicates, it contains a list of activities to be performed by the Working Group Chairs.

* **`CONTRIBUTING.md`** is a document that describes how to contribute on a particular repository. Each repository used by the Working Group should have its own `CONTRIBUTING.md` document.

* **`Release Planning`** the content of this document can be easily presented in a table that indicates the milestones for each Working Group deliverable. This content represents what the group is planning to deliver and by when.

## Rules of Engagement
As described above the **[Rules of Engagement](./rules_of_engagement.md)** provides a detailed overview of the `[Organization_Name]` Process, Procedures and Guidelines. 
The following sub-sections provide a high level summary of the technical aspects described in the document.

### Organization Structure
`[Organization_Name]` is headed by the **[Steering Committee](./rules_of_engagement.md#steering-committee)**, which is formed by the Senior Managers from the [Steering Members](https://open-manufacturing.org/). The **[Steering Committee](./rules_of_engagement.md#steering-committee)** meets once a week, biweekly, or monthly deals with the day to day activities to the Organizaton.
The **[Marketing Team](./rules_of_engagement.md#marketing-team)** is also formed by representatives from the Steering Members, it meets once a week, biweekly or monthly to discuss Marketing related topics.

The diagram below depictures `[Organization_Name]` Organigram.
<figure>
	<img src="images/omp_governance.svg" alt="`[Organization_Name]` Governance Structure">
	<figcaption>[Organization_Name] Governance Structure</figcaption>
</figure>

### Members Benefits
In the **[Rules of Engagement](./rules_of_engagement.md)** document, the section **[Membership Benefits](./rules_of_engagement.md#membership-benefits)** provides a detailed list of benefits for each Membership level.


### Working Group Charters
Companies that want to participate in a particular Working Group are required to sign the corresponding Working Group Charter. The current `[Organization_Name]` Working Group Charters are:

* [Working Group I Charter]()
* [Working Group II Charter]()
* [Working Group III Charter]()
* [Working Group IV Charter]()

### Work Packages
<figure>
	<img src="images/breakdown.svg" alt="[Organization_Name] Work Units">
	<figcaption>[Organization_Name] Work Units</figcaption>
</figure>

The **[Work Package](./rules_of_engagement.md#work-packages)** describes the scope of the work and expected deliverables. It must be ratified by the **[Steering Committee](./rules_of_engagement.md#steering-committee)** and it is assigned to a Working Group.

### Technical Specifications Developement
The diagram depictures a high level the process for developing Technical Specifications.

<figure>
	<img src="images/life_cycle.svg" alt="Specifications Life Cycle">
	<figcaption>Specifications Life Cycle</figcaption>
</figure>

Once the **[Work Package](./rules_of_engagement.md#work-packages)** has been defined, the **[Development](./rules_of_engagement.md#work-flow-for-technical-specifications-development)** work starts. After the development work is completed, the group will initiate the **[Consistency Review](./guidelines-for-wg-chairs.md#work-flow-for-technical-specifications-development)**, which is a process to formally evaluate the documentation prior final approval by the Working Group.
The **[Approval](./guidelines-for-wg-chairs.md#omp-approval-process)** of the Specifications is performed by the Working Group after completing the **[Consistency Review](./guidelines-for-wg-chairs.md#work-flow-for-technical-specifications-development)**.
Once the Group has formally approved the work under development, the deriverables need to be **[ratified](./guidelines-for-wg-chairs.md#work-flow-for-technical-specifications-development)** by the **[Organization Team](./rules_of_engagement.md#organization-team)**. The **[ratification](./guidelines-for-wg-chairs.md#work-flow-for-technical-specifications-development)** by the **[Technical Steering Committee](./rules_of_engagement.md#organization-team)** triggers the  **[Publication](./guidelines-for-wg-chairs.md#work-flow-for-technical-specifications-development)** of the corresponding deliverables.

#### Technical Document License
`[Organization_Name]` Process provide a **[License statement](./rules_of_engagement.md#technical-document-license)** that needs to be inserted in all documents published by the Working Groups.

### Software Code Development
The diagram below provides the process flow for code development.

![image](https://user-images.githubusercontent.com/3258579/136839210-fcd218ea-7227-407e-a5b2-4e4c555ad54d.png)

The process to approve Pull Requests is decided by each Working Group. This process is described in the **`CONTRIBUTING.md`** file available on each repository. In any case, `[Organization_Name]` recommends to follow the guidelines described in the **[Review & Approval Process](./guidelines-for-wg-chairs.md#[Organization_Name]-approval-process)**

#### Copyright and Licensing Best Practise
`[Organization_Name]` Process provides a set of guidelines on how to write and maintain **[Copyright](./rules_of_engagement.md#copyright)** statements with minimum effort. As well as how to best handling **[Software Licenses](./rules_of_engagement.md#licenses)** in `[Organization_Name]` repositories. If your project imports software code from a 3 party it is important to include the license as it is (without being modified) and ensure that the **[license is compatible](./rules_of_engagement.md#omp-software-license-policy)**.

#### Software License Policy
Contributors to `[Organization_Name]` repositories must be familar with **[Software License Policy](./rules_of_engagement.md#software-license-policy)**. This policy provides a set of simple rules related to Software Licenses that must be followed up by Contributors to the `[Organization_Name]` repositories.


### Semantic Versioning
`[Organization_Name]` published its deliverables: technical documents and, or software code, following **[Semantic Versioning](./rules_of_engagement.md#semantic-versioning)**, which provides a simple criteria to decide the version - Vx.y.z - of content to be released by the Working Groups.

### CONTRIBUTING.md
The `CONTRIBUTING.md` is a text file available in each `[Organization_Name]` repository. This file is created and approved by the corresponding `[Organization_Name]` Working Group. Its purpose is to describe how contribute to a particular repository. It can be adjusted as needed from one repository to another, even within the same Working Group. See an [example]() of a CONTRIBUTING.md file.

### Release Planning
Each Working Group should create and maintain its own Release Planning Document. This document in its simplest form, is a table (a Release Roadmap), which reflects the expectations about which features will be implemented and by when. See an [example]() of a Release file.