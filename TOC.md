The Cloud Foundry Technical Oversight Committee (TOC) is responsible for cross-cutting
product and design decisions.

- [Charter](#charter)
- [Composition](#composition)
- [Activities](#activities)
- [Decision-Making](#decision-making)
- [Meetings](#meetings)
- [Chair](#chair)
- [Members](#members)
- [Election Process](#election-process)

## Charter

The TOC shall be responsible for the oversight, direction, and delivery of technical aspects of the Cloud Foundry project, including:

- setting the overall technical direction and roadmap of the project;

- resolving technical issues, technical disagreements, and escalations
  within the project;

- setting the priorities of individual releases to ensure coherence and proper
  sequencing;

- approving the creation and dissolution of working groups and
  leadership changes within working groups;

- creating proposals based on TOC discussions and conveying them to the
  relevant working groups for discussion;

- approving the creation, archival, and deletion of GitHub repositories, along
  with conducting other high-level administration of GitHub and other tools for
  technical collaboration.

The TOC shall also be responsible for the health and well-being of the Cloud Foundry technical community, including:

- establishing and maintaining the overall technical governance guidelines for
  the project;

- ensuring the team adheres to the Cloud Foundry community [code of
  conduct](https://www.cloudfoundry.org/code-of-conduct/) and respects
  community [principles](./PRINCIPLES.md);

- fostering an environment for a healthy and happy community of developers and
  contributors.

## Composition

The TOC will have five seats, with a two-year term for each seat.

There will be an annual election to determine the composition of the TOC for the
following year. Three seats will be up for election in one year and two will be
up for election the following year.

### Employer diversity

Employees from the same organization or Related Organizations (as defined
below) should not hold more than two TOC seats.

- Related Organization means any entity which controls or is controlled by an entity or
  which, together with an entity, is under the common control of a third party, in each
  case where such control results from ownership, either directly or indirectly, of more
  than fifty percent of the voting securities or membership interests of the entity in
  question.

- Related Organizations are entities that are each a Related Organization of an entity.

During any TOC election, if the TOC membership would exceed this limit even
after the natural cycle of TOC seat term expirations, enough TOC members must
resign for it to be possible for the election to yield a diverse enough TOC.

If a TOC election cannot produce a diverse enough TOC, the limit will not
apply until the next election cycle. When a change in employment of a TOC
member causes the TOC membership to exceed this limit, that TOC member will
NOT be required to resign their TOC membership.

### TOC Member Resignations or Removal

In the case where a TOC member resigns or is removed from the TOC by the Governing
Board, the remaining members of the TOC will have the right to determine if the 
vacant seat will (1) remain vacant until the next annual election cycle, or (2) be 
filled by using the results of the last election.

When making this decision, the remaining members of the TOC should take under 
consideration the amount of time since the last election cycle.

## Activities

Activities of the TOC include:

- Defining, documenting, publishing, and maintaining the overall technical
  direction of the Cloud Foundry Foundation's open-source projects.

- Holding regular public meetings of the TOC to discuss topics currently under
  consideration in the community, with meeting notes to be recorded and
  published for community review and commentary. In order to prevent
  vandalism, the TOC may require that making comments on the notes requires
  authentication.

- Creating, reviewing, approving, and publishing technical project governance
  documents.

- Creating proposals to direct working groups towards project-wide objectives.

- Reviewing, addressing, and commenting on project issues.

- Providing advice on technical questions or designs arising in the working
  groups.

## Decision-Making

The TOC should strive to reach consensus on decisions when possible. Any
decision requires a quorum of the TOC, defined as the presence of a simple
majority (greater than 50%) of the current TOC members.

If a TOC member sustains an objection to a proposed decision, any member of
the TOC may call the decision to a vote. Each member of the TOC is entitled to
one vote in any voting matter. A simple majority (greater than 50%) of all
members of the TOC must vote to approve the decision for it to be accepted.

If a TOC vote is required to reach a decision, the TOC should ensure that
sufficient time has been allowed for TOC members to seek community input 
prior to the vote.

The TOC shall record calls to vote and decisions voted upon, including the
individual votes of the TOC members, in the regularly published TOC meeting
notes.

## Meetings

The TOC will determine a schedule for regular meetings. It may also hold ad-hoc
meetings at the request of two or more members of the TOC.

Community members are encouraged to suggest topics for discussion ahead of the
TOC meetings, and are invited to observe these meetings and engage with the TOC
during the community feedback period at the end of each meeting.

| Artifact                   | Link                                                                                                                                                     |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Google Group               | [cf-toc@lists.cloudfoundry.org](https://lists.cloudfoundry.org//g/cf-toc)                                                                                |
| Community Meeting VC       | See the top of the [Meeting notes]()                                                                                                                     |
| Community Meeting Calendar | Xdays at XX:XXa-XXp <br>[Calendar]()                                                                                                                     |
| Meeting Notes              | [Notes]()                                                                                                                                                |
| Document Folder            | [Folder]()                                                                                                                                               |

## Chair

The TOC will select a chair from amongst the TOC members.

The TOC Chair is responsible for:
* Chairing meetings of the TOC
* Coordinating meeting agendas, based on feedback from the community and other TOC members
* Representing the technical community on the CFF board

## Members

The members of the TOC are shown below. Membership in the TOC is determined by
the Cloud Foundry community via an election.

| &nbsp;                                                         | Member         | Company | Profile                                              |
| -------------------------------------------------------------- | -------------- | ------- | ---------------------------------------------------- |
| GH picture        | name     | employer  | profile               |

## Election Process

### Candidate Eligibility

Current TOC members, [WG Leads](https://github.com/cloudfoundry/community/blob/master/ROLES.md#working-group-technical-lead), 
and [Approvers](https://github.com/cloudfoundry/community/blob/master/ROLES.md#approver)
with at least 3 months tenure are eligible to stand for election. Candidates may
self-nominate or be nominated by another eligible member.

### Voter Eligibility

Contributions include, but are not limited to, opening PRs, reviewing
and commenting on PRs, opening and commenting on issues, writing design docs,
commenting on design docs, helping people (e.g.: on slack), and participating in 
working groups. Anyone who has at least 50 contributions in the last 12 months is 
eligible to vote in the TOC election. 

[This dashboard][1]
shows only GitHub based contributions and does not capture all the contributions
we value. **We expect this metric not to capture everyone who should be eligible
to vote.** If a community member has had significant contributions over the past
year but is not captured in the lfanalytics.io dashboard, they will be able
to submit an exception form to the current TOC who will then review and
determine whether this member should be marked as an exception. In a case where the 
TOC declines an exception request, the requestor may appeal that decision
to the Governing Board.

All eligible voters will be captured at
`cloudfoundry/community/elections/$YEAR/voters.md` and the voters’ guide
will be captured at `cloudfoundry/community/elections/$YEAR/README.md`
similar to the kubernetes election process.

We are committed to an inclusive process and the TOC will have the right to
adjust future eligibility requirements based on community feedback.

### Election Method and Tools

Elections will be held using a time-limited
[Condorcet](https://civs.cs.cornell.edu/rp.html) ranking on
[CIVS](http://civs.cs.cornell.edu/) using the
Schulze method. The top vote-getters will be elected to the open 
seats. This is the same process used by the Kubernetes project.

### Election Administration

On behalf of the Cloud Foundry Foundation's Board of Directors, foundation staff will 
administer the election based on the process outlined above.

---

The initial content of this page is from the work of the [Knative community](https://github.com/knative/community)
under the terms of the [Creative Commons Attribution 4.0 License](https://creativecommons.org/licenses/by/4.0/).

[1]: https://lfanalytics.io/projects/cloud-foundry%2Fcloud-foundry/active-contributor?time=%7B%22from%22:%22now-1y%22,%22type%22:%22datemath%22,%22to%22:%22now%22%7D