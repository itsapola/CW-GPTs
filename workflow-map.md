# Workflow Map

The CalmWave AI Workflow Suite was designed as a modular system.

Users could enter through the specialist most relevant to the task, then move work through strategy, governance, execution, measurement, and operations as needed.

The suite did not require every workflow to pass through every GPT.

Instead, it supported repeatable combinations of specialists based on the business problem.

## Core System Flow

```text
INTELLIGENCE
ABM Researcher / Simon
        ↓
STRATEGY
Amelie
        ↓
GOVERNANCE
WaveForm
        ↓
EXECUTION
Charlie / Juno / Nelson / Fiona / Gregor
        ↓
MEASUREMENT
Simon
        ↓
OPERATIONS
Gem
```

## Specialist Roles

```text
ABM Researcher
Research, call analysis, account intelligence, ABM briefs

Amelie
Strategy, prioritization, challenge, executive decision support

WaveForm
Brand voice, messaging alignment, terminology, claims discipline

Charlie
Copywriting, editing, content development, message adaptation

Juno
Website strategy, UX, SEO, CRO, information architecture

Nelson
Email campaigns, nurture sequences, lifecycle, automation

Fiona
Social media, community strategy, engagement, moderation

Gregor
Video strategy, production planning, filmography, editing

Simon
Analytics, interpretation, reporting, measurement planning

Gem
Marketing operations, coordination, documentation, follow-through
```

## Entry Points

Users entered the system based on the problem they were trying to solve.

| Need                                    | Starting specialist |
| --------------------------------------- | ------------------- |
| Research a target account               | ABM Researcher      |
| Analyze a sales or customer call        | ABM Researcher      |
| Challenge a proposed strategy           | Amelie              |
| Prepare an executive recommendation     | Amelie              |
| Review brand voice or messaging         | WaveForm            |
| Draft or improve copy                   | Charlie             |
| Audit a website or landing page         | Juno                |
| Build an email campaign                 | Nelson              |
| Plan social content or engagement       | Fiona               |
| Develop a video concept or edit plan    | Gregor              |
| Interpret campaign performance          | Simon               |
| Organize actions, owners, and deadlines | Gem                 |

## Routing Logic

```text
Does the task require evidence or context?
        ├── Yes → ABM Researcher or Simon
        └── No
             ↓
Does the task require a strategic decision?
        ├── Yes → Amelie
        └── No
             ↓
Does the task require brand or message validation?
        ├── Yes → WaveForm
        └── No
             ↓
Which execution channel is involved?
        ├── General copy → Charlie
        ├── Website → Juno
        ├── Email → Nelson
        ├── Social/community → Fiona
        └── Video → Gregor
             ↓
Does performance need to be evaluated?
        ├── Yes → Simon
        └── No
             ↓
Does the work need coordination or follow-up?
        ├── Yes → Gem
        └── Complete
```

## Standard Handoff Packet

When work moved between specialists, the handoff should preserve:

```text
OBJECTIVE
What business outcome is being pursued?

AUDIENCE
Who is the work intended for?

CONTEXT
What background does the next specialist need?

EVIDENCE
What facts, research, data, or source material support the work?

DECISIONS
What has already been approved or ruled out?

CONSTRAINTS
What must remain fixed?

ASSUMPTIONS
What is being inferred rather than confirmed?

OPEN QUESTIONS
What remains unresolved?

EXPECTED OUTPUT
What should the next specialist produce?

REVIEW OWNER
Who is accountable for approving the result?
```

## Campaign Workflow

```text
ABM Researcher
Builds account and audience intelligence
        ↓
Amelie
Defines the campaign thesis and priorities
        ↓
WaveForm
Validates message and positioning alignment
        ↓
Charlie
Develops core campaign copy
        ↓
Channel Specialist
Juno / Nelson / Fiona / Gregor
        ↓
Simon
Evaluates performance and implications
        ↓
Gem
Organizes actions, owners, and follow-up
```

### Typical outputs

| Stage             | Output                                                    |
| ----------------- | --------------------------------------------------------- |
| Research          | Account brief, audience insight, opportunity summary      |
| Strategy          | Campaign thesis, priorities, risks, recommendation        |
| Governance        | Approved messaging direction, claims flags, tone guidance |
| Copy              | Core narrative, headlines, supporting copy                |
| Channel execution | Landing page, email sequence, social plan, or video brief |
| Measurement       | Performance interpretation and recommended action         |
| Operations        | Task plan, owners, dependencies, and deadlines            |

## ABM Workflow

```text
ABM Researcher
Company, stakeholder, and opportunity research
        ↓
ABM Researcher
Call or transcript analysis
        ↓
Amelie
Strategic account hypothesis
        ↓
WaveForm
Message alignment
        ↓
Charlie
Account-specific messaging
        ↓
Nelson
Email sequence
        ↓
Simon
Engagement analysis
        ↓
Gem
Sales and marketing follow-up
```

### Decision gates

* Is the account information verified?
* Are assumptions clearly labeled?
* Is the message sufficiently specific to the account?
* Are claims supported?
* Is the next action defined?
* Is sales or executive review required?

## Website Optimization Workflow

```text
Simon
Reviews available traffic and conversion data
        ↓
Juno
Audits UX, SEO, information architecture, and CRO
        ↓
Amelie
Prioritizes strategic opportunities
        ↓
WaveForm
Reviews messaging and positioning
        ↓
Charlie
Develops revised copy
        ↓
Juno
Maps copy into the user journey
        ↓
Gem
Creates implementation plan
        ↓
Simon
Measures performance after launch
```

### Decision gates

* Is the issue observed or hypothesized?
* Is analytics data available?
* Is the problem messaging, UX, traffic quality, or conversion?
* Which recommendation has the highest expected impact?
* What should be tested before permanent implementation?

## Email and Lifecycle Workflow

```text
Amelie
Defines objective, audience, and strategic role
        ↓
Nelson
Designs journey, segmentation, timing, and automation
        ↓
WaveForm
Validates message direction
        ↓
Charlie
Drafts campaign copy
        ↓
Nelson
Adapts copy across the sequence
        ↓
Simon
Evaluates delivery, engagement, and conversion
        ↓
Gem
Coordinates iteration and follow-up
```

### Decision gates

* What behavior should the sequence influence?
* Which audience segments require different treatment?
* What triggers entry or exit?
* What should happen after each action?
* Are performance benchmarks defined?
* Does the automation require human intervention?

## Social and Community Workflow

```text
Amelie
Defines campaign or community objective
        ↓
Fiona
Develops channel and engagement strategy
        ↓
WaveForm
Reviews tone and message alignment
        ↓
Charlie
Develops supporting copy
        ↓
Fiona
Adapts content to platform and community context
        ↓
Simon
Interprets engagement and audience response
        ↓
Gem
Coordinates publishing and follow-up
```

### Decision gates

* Is the goal awareness, engagement, education, conversion, or trust?
* Is the content appropriate for the platform?
* Does the response strategy distinguish criticism from misinformation?
* Does the plan build community or merely increase publishing volume?
* Is escalation required for sensitive responses?

## Video Workflow

```text
Amelie
Defines objective, audience, and strategic message
        ↓
WaveForm
Validates narrative and claims
        ↓
Charlie
Develops script or interview language
        ↓
Gregor
Creates concept, storyboard, shot plan, and edit approach
        ↓
Fiona / Nelson / Juno
Adapts distribution by channel
        ↓
Simon
Evaluates performance
        ↓
Gem
Coordinates revisions and reuse
```

### Decision gates

* What should the audience think, feel, or do?
* Is video the right format?
* What production constraints exist?
* Which shots are essential?
* Which claims or statements require review?
* How will the asset be distributed and measured?

## Executive Communications Workflow

```text
Simon
Provides performance or evidence context
        ↓
Amelie
Defines strategic narrative and decision framing
        ↓
Charlie
Develops the draft
        ↓
WaveForm
Reviews tone, message discipline, and claims
        ↓
Gem
Coordinates approval and distribution
```

### Decision gates

* What decision or action is required?
* What is the most material point?
* Which facts support it?
* What risk or tradeoff must be acknowledged?
* What can be removed without weakening the argument?
* Who must approve the final version?

## Analytics Workflow

```text
Simon
Validates available data and definitions
        ↓
Simon
Identifies trends, anomalies, and limitations
        ↓
Amelie
Interprets strategic implications
        ↓
Gem
Translates findings into actions and owners
```

### Required distinctions

```text
OBSERVATION
What happened?

INTERPRETATION
What might explain it?

LIMITATION
What cannot be concluded?

RECOMMENDATION
What should be done next?

MEASUREMENT
What data would confirm or reject the hypothesis?
```

## Brand Review Workflow

```text
Original draft or concept
        ↓
WaveForm
Reviews voice, tone, positioning, terminology, and claims
        ↓
Decision
        ├── Aligned → Proceed
        ├── Needs revision → Charlie or channel specialist
        └── Strategic conflict → Amelie or human brand owner
```

### Review outcomes

* approved
* approved with minor edits
* revision required
* unsupported claim
* messaging conflict
* insufficient context
* human decision required

## Operations Workflow

```text
Meeting notes, strategy, campaign output, or analysis
        ↓
Gem
Extracts decisions and actions
        ↓
Gem
Identifies owners, dependencies, and deadlines
        ↓
Human confirmation
        ↓
Gem
Produces final operating plan
```

### Standard operational output

```text
DECISION
What was agreed?

ACTION
What needs to happen?

OWNER
Who is accountable?

DEADLINE
When is it due?

DEPENDENCY
What must happen first?

RISK
What could block progress?

OPEN QUESTION
What remains unresolved?
```

## Review Escalation Flow

```text
Is the output public-facing?
        ├── Yes → Functional or brand review
        └── No
             ↓
Does it contain a material claim?
        ├── Yes → Evidence and claims review
        └── No
             ↓
Does it involve clinical, legal, regulatory, or sensitive content?
        ├── Yes → Subject-matter review required
        └── No
             ↓
Could an error materially affect reputation, trust, or business decisions?
        ├── Yes → Senior human review
        └── No → Standard review
```

## Failure and Recovery Flow

```text
Weak or incorrect output identified
        ↓
Classify the issue
        ├── Missing context
        ├── Factual error
        ├── Specialist drift
        ├── Governance failure
        ├── Poor usability
        └── Handoff failure
        ↓
Determine corrective action
        ├── Improve input requirements
        ├── Revise role boundaries
        ├── Update knowledge source
        ├── Tighten output structure
        ├── Add escalation rule
        ├── Add test case
        └── Redirect to another specialist
        ↓
Retest
        ↓
Document resolution
```

## Workflow Principles

1. Start with the business problem, not the tool.
2. Use the minimum number of specialists needed.
3. Preserve evidence and decisions through handoffs.
4. Separate research, strategy, governance, and execution.
5. Do not allow channel execution to silently redefine strategy.
6. Route brand conflicts to WaveForm or the human brand owner.
7. Route strategic conflicts to Amelie or the accountable decision-maker.
8. Route uncertain performance conclusions to Simon.
9. Route execution coordination to Gem.
10. Escalate when risk exceeds the system’s authority.

## Core Workflow Principle

> The system should move work forward without allowing context, accountability, or evidence to disappear between stages.

