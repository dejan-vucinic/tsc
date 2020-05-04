# Project Lifecycle Process

## Introduction

This governance policy sets forth the proposal process for projects to be accepted into CHIPS Alliance. The process is the same for existing projects which seek to move into CHIPS Alliance and new projects being formed within CHIPS Alliance.

There are four project categories:

* [Sandbox](#sandbox): Optional pre-membership stage to help a project prepare for the TSC's consideration.
* [Incubating](#incubating): A project which has been accepted by the TSC and assigned to a workgroup.
* [Graduated](#graduated): A project which has met the graduation requirements and demonstrated sustainable momentum.
* [Archived](#archived): When an Archival proposal is accepted, the PR may be landed and closed.): A former Incubating or Graduated project which has been archived for strategic or practical reasons.


## Sandbox

*Sandbox projects* are projects which plan to join the CHIPS Alliance, but have not yet met the prerequisites to formally join. Projects may optionally make use of the Sandbox stage in order to request TSC time and attention in preparing for their application to become a part of CHIPS Alliance.

The Sandbox stage is optional, and Sandbox projects are not yet considered part of CHIPS Alliance.

### Benefits of becoming a Sandbox project:

* The TSC will prioritize requests for help meeting the requirements of Incubating or Graduated projects.
* The TSC will monitor the project to ensure progress is being made.

### Expectations of Sandbox projects:

* Because Sandbox projects are not yet a part of CHIPS Alliance, it is their responsibility to manage the Incubating or Graduated application process.
* Projects may remain in the Sandbox stage so long as they are making reasonable progress toward applying for Incubating or Graduated status.
* Projects which cease to make progress or are on a trajectory which would lead to rejection may be removed by majority vote of the TSC.
* Projects may reapply for Sandbox status if previously removed for any reason.

### Requirements to become a Sandbox project:

1. The project must complete an application based upon the [project application template](./PROJECT_APPLICATION_TEMPLATE.md), copy it to the [sandbox](sandbox) directory, and open a PR against the TSC repo with the `tsc-meeting` and `sandbox-application` labels.
1. The project must join a TSC meeting to present its proposal.
1. TSC must approve the application as a Sandbox project by majority vote.

When a Sandbox proposal is accepted, the PR may be landed.

## Incubating

*Incubating projects* are projects which have applied and been formally accepted into CHIPS Alliance by the TSC.  These projects are early stage but have not yet achieved the maturity or broad adoption of Graduated projects.  Incubating projects are assigned to a Workgroup, and are officially a part of CHIPS Alliance.

All projects must complete the Indubating application. Some projects (particularly large, mature, pre-existing projects) may progress through this stage quickly. Others may require some time or work to meet the maturity and adoption requirements of the Graduated stage. Finally, some projects may never reach the Graduated stage, and instead remain productive Incubating projects.

### Benefits of becoming an Incubating project

* Project may claim a formal association with CHIPS Alliance
* Project is placed within a workgroup, and project members can be considered for workgroup leadership and TSC voting member status.
* Project gains access to CHIPS Alliance resources, including events, the ability to request financial resources, and mentorship.

### Expectations of Incubating projects

* Projects must adhere to open source best practices.
* Project must proactively and positively promote CHIPS Alliance.
* Project must participate actively in its workgroup meetings and governance, and any other positions held within CHIPS Alliance. At least one member from the Project should join TSC meetings, whether a voting member or non-voting attendee.
* Project must actively work to ensure a healthy number of committers.
* Project must demonstrate ongoing and sustained involvement from contributors.
* Project will participate in reviews by the TSC to ensure it remains a fit for CHIPS Alliance

### Requirements to become an Incubating project

1. The project must actively work with the TSC as it does due diligence to determine fit.
1. The project must have a substantial ongoing flow of commits and merged contributions.
1. The project must use a clear versioning scheme.
1. The project must have a [draft mission statement](./MISSION_STATEMENT_TEMPLATE.md) prepared for TSC approval.
1. The project must internally pre-approve the Code of Conduct, IP Policy, and header/footer for websites so that they are in effect upon project acceptance by the TSC.
1. The project must be prepared to transfer any registered trademarks and domain names to the Linux Foundation upon acceptance.
1. The project must complete an application based upon the [project application template](./PROJECT_APPLICATION_TEMPLATE.md) (or modify its existing Sandbox application), copy it to the [incubating](incubating) directory, and open a PR against the TSC repo with the `tsc-meeting` and `incubating-application` labels.
1. The project must join a TSC meeting to present its proposal.
1. The TSC must approve the Incubating application and the project's mission statement by majority vote.

When an Incubating proposal is accepted, the PR may be landed.

## Graduated

*Graduated projects* are projects which have applied and been formally accepted as Graduated projects by the TSC. These projects are mature in their development and deployment cycles, and broadly adopted by end-users. 

However, achieving Graduated status requires more than maturity and adoption. The TSC is run by and for the technical community, and it can only function with involvement from project leaders. Representatives from Graduated projects are expected to take an active role in TSC and CHIPS Alliance processes. For example, participating in TSC meetings, volunteering as a program committee member for events, participating in mentoring initiatives, and helping Sandbox projects prepare for their Incubating status application.

### Benefits of becoming a Graduated project

* Project gets the highest level of support from CHIPS Alliance.

### Expectations of Graduated projects

* The project must exemplify the values of CHIPS Alliance and be committed to diversity and inclusion.
* The project is expected to take an active role in TSC operations and initiatives.
* The project must lead by example on adherence to core project policies, such as the Code of Conduct.
* The project must ensure that committers are diversified across organizations.
* The project must avoid actions that will lead to an unsustainable development community.

### Requirements to become a Graduated project

1. The project must have committers from at least two independent organizations.
1. The project must have a public list of project adopters.
1. The project must have achieved and maintained a Core Infrastructure Initiative [Best Practices Badge](https://bestpractices.coreinfrastructure.org/).
1. All registered trademarks and domain names must be fully transferred to the Linux Foundation.
1. The project must have a documented process for reporting security vulnerabilities.
1. The project must complete an application based upon the [project application template](./PROJECT_APPLICATION_TEMPLATE.md) (or modify its existing Sandbox/Indcubating application), copy it to the [graduated](graduated) directory, and open a PR against the TSC repo with the `tsc-meeting` and `graduation-application` labels.
1. The project must join a TSC meeting to present its proposal.
1. The project must receive a supermajority vote from TSC voting members.

When a Graduated proposal is accepted, the PR may be landed.

## Archived

*Archived projects* are projects which no longer have sufficient momentum to justify an active state in CHIPS Alliance. By archiving a project, CHIPS Alliance is indicating that downstream users should not expect any updates, including security fixes or backports.

The decision to move a project to Archived is not taken lightly by the TSC, and each situation will be unique.  However, reasons which could lead to an Archived state may include:

* The project has requested the TSC move it to Archived state.
* There are no more active committers.
* There are no more active contributors.
* Another project has encompassed its functionality.

### Expectations of Archived projects

* If possible, the project should add a Linux Foundation member as organization owner.
* The project should remove all references to its former CHIPS Alliance lifecycle stage, the standard footer, and any logos.
* The project should move its repos to `Archived` state in GitHub.
* The project should add a prominant notice on its `README.md` and `CONTRIBUTING.md` that the project has been archived, and that downstream users should not expect any further development, updates, or fixes.

### Requirements to become an Archived project

1. A representative from the project or a TSC voting member should complete the [project archival template](./PROJECT_ARCHIVAL_TEMPLATE.md), copy it to the [archived](archived) directory, and open a PR against the TSC repo with the `tsc-meeting` and `archival-application` labels.
1. A representative from the project or a TSC voting member must join a TSC meeting to present the proposal.
1. The archival proposal must receive a supermajority vote from TSC voting members.

When an Archival proposal is accepted, the PR may be landed.

## FAQs

#### Is the Sandbox a required stage?

No, but it can help a project get organized and make the Incubation proposal more straightforward.

#### Can a project skip Incubation?

Some mature projects may seek to enter CHIPS Alliance and already meet all of the criteria for a Graduated project.  Because the Graduated application is a superset of the Incubating application, a project which applies for Graduated status is effectively applying for both. If for any reason the TSC does not confirm Graduated status, it can vote on Incubating status with the same application.  Likewise, should the TSC not confirm Incubating status, it can vote on Sandbox status with the same application.

#### Does the TSC have final discretion over a project's status?

Yes, the TSC always makes the final decision whether a project's application is accepted, deferred, or rejected.

#### Can a project be removed from any stage?

Yes, any project may be converted to Archived state or removed from CHIPS Alliance through a supermajority vote by disinterested voting members.

#### Can a project move from Archived to an active state?

Yes, an Archived project can be reactivated if a contributors and maintainers are willing to commit to ongoing development. In this case, the project may reapply for consideration as a Sandbox or Incubating project.