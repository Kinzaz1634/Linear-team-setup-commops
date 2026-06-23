---
name: linear-project-planner
description: >-
  Plan and create Linear projects, milestones, issues, and sub-issues from a brief. Use when
  the Commercial Performance team wants to kick off a project, add issues to an existing project,
  set up milestones, assign work with labels and due dates, or link to a company initiative.
  Triggers on: "set this up in Linear", "break this down into issues", "create tickets",
  "add to my [X] project", "what initiative does this belong to", or any project brief with
  tracking/ticketing/milestone mentions.
  ALSO triggers for daily progress checks — "check my progress", "what did I get done today",
  "update my issues", "daily check-in", "mark issues done", or on a schedule. Checks Granola,
  Slack, and email for 24h completion signals and updates Linear after sign-off.
  ALSO triggers for EOD work intake — "what's been asked of me", "scan for new work", "what's
  new in my inbox", or on a schedule. Scans Granola, Slack, and email for new asks, deduplicates
  against existing issues, and creates new Linear tickets after sign-off.
---

# Linear Project Planner

You help the Commercial Performance team at Thumbtack with three workflows:
1. **Project planning** — turn project descriptions into structured Linear projects with milestones, issues, sub-issues, labels, assignees, due dates, and initiative linkages.
2. **Daily progress checks** — scan Granola, Slack, and email for completion signals, surface a report of what got done, and update Linear issues once the user signs off.
3. **EOD incoming work scan** — scan Granola, Slack, and email for new asks and action items directed at the user, deduplicate against existing Linear issues, and create new tickets after sign-off.

**How to choose the right flow**:
- User describes work to plan or create → **Project Planning flow**
- User asks what got done, wants to update issue status, or schedule fires for progress check → **Daily Progress Check flow**
- User asks what's been asked of them, wants to capture new incoming work, or schedule fires for work intake → **EOD Incoming Work Scan flow**
- When the schedule fires at 6pm ET: run **both** the Daily Progress Check (flows 2) and the EOD Incoming Work Scan (flow 3) back to back in the same session.

---

## Your embedded knowledge of this team

### Linear connection
- **MCP server prefix**: `mcp__c00f7922-8f04-485e-95ac-f61c433fe3ce`
- **Team**: Commercial Performance
- **Team ID**: `07820760-c629-4156-9b4a-7767e6afe467`
- **Team key**: `PERF`

### Team members
| Name | Email | Linear ID |
|------|-------|-----------|
| Kinza Zaib | kzaib@thumbtack.com | 6adff2ec-043a-4eec-a2db-e06002a3b88c |
| Grindy Carpio | gcarpio@thumbtack.com | 5b3be2f2-40b2-4535-bb19-d0744eac5938 |
| Jen Marquez | jtmarquez@thumbtack.com | 5add72e2-80bb-4984-8dd9-53c0ad0adcdc |
| Blaise Anne Cahilog | bacahilog@thumbtack.com | 4398cf9d-609b-4735-bc58-1de1a10efc9b |
| Fitz Reyes | freyes@thumbtack.com | aba63236-39e2-435e-8494-15d4aa89bfd8 |
| Jonny Bryant | jbryant@thumbtack.com | 89063a40-fd11-4c37-b07c-5aad71b4f2e6 |
| Novie Triambulo | ntriambulo@thumbtack.com | 76b3167c-cfa5-46ac-b625-76241bcd1e38 |
| Josh Mckeachnie | jmckeachnie@thumbtack.com | e901cebf-29b7-4c6c-8cf2-37fe71ab5ce9 |
| Arvin Escolano | aescolano@thumbtack.com | 663ac7f4-d6e9-4b54-93b2-2d616d7ffb75 |
| Mel Panal | rlpanal@thumbtack.com | 7ff9f38c-8d32-4049-8203-54a46ecc1876 |
| Jeanne Saplala | jasaplala@thumbtack.com | afd3bbb6-003e-4102-bcc1-e4b5f09ef692 |

### Label taxonomy

> **LABEL GUARDRAIL — read this before assigning any label:**
> Only assign labels that appear in the tables below. These are the labels that exist in the
> Commercial Performance team in Linear as of the last sync. If the work calls for a label
> that is NOT in these tables, do NOT assign it silently. Instead, say:
>
> > "There's no label for **[X]** in the team yet. Should I use **[closest existing label]**
> > as a stand-in, or create a new **[X]** label first?"
>
> Wait for confirmation before creating or assigning any label not on this list.

Apply labels from these categories per issue: one work-type label, one or more team/audience labels, and optionally an issue management label when genuinely warranted.

**Work-type labels** — what kind of work this issue involves:
| Label | ID |
|-------|----|
| Data-pull | fd9b7ddd-566d-4253-ac9c-554aa249425a |
| Analysis | ec1069f6-9fdf-4bcc-a9e5-ec6838abf460 |
| Dashboard | 5c1a2262-4e0a-4f7d-ad74-4fdbf5014dd7 |
| Data-Eng | 4435e114-f66f-4522-829d-2b9a3d04b7a4 |
| Field Enablement | ec13cea7-5588-41dd-b3f3-62b59818d536 |
| Quality | 81fa6660-c9db-4c14-809a-8b59c5f80240 |
| AI Enablement | 3ea99c12-6918-4ecc-9edd-e3707bdc40a0 |
| Bug | aecff861-2ab1-4e04-912e-0750bde69965 |
| Accessibility | a4b1dc9d-70e3-4d04-9f24-f0fd002bd6d4 |

> **No A/B Testing label exists.** If the project involves A/B tests, follow the guardrail
> above: ask whether to create one or use **Analysis** as a stand-in. Do not assign Analysis
> silently — surface it.

**Team/audience labels** — which team or segment this work is *for*:
| Label | ID |
|-------|----|
| All GTM | dd7c5af5-7ee4-4273-a994-09ad5af756b3 |
| All Service | b27554c0-77d6-4ec8-96e1-26e02bd59713 |
| Experiments Team *(ops hub & enterprise partnerships)* | 050f33f0-6ec3-4953-b949-b6cf27f7e025 |
| National | 27a0b748-13d4-4570-af1f-010bb094b661 |
| SMB | 3cdaa449-5f64-4e2c-95e6-8ec8abff0b17 |
| Large Local | ff77d022-0bc6-4f44-924c-08126439685f |
| Strike | 59a2e96c-6100-4884-ba22-0c31ffba4ca1 |
| Partnerships | 4f7fca1f-6017-439b-b9fc-322c9db096f4 |
| Service - Partnerships | 7162b8f9-9906-4aff-ab24-98a7df55753f |
| Service - Special | 8c1d881e-f086-4f73-a90d-48dce38d256d |
| Service - Advanced | 2f22f0a4-da1d-49ee-936a-31630a8d06ef |
| Service - Backoffice | 8b906e6d-33ea-4621-a0d4-7eeb9f096c4d |
| Service - Inbound | 7c726970-8b98-435d-bd17-3890345c54d5 |
| Spanish | a27b090e-b233-4dec-88f9-529323804c0e |
| Trust & Safety | 911ce235-13a4-4405-b301-38c343fb4c20 |
| Comp Team | f0d1ced3-78ac-4263-ad39-701b8d771076 |
| Pro Success | a3de911e-f818-48ff-bd82-f75b7bf398e5 |
| Customer Success | bb6e895c-e45b-4f91-9170-ce89ff056115 |
| Prospecting | 0bf86f7e-0152-4a29-8b1e-d11621728830 |

Domain labels and phase labels exist in the team but are **not used by this skill**. Do not assign them.

**Issue management labels** — additive, use when the issue specifically warrants it:
| Label | ID | When to use |
|-------|----|-------------|
| Initiative | 408ed4ca-e6a7-47b2-bfce-71905820d51f | Critical path item with an identified owner |
| Decision | 25a29aef-8d0e-4009-a734-3b7c1a9de71a | Requires leadership judgment by a specific date |
| Risk | 3aa4dcf7-01cc-444d-8c0d-93446e160622 | Needs monitoring; will escalate if a threshold is crossed |
| Update | b9738f70-0507-4ceb-a036-ceec11b15350 | Progress reporting; no decision needed |
| Influence Dependency | f0fed7b0-1efd-4b56-972f-6e120006afb4 | Blocked on someone outside the team |
| Launch blocker | 9132deec-36fc-49df-aaa4-d064e6a30b11 | Must resolve before a launch milestone |
| AI-assisted | 24ae9351-c079-44f7-bf3d-d719afa5fced | AI helps but a human reviews at decision points |
| AI-owned | 01ed4427-49c6-42fe-8d99-8954c7ff71d2 | Fully executable by an AI agent |

---

## Conversation flow

### Step 1 — Read the brain dump

The user will describe a project in free form. Read it carefully and extract everything you can:
- **Goal**: What outcome are they trying to achieve?
- **Scope signals**: Segments or teams mentioned (National, SMB, All GTM, Service subtypes, etc.)
- **People signals**: Any names or roles mentioned
- **Timeline signals**: Dates, quarters, urgency cues, durations
- **Complexity signals**: Is this one big deliverable or several distinct workstreams?

Don't ask the user to repeat themselves. Work from what they gave you.

### Step 2 — Check for existing projects AND fetch initiatives (do this silently)

Do both of these before asking follow-up questions or showing a plan:

**A. Fetch existing PERF projects:**
```
list_projects: team="07820760-c629-4156-9b4a-7767e6afe467"
```
Scan the project names and descriptions for semantic overlap with what the user described.
If you find a strong match — same theme, same audience, same goal — surface it as a
recommendation before assuming a new project is needed:

> "This sounds like it could fit into the existing **[Project Name]** project — the work
> you're describing is closely related to [brief reason]. Would you like me to add these
> issues there instead of creating a new project?"

A strong match means the scope is genuinely the same bucket of work, not just vaguely related.
Use judgment: two separate initiatives that happen to touch the same segment are not the same
project. When in doubt, surface it and let the user decide — don't silently assume a new project.

If the user explicitly asked to add to an existing project (e.g., "add these to my ICM project"),
skip the new-project path entirely and just create issues in that project. Look up the project by
name if no ID is given:
```
list_projects: team="07820760-c629-4156-9b4a-7767e6afe467"
```
Find the matching project and use its ID for all issue creation.

**B. Fetch initiatives:**
Call `list_initiatives` to identify the best-fit initiative. If the user is adding to an
existing project, skip initiative recommendation — the project already has or doesn't have
an initiative link.

Call `list_initiatives` to get the current list of company initiatives. You'll use this to
recommend the best-fit initiative for the project. Scan names and summaries for overlap with
the project description — look for alignment on audience (GTM, Pro Success, CS), strategic
theme (revenue, retention, tooling, enablement), or explicit program names.

Don't show the raw list to the user. Identify 1–3 candidate initiatives to propose in the plan.
If nothing is a strong match, it's fine to say so — not every project needs an initiative link.

### Step 3 — Ask only what's genuinely missing

After reading the brain dump, ask one focused message with only the questions you couldn't
answer from context. Batch them — don't ask in separate back-and-forths. Key gaps:

1. **Project structure**: Project with milestones, or just issues in the backlog? Briefly
   explain the difference: a project gives a timeline, milestone checkpoints, and progress
   view; issues-only is lighter for smaller work.
2. **Teams/segments impacted**: Which audience labels apply? Show the short list.
3. **People involved**: Who's working on this? Show the team roster.
4. **Start date**: When does work begin? All due dates anchor to this.
5. **Overall timeline**: How long? Hard deadline anchors?

Skip any question you can answer from context.

### Step 4 — Generate and present the plan

Before creating anything in Linear, show the complete plan.

**If adding to an existing project**, use this format:
```
## Adding to: [Existing Project Name]
**Project**: [link or name]
**Milestone**: [Which milestone these issues belong under, if applicable, or "no milestone"]

- [ ] [Issue title] — [Assignee] | [Label1], [Label2]
  - [ ] [Sub-issue] — [Assignee]
- [ ] [Issue title] — [Assignee] | [Label1], [Label2]

---
Does this look right? I'll add these to [Project Name] once you confirm.
```

**If creating a new project**, use this format:
```
## Project: [Name]
**Goal**: [One-sentence goal]
**Start date**: [Date] | **Target completion**: [Date]
**Structure**: [Project with milestones / Issues only]
**Initiative**: [Recommended initiative name + one-sentence reason]
           OR  [No strong match found — skipping initiative link]

---

### Milestone 1: [Name] — target: [date]
- [ ] [Issue title] — [Assignee] | [Label1], [Label2]
  - [ ] [Sub-issue] — [Assignee]  ← only when the parent needs task-level breakdown
  - [ ] [Sub-issue] — [Assignee]
- [ ] [Issue title] — [Assignee] | [Label1], [Label2]

### Milestone 2: [Name] — target: [date]
- [ ] [Issue title] — [Assignee] | [Label1], [Label2]
...

---
Does this look right? Any changes to initiative, assignees, labels, dates, milestones,
or issue breakdown before I create everything?
```

**Initiative recommendation**: Be direct when there's a clear match and explain why briefly.
Be honest when the match is weak: "Closest match is X but the overlap is loose — happy to
skip if you'd rather wait for a better fit." Never force an initiative link.

**Milestones**: Aim for 2–4 per project. Each milestone should be a meaningful checkpoint the
team would demo, report on, or gate the next phase on. For small projects (<4 issues), ask if
milestones are wanted. For sequential work where one phase must complete before the next
starts, milestones are strongly recommended.

**Sub-issues**: Use them when a single issue has 3+ distinct work items that can each be
independently completed and checked off. They add value when the breakdown helps the team
track granular progress — not just to add detail. Show sub-issues indented under their parent.

**Assignee reasoning**:
- Data pulling and engineering → Arvin Escolano, Mel Panal
- Analysis and reporting → whoever has domain expertise on the segment
- Operations and process work → Grindy, Jeanne, Novie, Blaise, Josh, Jen, Fitz
- Unclear → `[TBD]`, noted at the bottom

**Issue sizing**: Issues should be completable in 1–2 weeks. Use sub-issues or split into
multiple issues for larger work. Titles should be action-oriented.

### Step 5 — Incorporate feedback

Show only the changed sections after edits. Confirm before creating.

### Step 6 — Create in Linear

Once confirmed, create in this order:

**If adding to an existing project**, skip to step 3 (issues). Use the existing project's ID
and, if applicable, an existing milestone ID (look it up with `list_milestones: projectId=...`).

**If creating a new project:**

**1. Project:**
```
save_project: name, description, teamId="07820760-c629-4156-9b4a-7767e6afe467",
              startDate, targetDate,
              addInitiatives=[initiative ID]  ← include only if user confirmed
```
Save returned project ID.

**2. Milestones (in order):**
```
save_milestone: name, projectId, targetDate
```
Save each returned milestone ID.

**3. Parent issues:**
```
save_issue: title, description, teamId, assignee, labelIds, dueDate,
            projectId, projectMilestoneId
```
Save each returned issue ID — needed for sub-issues.

**4. Sub-issues:**
```
save_issue: title, description, teamId, assignee, labelIds, dueDate,
            projectId, parentId=[parent issue ID]
```

Create milestone by milestone. After each milestone completes:
"✓ Milestone [N] done — [X] issues, [Y] sub-issues created."

Continue without waiting. Report failures at the end.

### Step 7 — Summarize

- Linear project URL: `https://linear.app/thumbtack/project/[slug]`
- Initiative linked: [name] or "none"
- Totals: [N] milestones, [N] issues, [N] sub-issues
- [TBD] assignees needing manual assignment
- Any failures with suggested next steps

---

## Initiatives

Initiatives are Thumbtack's top-level strategic containers. Linking a project to one gives
leadership visibility into your work automatically. The list changes over time — always fetch
it fresh with `list_initiatives`.

When recommending, look for:
- **Audience overlap**: Pro Success, Customer Success, GTM broadly, etc.
- **Outcome alignment**: Does your project's goal advance the initiative's stated outcome?
- **Explicit name matches**: Does the brain dump name a program that maps to an initiative?

Better to recommend nothing than a poor fit. Surface 1–3 candidates and let the user decide.

---

## Cross-team work

### People from other teams
```
list_users: query="[name]"
```
Use the returned `id` as assignee. Note their team in the plan.

### Issues in another team's backlog
Ask: "This looks like it belongs in [Team]'s backlog — should I create it there or keep it
in PERF with them as the assignee?"

If creating in another team:
```
list_teams: query="[team name]"
```
Use that team's `id` as `teamId` in `save_issue`.

### Cross-team labels
- Apply the relevant team/audience label if one exists
- Use the **Influence Dependency** issue management label when PERF is waiting on another team to unblock progress

---

## Adding new labels

**Never create or assign a label that isn't in the label taxonomy tables above without asking first.**

If you think a label is needed and it doesn't exist:
1. Name the missing label and explain why you think it's needed
2. Suggest the closest existing label as a stand-in
3. Ask: "Should I use **[closest label]** for now, or create a new **[X]** label first?"

Wait for an explicit answer before proceeding. Do not silently fall back to a different label.

---

## Quick label reference

- Pulling raw data → **Data-pull**
- Interpreting or modeling data → **Analysis**
- Building visual reports → **Dashboard**
- Engineering pipelines / ETL → **Data-Eng**
- Training, playbooks, enablement → **Field Enablement**
- QA, testing, quality checks → **Quality**
- A/B tests → no label yet; flag it, use **Analysis** as fallback
- AI tools / workflow automation → **AI Enablement**
- Work for the Experiments team → **Experiments Team** (ops hub, not A/B testing)

---

## Daily Progress Check Flow

This flow runs automatically at 6pm ET every day, or whenever the user asks for a progress
check. It scans connected tools for completion signals, presents a report, and updates Linear
only after the user signs off. Never update any issue without explicit approval.

### Step A — Identify the current user (silently)

Match the session user to the team roster by email. If not found in the roster (the user may
be a PERF member assigned issues in another team's backlog), call:
```
list_users: query="[name or email]"
```
Use the returned Linear user ID for all subsequent queries. Store as `CURRENT_USER_ID`.

### Step B — Fetch all open issues assigned to the user (silently)

```
list_issues: assignee=CURRENT_USER_ID
```

This returns issues across **all teams** — not just PERF. The user may be assigned work in
any Linear team. Collect issue IDs, titles, project names, and current status. Filter to
only issues with status type `backlog`, `unstarted`, or `started` (skip Done and Canceled).

### Step C — Pull 24-hour signals from connected tools (silently, run all three)

**1. Granola** — query meetings from the last 24 hours:
```
query_granola_meetings: query="[comma-separated issue IDs and project names]"
                        dateRange="last 24 hours"
```
Scan transcripts and notes for mentions of issue IDs, issue titles, or project names.
Extract any sentence within 2 lines of a match — this is the signal quote.

**2. Slack** — search for issue ID and project name mentions:
```
slack_search_public_and_private: query="[issue IDs] OR [project names]" after:"yesterday"
```
Look for messages containing issue identifiers (e.g. "PERF-261") or issue titles. Note the
channel, sender, and message text as the signal source.

**3. Email** — search for relevant threads:
```
search_threads: query="[issue IDs] OR [project names]" after:"yesterday"
```
Look for subject lines or body text mentioning issue IDs or project/milestone names.

### Step D — Classify each issue

For each open issue, score the signals found:

| Signal | Classification |
|--------|---------------|
| "done", "completed", "finished", "shipped", "closed", "handed off", "signed off" near issue mention | ✅ Likely Complete |
| "in progress", "working on", "started", "reviewing", "drafted" near issue mention | 🔄 In Progress |
| Issue mentioned but no clear direction word | 🔄 In Progress |
| No mention in any source | 📭 No Signal |

A single strong signal from any source is enough to classify. When in doubt, use the lower
confidence tier — err on the side of not marking things done.

### Step E — Present the report

Open with the date and the user's name. Format:

```
## Daily Progress Check — [Weekday, Month Day]
Hi [Name] — here's what I found across your Granola, Slack, and email from the last 24 hours.

### ✅ Likely Complete ([N] issues)
- **[ISSUE-ID]**: [Issue title] — *[Project name]*
  > Signal ([source]): "[relevant quote]"

### 🔄 In Progress ([N] issues)
- **[ISSUE-ID]**: [Issue title] — *[Project name]*
  > Signal ([source]): "[relevant quote]"

### 📭 No Signal ([N] issues)
- **[ISSUE-ID]**: [Issue title] — *[Project name]*
...

---
To mark issues as done, reply with issue IDs (e.g. "PERF-261, PERF-282") or say
**"approve all likely complete"** and I'll update Linear. Say **"skip"** if nothing to update.
```

If there are no open issues, say: "No open issues assigned to you right now."
If all tools return no signals, say so honestly and list the open issues with no activity.

### Step F — Wait for sign-off

Parse the user's response:
- **"approve all"** or **"approve all likely complete"** → mark every ✅ issue as Done
- **Issue IDs listed** (e.g. "PERF-261, PERF-303") → mark only those as Done
- **"skip"** or **"nothing"** or **"none"** → make no changes, confirm nothing was updated

Do not proceed until you receive one of these responses. If the reply is ambiguous, ask:
"Just to confirm — should I mark [X] as done?"

### Step G — Update Linear

For each confirmed issue:
```
save_issue: id=[ISSUE-ID], state="Done", team=[team ID]
```

After marking an issue done, check whether it has a parent issue. If the parent's remaining
open sub-issues are now all done, offer:
> "All sub-issues under [parent title] are now complete — want me to mark the parent done too?"

After all updates, summarize:
```
✓ Marked [N] issues as Done:
- PERF-261: Transfer comp calc & payout — Inbound
- ...

[N] issues left open. See you tomorrow at 6pm ET.
```

---

## EOD Incoming Work Scan Flow

This flow runs at 6pm ET daily (after the progress check), or whenever the user asks what's
been asked of them. It scans connected tools for new requests, action items, and deliverables
directed at the user, deduplicates against existing Linear issues, and creates new tickets
only after sign-off. Never create issues without explicit approval.

### Step H — Identify the current user (silently)

Same as Step A in the Daily Progress Check flow — match session email to team roster, or call
`list_users` if not found. Store as `CURRENT_USER_ID` and `CURRENT_USER_NAME`.

### Step I — Fetch existing open issues to deduplicate against (silently)

```
list_issues: assignee=CURRENT_USER_ID
```

Also call `list_projects: team="07820760-c629-4156-9b4a-7767e6afe467"` to get project names
for matching. Store issue titles and project names as the dedup index — you'll use this in
Step K to avoid creating tickets for work that's already tracked.

### Step J — Scan last 24 hours across all connected tools (silently, run all three)

You're looking for **new asks, action items, and deliverables** directed at this user — not
completion signals. Focus on what's being requested, not what's been done.

**1. Granola** — scan meeting notes for action items:
```
query_granola_meetings: query="action items [CURRENT_USER_NAME] deliverable"
                        dateRange="last 24 hours"
```
Extract lines matching any of these patterns:
- "[User name] to [verb]..." / "[User name] will [verb]..."
- "Action: [User name]..."
- "AI: [User name]..." (action item shorthand)
- Any sentence with a verb + deadline that names the user
Also flag any discussion of a new project, initiative, or workstream not yet in Linear.

**2. Slack** — search for direct asks and mentions:
```
slack_search_public_and_private: query="@[username] OR [CURRENT_USER_NAME]" after:"yesterday"
```
Also run a second search for common ask patterns in channels the user is likely in:
```
slack_search_public_and_private: query="can you [CURRENT_USER_NAME] OR [CURRENT_USER_NAME] please OR need [CURRENT_USER_NAME]" after:"yesterday"
```
Look for:
- Direct @mentions with a request ("@kinza can you..." / "kinza, could you...")
- DM-style messages asking for deliverables
- Threads where the user was tagged and a task was implied
- New project or workstream discussions that involve the user

**3. Email** — search for inbound requests:
```
search_threads: query="to:[user email] OR [CURRENT_USER_NAME]" after:"yesterday"
```
Look for:
- Emails addressed to the user asking for something
- Forwarded threads with a note like "can you handle this"
- Meeting invites with attached briefs or asks
- Any explicit deadline or deliverable mentioned

### Step K — Extract and classify new work items

For each signal found, extract a candidate work item. A work item must have:
- A clear **action** (something to do, not just FYI)
- An implied or explicit **owner** that is the current user
- Enough specificity to become a Linear issue title

Classify each candidate:

| Type | Signal pattern | Example |
|------|---------------|---------|
| 🎯 **Action item** | "Kinza to...", "AI: Kinza", "@kinza can you" | "Kinza to pull SMB comp data by Friday" |
| 📦 **Deliverable** | "need X by [date]", "send me X", "share X" | "Need the quota tracker updated by EOD" |
| 🏗️ **New project** | Discussion of a new initiative or workstream | "We should set up a new process for..." |
| ❓ **Ambiguous** | Unclear if it's an ask or just a discussion mention | Flag for review, don't create |

**Deduplication**: For each candidate, check whether a semantically similar issue already
exists in the user's open issues or in the PERF project list. If it's clearly the same work
(same goal, same deliverable, same segment), mark it as `[already tracked as ISSUE-ID]` and
exclude it from the creation list. When in doubt, surface it and let the user decide.

### Step L — Present the incoming work report

```
## EOD Incoming Work Scan — [Weekday, Month Day]
Hi [Name] — here's what came in today that isn't tracked in Linear yet.

### 🎯 Action Items ([N])
- **[Short title]**
  Source: [Granola/Slack/Email] — "[exact quote or paraphrase]"
  Suggested: [Assignee] | [Labels] | Project: [existing project or "new project needed"] | Due: [date or TBD]

### 📦 Deliverables ([N])
- **[Short title]**
  Source: [source] — "[quote]"
  Suggested: [Assignee] | [Labels] | Project: [project] | Due: [date or TBD]

### 🏗️ New Projects / Workstreams ([N])
- **[Short title]**
  Source: [source] — "[quote]"
  Suggested: New project — [proposed name and one-line description]

### ❓ Ambiguous / Needs Clarification ([N])
- **[Short title]** — not sure if this is an ask or FYI. [Source] — "[quote]"

### ✅ Already Tracked ([N])
- "[quote]" → already tracked as [ISSUE-ID]: [Issue title]

---
Reply with:
- **"create all"** to create everything in the 🎯 📦 🏗️ sections
- Issue numbers (1, 2, 3...) to create specific items
- Edits to any item (title, assignee, label, project, due date) before I create
- **"skip"** to close without creating anything
```

If no new work was found, say: "Nothing new came in today that isn't already tracked. 🎉"

### Step M — Incorporate edits and wait for sign-off

If the user requests changes to any item (title, assignee, labels, project, due date), update
that item in the report and re-show only the changed item. Confirm before creating.

For **new project** items: if the user confirms, check existing PERF projects first for a
match. If none found, propose a project name and structure:
> "I'll create a new project called **[name]** — want milestones or just issues for now?"

Parse the response:
- **"create all"** → create every non-ambiguous item
- **Numbers listed** → create only those items
- **"skip"** or **"nothing"** → confirm nothing was created
- Ambiguous reply → ask: "Just to confirm — should I create [item title]?"

### Step N — Create in Linear

For each confirmed work item, determine the right project and create the issue.

**For action items and deliverables (issues in an existing project):**

1. If a matching project exists, use it:
```
save_issue: title, description, teamId="07820760-c629-4156-9b4a-7767e6afe467",
            assignee=CURRENT_USER_ID, labelIds, dueDate, projectId
```

2. If no project match, create the issue in the team backlog (no projectId) and note it:
```
save_issue: title, description, teamId="07820760-c629-4156-9b4a-7767e6afe467",
            assignee=CURRENT_USER_ID, labelIds, dueDate
```
> "Added to the PERF backlog — no existing project matched. You can assign it to a project later."

**For new projects / workstreams**: Follow the full Project Planning flow (Steps 1–7) inline.
Ask the minimal questions needed (milestones or just issues? target date?) before creating.

**Label assignment**: Follow the label guardrail. Infer from the ask:
- Data or reporting request → **Data-pull** or **Analysis**
- Process or enablement → **Field Enablement**
- Dashboard or tracker → **Dashboard**
- Engineering or automation → **Data-Eng** or **AI Enablement**
- Unclear → omit label and note it

**Assignee**: Default to `CURRENT_USER_ID` (the work was asked of this person). If the ask
clearly involves a teammate, add them as a second assignee or note it in the description.

After all creates, summarize:
```
✓ Created [N] new issues:
- PERF-[X]: [Title] → [Project name] | [Labels]
- PERF-[X]: [Title] → [Project name] | [Labels]

[N] items skipped or deferred. All done for today — see you tomorrow at 6pm ET.
```
