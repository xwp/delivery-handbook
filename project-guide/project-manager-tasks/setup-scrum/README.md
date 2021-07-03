# Agile Scrum at XWP

Scrum at XWP has a two week time-box with an adjustable scope known as Sprints to address rapidly changing development needs. A typical Scrum process is distinguished from other agile processes by specific concepts and practices, divided into the three categories of **Roles**, **Artifacts**, and **Ceremonies.**

## **Roles**

* Project Manager \(aka Scrum Master\)
* Product Owner
* Scrum Team

## Artifacts

Scrum’s artifacts represent work or value to provide transparency and opportunities for inspection and adaptation. Artifacts defined by Scrum are specifically designed to maximize transparency of key information so that everybody has the same understanding of the artifact. Here are a couple typical artifacts.

* Product Backlog
* Sprint Backlog
* Burn-Down Chart
* etc...

## Ceremonies

Prescribed ceremonies are used in Scrum to create regularity and to minimize the need for meetings not defined in Scrum. All ceremonies are time-boxed, such that every ceremony has a maximum duration. Once a Sprint begins, its duration is fixed and cannot be shortened or lengthened. The remaining ceremonies may end whenever the purpose of the ceremony is achieved, ensuring an appropriate amount of time is spent without allowing waste in the process.

Other than the Sprint itself, which is a container for all other ceremonies, each ceremony in Scrum is a formal opportunity to inspect and adapt something. These events are specifically designed to enable critical transparency and inspection. Failure to include any of these events results in reduced transparency and is a lost opportunity to inspect and adapt.

### Sprints

The heart of Scrum is a Sprint, a time-box of two weeks during which a "Done", useable, and potentially releasable product increment is created. Sprints have consistent durations throughout a development effort. A new Sprint starts immediately after the conclusion of the previous Sprint.

### Meetings

It's important to set up consistent meetings with agendas for each of the typical Scrum Ceremonies, in an effort to support the success of each project, and bring consistency across the organization.

{% tabs %}
{% tab title="Daily Standup" %}
**Meeting Goal:** Ensure everyone is up to speed on the project

**Meeting Cadence:** Occurs daily, async

**Agenda**

1. What did I work on yesterday?
2. What am I working on today?
3. What issues are blocking me?

At XWP we typically don't have a meeting set up for this ceremony, instead we post a Daily Standup via Slack to the shared client channel. This is done using a Slack Workflow that should always be setup in the shared channel. Once setup the Scrum Team can select the bolt icon in the top right menu, next to the phone icon.

**For Stand-up Workflow Setup and How-to see** [**Stand-up Workflows in Slack**](setting-up-a-stand-up-workflow-in-slack.md)**.**

{% hint style="warning" %}
This ceremony should include all team members from XWP and the client team
{% endhint %}
{% endtab %}

{% tab title="Backlog Grooming" %}
**Meeting Goal:** Review the backlog for upcoming sprint\(s\) and flesh out any needs ahead of the sprint starting, so items have all the details necessary to be executed.

**Meeting Cadence:** bi-weekly, ideally 2 weeks ****prior to the Sprint start \(occurs in the off week of Sprint Planning\)

**Meeting Agenda:**

1. Review a set of the product backlog stories for the upcoming Sprint.
2. Forecast by the Scrum Team about what functionality will be in the next Sprint and the work required to deliver that functionality into Done.
3. Q&A to flesh out the Acceptance Criteria
4. Next Steps &gt; Sprint Planning to start the upcoming Sprint \[Link Notes\]

{% hint style="warning" %}
This meeting should include all team members on the XWP and client team.
{% endhint %}
{% endtab %}

{% tab title="Sprint Planning" %}
**Meeting Goal:** As a team align on what the goal of the upcoming sprint is, estimate/point items and get the upcoming sprint planned/signed off on collectively. 

**Meeting Cadence:** bi-weekly, ****the week prior to the Sprint start \(occurs in the off week of Backlog Grooming\)

**Meeting Agenda**

At XWP we recommend having an **Internal** and **Client** meeting for **Sprint Planning**, if the budget can support that cadence, else combine the meetings. If you combine the meetings be sure you go in prepared and extend the time-box accordingly.

**Internal** - the week prior to the Sprint start,  typically on Monday or Tuesday

1. A collaboration with the internal XWP team on this project, to determine what will be delivered in the upcoming Sprint.
2. Review Acceptance Criteria \(AC\) in preparation for the Client Sprint Planning session and gather questions and feedback to discuss with the client.
3. Q & A
4. Next Steps &gt; Client/XWP Sprint Planning \[Link Notes\]

{% hint style="warning" %}
This meeting should include all team members on the XWP and any devs on the client team.
{% endhint %}

**Client** - the week prior to the Sprint start, typically on Wednesday or Thursday

1. A collaboration with the client and XWP teams to determine what will be delivered and in the upcoming Sprint.
2. Review Acceptance Criteria \(AC\) for client Approvals.
3. Any Stories not approved in this call, should be followed up on via the Jira Story and be approved by the client by EOB Friday to ensure all Stories selected, are Sprint ready.
4. Q & A
5. Next Steps &gt; Final Sprint Story Approvals/Sprint Start \[Link Notes\]

{% hint style="warning" %}
This meeting usually only includes the XWP PM, PO and Architect, as well as the client contact approving tickets for the upcoming Sprint.
{% endhint %}
{% endtab %}

{% tab title="Demo" %}
**Meeting Goal:** Review the work completed in the previously closed sprint

**Meeting Cadence:** bi-weekly, the week following the Sprint completion

**Meeting Agenda:**

1. Post Sprint completion to review and inspect the previous Sprint’s deliverables and adapt/adjust the product backlog, if needed.
2. Recorded Demo to be shared with the client in an effort to showcase the work completed by XWP in the previous Sprint.
3. Collaborate on any next steps on how to optimize value and provide feedback.
4. Q & A
5. Next Steps &gt; Adapt/adjust the product backlog based on any feedback provided. \[Link Notes\]

Note: This meeting should include all team members on the the client team, as well as the PM, PO and Architect/Lead Engineer presenting the video/demo of our work in the previous Sprint.
{% endtab %}

{% tab title="Retrospective" %}
**Meeting Goal:** Review what want well, and what can be done better, to constantly be improving as a team

**Meeting Cadence**: bi-weekly, the week following the Sprint completion

**Meeting Agenda:**

1. Scrum team inspects itself and discusses improvements to be implemented during the next Sprint.
2. Ahead of this call, submit your feedback entries into the sheet linked below
3. Q & A
4. Next Steps &gt; Formulate a plan to implement feedback into the next Sprint \[Link Retro Sheet - include a tab for each Sprint\]

{% hint style="warning" %}
This meeting should include all team members on the XWP and client team.
{% endhint %}
{% endtab %}

{% tab title="Example Calendar" %}
This calendar illustrates one possible example for setting the Scrum meetings. Your team and time zones will decide on the appropriate days for the meetings.

1. All PMs should be setting these up, in an effort to standardize the experience for XWP internally and for our clients. 
2. The cadences are usually a Monday/Wednesday or Tuesday/Thursday split. Wednesday/Friday is possible, but not usually ideal for people in time zones that are spread far apart. 
3. **Each day there should be either, a Standup Meeting with the client, or a post to the client's Slack channel.**

| Sprint | Monday | Tuesday | Wednesday | Thursday | Friday |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 0 | _Backlog created/prepped ahead of call_ | \_\_ |  | **Product Backlog - Sprint 1**  |  |
| 0 | \*\*\*\* | **Internal Sprint 1 Planning** |  | **Client** **Sprint 1 Planning** | _Deliver Discovery/Project Docs - Delivery Ends_ |
| 1 | _Sprint Start_ |  |  | **Product Backlog - Sprint 2** |  |
| 1 |  | **Internal Sprint 2 Planning** |  | **Client** **Sprint 2 Planning** | _Sprint Ends_ |
| 2 | _Sprint Start_ | **Demo - Sprint 1 Review & Sprint 1 Retrospective** |  | **Product Backlog - Sprint 3** |  |
| 2 |  | **Internal Sprint 3 Planning** |  | **Client** **Sprint 3 Planning** | _Sprint Ends_ |
| 3 |  | **Demo - Sprint 2 Review & Sprint 2 Retrospective** |  | **Product Backlog - Sprint 4** |  |
{% endtab %}
{% endtabs %}

## 

## 

