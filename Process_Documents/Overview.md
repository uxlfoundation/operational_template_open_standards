## Scope
This document provides process guidelines based on best practice and practical implementations.

### Introducion
This section provides a practical step by step guide on how to customize your Organization Process template in the [`Organization Operational Process`](Organization_Operational_Process.md)

* The preparation and approval of the Organization process is important to create a culture of openness, collaboration and a sense of forming a community.
* We recommend to follow up the following steps:

[Governance](/Organization_Operational_Process.md#governance)

> Note: Create a simple organigram of the Organization, listing:

  * The Technical Steering Committee, (TSC)
  * Committees Team created by the TSC
  * The Working Group(s), (WGs), and its Sub-Working Group(s), (TSC), (if any)

> Then, complete the function and meeting cadence for the groups listed in the diagram:

  * The [Technical Steering Committee](./Organization_Operational_Process.md#steering-committee):
    * it is formed by the [Steering Members](). 
    * it meets `week, biweekly, monthly` 
    * it deals with the day to day activities to the Organizaton.
  
  * The [Marketing Team](./Organization_Operational_Process.md#marketing-team)
    * it is also formed by representatives from the Steering Members, 
    * it meets once a `week, biweekly, monthly` 
    * it discuss Marketing related topics.

  * Other [Committee Team Name]()
    * it is formed by ...
    * it meets once a `week, biweekly, monthly` 
    * it is dedicated to ...

  * [Working and Sub Working Groups]()
    * Companies that want to participate in the Working Group(s) need to be a member of the Organization
      * Apply [here]() for Membership
      * [Membership Benefits](/Organization_Operational_Process#membership-benefits). This section provides a detailed list of benefits for each Membership type.

> Next steip is to define the Organization roles

* **[Organization Roles](./Organization_Operational_Process.md#organizataion-roles)**

This section provides a description of what tasks and behaviour is expected by the different roles in the organization: 
  
  * [Maintainers/Chairs](),
  * [Editors](), and
  * [Participants]().

* **[Work Package](./Organization_Operational_Process.md#work-packages)**
It is recommended that each Working Group creates a Work Package, which describes the scope of the work and expected deliverables.
The Work Package SHOULD be ratified by the [Steering Committee](./Organization_Operational_Process.md#steering-committee) and assigned to a Working Group.

* **[Technical Specifications Development](./Organization_Operational_Process.md#approval-process)**

This section suggest on how the Working Groups can approve Pull Requests; the final process is decided by each Working Group. The process is described in the **`CONTRIBUTING.md`** file available on each repository. In any case, this section recommends to follow the guidelines described in the **[Review & Approval Process](./Rules_of_Engagement.md#[Organization_Name]-approval-process)**

Once the **[Work Package](./Rules_of_Engagement.md#work-packages)** has been defined, the **[Development](./Rules_of_Engagement.md#work-flow-for-technical-specifications-development)** work starts. After the development work is completed, the group will initiate the **[Consistency Review](./Rules_of_Engagement.md#work-flow-for-technical-specifications-development)**, which is a process to formally evaluate the documentation prior final approval by the Working Group.
The **[Approval](./Rules_of_Engagement.md#omp-approval-process)** of the Specifications is performed by the Working Group after completing the **[Consistency Review](./Rules_of_Engagement.md#work-flow-for-technical-specifications-development)**.
Once the Group has formally approved the work under development, the deriverables need to be **[ratified](./Rules_of_Engagement.md#work-flow-for-technical-specifications-development)** by the **[Organization Team](./Rules_of_Engagement.md#organization-team)**. The **[ratification](./Rules_of_Engagement.md#work-flow-for-technical-specifications-development)** by the **[Technical Steering Committee](./Rules_of_Engagement.md#organization-team)** triggers the  **[Publication](./Rules_of_Engagement.md#work-flow-for-technical-specifications-development)** of the corresponding deliverables.

* **License on Technical Documents**
The section provides a **[License statement](./Rules_of_Engagement.md#technical-document-license)** that needs to be inserted in all documents published by the Working Groups.

* **[Documentation - Versioning](./Rules_of_Engagement.md#documentation)**
The organization publishes its deliverables: technical documents and, or software code, following **[Semantic Versioning](./Rules_of_Engagement.md#semantic-versioning)**, which provides a simple criteria to decide the version - Vx.y.z - of content to be released by the Working Groups.


* **[Copyright and Licensing Best Practise](./Rules_of_Engagement.md#copyright)**
These rules are guidelines on how to write simple and easy to maintain **[Copyright](./Rules_of_Engagement.md#copyright)** statements. As well as how handle **[Software Licenses](./Rules_of_Engagement.md#licenses)** in the repositories of the organization. 

* **[Software License Policy](./Rules_of_Engagement.md#software-license-policy)**
This policy provides a set of Software Licenses rules that must be followed up by the contributors to the organization repositories.

* **[Technical Decision Making](./Rules_of_Engagement.md#technical-decision-making)**

* **Using Supermajority vote to achieve agreement**

* **[[Organization_Name] Approval Process](./Rules_of_Engagement.md#omp-approval-process)** which is used to approve contributions presented to the Working Groups 
[[Organization_Name] Work Flow](./Rules_of_Engagement.md#github-flows)


In addition to the [Rules of Engagement]() there are two documents that provide further procedures:

**`CONTRIBUTING.md`** 
The `CONTRIBUTING.md` is a text file available in each `[Organization_Name]` repository. This file is created and approved by the corresponding `[Organization_Name]` Working Group. Its purpose is to describe how contribute to a particular repository. It can be adjusted as needed from one repository to another, even within the same Working Group. See an [example]() of a CONTRIBUTING.md file.

**`Release Planning`** 
It is a set of milestones that indicate what the group is planning to deliver and by when.
Each Working Group should create and maintain its own **Release Planning Document**. This document in its simplest form, is a table (a Release Roadmap), that contains version and release date. It can be extended with the list of features that will be released. See an [example]() of a **Release Planning table**.
