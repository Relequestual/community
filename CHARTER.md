# JSON Schema Org Charter
<!-- This document is managed in the json-schema-org/.github GitHub repository. Please do NOT modify this file in another repository as changes may be overridden. -->

<!-- While this document is being written, you can find the discussion to help determine what should be found here at https://github.com/json-schema-org/community/discussions/286 - This comment should be removed before merging -->

## Section 0: Guiding Principles
<!-- https://github.com/json-schema-org/community/discussions/286#discussioncomment-4391241 -->

The JSON Schema project is part of the OpenJS Foundation which operates transparently, openly, collaboratively, and ethically. We strive to be open and transparent as much as is possible, and wish to enable anyone to interact and engage with any area of our work.

Having no structure in place usually leads to one that is informal and undocumented, making it difficult to meet our own expectations of how we wish to operate. As such, we define the following charter which includes aspects of the governance model to which we subscribe and by which we operate.

## Section 1: Scope
<!-- https://github.com/json-schema-org/community/discussions/286#discussioncomment-4391250 -->

JSON Schema aims to enable the confident and reliable use of the JSON data format. It does this primarily by providing specification documents which define a declarative language that allows annotation and validation of JSON documents.
While JSON Schema's primary target is constraint-based data validation, it continues to be used across the whole stack, in different stages of a given project, and for purposes beyond its original design. We aim to enable these additional and emergent use cases.

### 1.1: In-scope (optional)

https://github.com/json-schema-org/community/discussions/286#discussioncomment-4391253

_directions: list or bullet out problem spaces, use cases, repositories_
_or other projects which are included with the work but may not be readily_
_apparent. This may help differentiate the project from other solutions in the_
_space. If you are not using this section, please indicate your intent with the_
_phrase, 'Section Intentionally Left Blank'._

ex. [K8s SIG Architecture Charter](https://github.com/kubernetes/community/blob/HEAD/sig-architecture/charter.md#in-scope)

### 1.2: Out-of-Scope (optional)
<!-- https://github.com/json-schema-org/community/discussions/286#discussioncomment-4391262 -->

Section Intentionally Left Blank

## Section 2: Relationship with OpenJS Foundation CPC.
<!-- https://github.com/json-schema-org/community/discussions/286#discussioncomment-4391266 -->

Most large, complex open source communities have both a business and a technical governance model. Technical leadership for the projects within the OpenJS Foundation is delegated to the projects through their project charters by the OpenJS Cross Project Council (CPC). In the case of the JSON Schema project, it is delegated to the JSON Schema Technical Steering Committee ("TSC").

### 2.1 Other Formal Project Relationships (optional)
<!-- https://github.com/json-schema-org/community/discussions/286#discussioncomment-4391271 -->

Section Intentionally Left Blank

## Section 3: JSON Schema Org Governing Body (TSC)
<!-- https://github.com/json-schema-org/community/discussions/286#discussioncomment-4391284 -->

The TSC is initially established from the observed major contributors who are currently active and in good standing.

There is no maximum TSC membership size. The TSC must have a minimum of four members.

Changes to TSC membership should be posted in the agenda, and may be suggested as any other agenda item.

TSC memberships are not time-limited.

While the project is not looking to obtain "Impact" project status within the OpenJS Foundation, there is no requirement set out to limit the number of TSC members by employer. It is in some cases considered difficult or even unhelpful for the project to limit the number or percentage of TSC members by employer (Especially when an employer has employed individuals already active in the community to work exclusively on the open source project). While at this time there is no limits on TSC membership by employer, the TSC will strive to keep to at least less than 50%, ideally 33% (One third, one in three). The TSC will re-evaluate this specific clause at least every six months, and aim to revise it within one year to meet the "no more than 1/3 employer member affiliation" mandate.

TSC members are expected to regularly participate in TSC activities.

The TSC will meet regularly using virtual conferencing tools. The meeting will be directed by the TSC Chairperson(s). Responsibility for directing individual meetings may be delegated by a TSC Chairperson to any other TSC member. Minutes or an appropriate recording will be taken and made available to the community through accessible public postings.

The TSC may, at its discretion, invite any number of non-voting observers to participate in the public portion of TSC discussions and meetings.

A TSC member may be removed by vote from the TSC if, during a 3-month period, all of the following are true:

- They attend fewer than 25% of the regularly scheduled meetings
- They do not participate in any TSC votes
- They do not provide any form of excuse or no excuse is known for their absence

## Section 4: Roles & Responsibilities
<!-- https://github.com/json-schema-org/community/discussions/286#discussioncomment-4391286 -->

The JSON Schema project is jointly governed by a Technical Steering Committee (TSC) which is responsible for high-level guidance of the project.

The TSC has final authority over this project including:

- Technical direction
- Project governance and process (including this policy)
- Contribution policy
- GitHub repository hosting and administration
- Establishment of and delegation to working groups or teams
- Mediating technical conflicts

### Section 4.1 Project Operations & Management (optional)
<!-- https://github.com/json-schema-org/community/discussions/286#discussioncomment-4391290 -->

The TSC and entire technical community will follow any processes as may be specified by the OpenJS Foundation Board relating to the intake and license compliance review of contributions, including the OpenJS Foundation IP Policy.

### Section 4.2: Decision-making and Voting
<!-- https://github.com/json-schema-org/community/discussions/286#discussioncomment-4391296 -->
Note: See comments found in raw view...

The TSC follows a formal consensus seeking decision making model.
In some situations, a vote may be preferable, however a vote will not be used to make the vast majority of decisions.
In the unlikely case where it seems that consensus cannot be reached after multiple attempts, the decision process may be moved to resolve via a vote. This is not expected to happen, but defined as a backup.

#### Decision-making via consensus

When a TSC member looks for an issue to be discussed and a decision to be made, they must start by assessing if they feel it warrants potentially being a non-public discussion and decision. The TSC member must reach out to the TSC chairs to request a non-public discussion and decision. A discussion and decision will be non-public at the discretion of the TSC chairs. It is expected that decision discussions and voting will only be non-public in rare circumstances.

Both the Quick and Standard consensus process require the creation of an Issue in the TSC GitHub repository.
The Issue must:
- Include brief introductory information about the decision that needs to be made
- Be labelled with 'tsc-decision'
- Use the provided template, unless there is a good reason not to do so

##### Quick consensus process

In the event a TSC member feels the need for a decision to be expedited, they may create the decision discussion, indicating that they wish to use the quick process rather than the standard consensus process. This should be done by creating a new Issue in the TSC repository.
In addition to the requirements above, the Issue must be labelled 'expedited'.

While an associated Discussion is not required, if one is used, it must be clearly linked in both directions, and be labelled with 'tsc-decision'.

A vote is called to see if other members agree. The vote takes place on the opening comment. This vote is different from the decision-making voting process, and only requires 3 (additional) votes in favour and none against to carry. If the vote carries, the quick process is started, otherwise the standard consensus process is started.

The quick process is designed for small trivial issues where the resolution feels likely obvious, and the member who proposes the decision discussion has at least one clear resolution to present. The decision discussion owner should present the possible solution they are advocating for (in a follow up comment on the Issue. Not in the opening comment.), and ask to test for agreement. If consensus is not clearly reached, the quick process is ended and the standard consensus process is started. (Label 'expedited' should be removed and 'stage-1' added.)

##### Standard consensus process

The standard consensus process is designed for all non-trivial decisions.

A decision discussion may be started by creating an Issue and Discussion in the TSC repository.

In addition to the requirements above, the Issue must:
- Be labelled with 'stage-1'
- Link to the associated initial Discussion

The Discussion must:
- Link to the associated Issue
- Include detailed introductory information about the decision that needs to be made
- Be labelled with 'tsc-decision'

The standard consensus process should progress through the following seven stages.

1. Introduction and clarify the issue
2. Open the discussion - Share needs and perspectives on the issue
3. Explore ideas in a broad discussion
4. Form a proposal
5. Amend the proposal
6. Test for agreement
7. Determine resolution

(These stages are those defined by the [Seeds For Change's Consensus Decision Making document](https://seedsforchange.org.uk/consensus). Please use that document as a rough guide for specific steps while we test and firm up our specific requirements, and document them in our [Governance document](./GOVERNANCE.md))
<!-- GOVERNANCE.md is not yet created. I would suggest that creating one which helps us through the seven stages of the consensus process be the first order of business. -->

All decisions that go through the standard consensus process must have an associated GitHub Issue, which allows those unable to attend meetings to participate.
The opening comment of the Issue should be kept up to date as to the status of the decision.

Transition between stages may be requested by anyone, but must be called by the facilitator (either a TSC chair or TSC member delegated the facilitator role for a given decision discussion). The stage will be indicated in the opening comment of the Issue and using the appropriate label.

Most of the discussion should happen within the associated Discussion. The Issue should mostly be used to updated and report progress the consensus process. Groups looking to form a proposal or amend a proposal (stages 4 and 5) may make use of other additional Discussions or Issues, but these must be clearly linked. The opening comment should be updated to include links to relevant specific threads and comments in associated Discussion, and any other relevant locations.

Moving to the 'Form a Proposal" stage should be approached when the group might feel able to combine ideas to form a single proposal. Multiple possible solutions should be discussed in the previous stage.

The "Test for Agreement" step is not voting, and is in stead asking for "signals", which enable the consensus process to continue.
Voting should be considered a last resort if the consensus process has failed for a particular issue, to enable the project to move forward.

If someone calls for a Test for Agreement, the facilitator for the decision discussion will review current proposal and may call to Test for Agreement. The facilitator will post a comment on the Issue (using the provided template), linking to the current version of the proposal, and update the opening comment with a link to the new comment. TSC members will then be asked to signal their agreement using GitHub Reactions on the comment.

The signals include "Block". Any use of the "Block" signal will require a new or amended proposal to be worked on. A "Block" should be used to indicate a strong objection, such as something against the projects core principals or something that would harm the project.

The blocker/s should be prepared to commit to trying to find a solution, but not necessarily form and present a solution by themselves. The TSC will look to facilitate a number of workshops to help understand the blocking objections, and form a new or amended proposal as a result.

If someone feels a "Block" is being used for unfair reasons, such as targeting individuals or to gain some personal advantage, or any such reason that might be in breach of our Code of Conduct, they should immediately report it to the Code of Conduct committee. The Code of Conduct committee should report this to the TSC Chairs as soon as possible, and the decision is halted while the committee investigates the report.

The Code of Conduct committee will report their findings and any remediation action to the TSC Chairs.
Reports must remain anonymous, as per the Code of Conduct.

The other signals that may be made when a Test For Agreement is called include "Reservations" and "Stand Aside". Both are signals which convey consent to let the proposal pass, however they may be conditional.

Signalling "Reservations" means an agreement on the overall direction, however there is some desire to revise or amend the proposal somewhat. It is expected that the individuals signalling "Reservations" want to engage in reworking the proposal. The facilitator will check with each individual regarding the strength of the reservation, and later facilitate or direct discussion as required to amend and represent the proposal. If the individual/s do not wish to participate in reworking the proposal, their reservations should be logged as part of the decision record as unresolved.

If "Reservations" is signalled three consecutive times by the same individual/s, anyone may call for no further attempts to remediate the reservations, and the proposal will pass.

Signalling "Stand Aside" convey consent, but an unwillingness for whatever reason to be further involved. It could be for example that the individual does not have time to participate, or that they have limited opinions on the specific decision. The individual may provide a reason for standing aside. If the individual believes the reason can be remedied by the group, the group should seek to remedy the reason where possible, with help from the facilitator.

The TSC will make every reasonable effort to reach unanimity based consensus. If unanimity seems unlikely after several failed attempts to revise the proposal and Test for Agreement, if the proposal is clear, the decision may be moved to a vote, at the discretion of the TSC Chairs. This is a last resort.

The "Determine resolution" step should result in the creation of an [Any Decision Record](./docs/adr/README.md). More details in following sections.

#### Decision-making via vote

Any call for public TSC votes will be made by creating an Issue in the TSC repository with the `tsc-vote` label assigned. The Issue should use the provided template.

Once an Issue gains the label `tsc-vote`, all members of the TSC will be notified via a specific Slack channel (and by any additional method the TSC deems helpful). The votes will be collected by way of using GitHub Reactions on a specific comment, which must not be the first comment. The first comment must link to the voting comment in the same Issue.
Voting will by default close after 7 days. Any member of the TSC may request a 7 day extension for any reason, moving the closing date back by 7 days. Any member of the TSC may request additional extensions, approved at the discretion of any TSC chair.

For a vote to carry, a quorum of 75% is required by default.

If a TSC member wants to call for a vote that they wish to be non-public, they must do so by contacting the TSC Chairs directly.
At the discretion of the TSC Chairs, a vote may be made non-public, and will then be handled by creating an Issue in the 'TSC-private' repository.

The topic and nature of non-public votes may remain non-public, including the results.(It is expected that vast majority of votes will be public. Non-public voting should only be used in exceptional circumstances.)

#### Documenting decisions

Either initially, or at any point during the process, any TSC member may suggest the issue being discussed is "significant or noteworthy." If there are no objections, the resolution actions for the issue must include the creation of an Any Decision Record (Previously named Architectural Decision Record). The Any Decision Record (ADR) should include as much information as is thought to be useful, following the provided template. The Pull Request for the ADR must be approved by all those who were involved in the decision making process, which must also be documented in the ADR as the "deciders."

(The quick consensus process does not require a Decision Record, but the decision should be minuted.)

Non-public decisions should be documented (as an ADR or otherwise) in the private `private-tsc` repo.

### Section 4.3: Other Project Roles (optional)

The JSON Schema project recognises the need for both technical and non-technical roles. While the OpenJS Foundation takes on business responsibilities as the legal entity hosting the project, there are other non-technical responsibilities.

The TSC will look to create other roles as appropriate, and may update this document in accordance with the requirements for doing so, to formally recognise the additional roles.

The following responsibilities are recognised as those requiring roles to be defined by the TSC:
- Community and Industry connections
- Brand awareness, recognition, and health
- Strategic allocation of funds and budgeting for investment in JSON Schema and its ecosystem
- Education and training
- Financial allocation approval, tracking, and auditing

## Section 5: Definitions (optional)
<!-- https://github.com/json-schema-org/community/discussions/286#discussioncomment-4391301 -->

The JSON Schema project: The project which is housed by the OpenJS Foundation which operates as The JSON Schema Org.

The JSON Schema Org: The people, policies, processes, activities, and artifacts, found within the GitHub json-schema-org.

TSC: The Technical Steering Committee, delegated technical leadership for the JSON Schema project by the OpenJS Foundation.

---

This work is a derivative of the [WebdriverIO Project Governance Model](https://github.com/webdriverio/webdriverio/blob/main/GOVERNANCE.md).

Inspired by https://seedsforchange.org.uk/consensus, https://seedsforchange.org.uk/quickconsensus
Informed by https://www.ic.org/busting-the-myth-that-consensus-with-unanimity-is-good-for-communities/

This work is licensed under a [Creative Commons Attribution-ShareAlike 2.0 UK: England & Wales License](https://creativecommons.org/licenses/by-sa/2.0/uk/).