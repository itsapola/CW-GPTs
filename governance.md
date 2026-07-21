# Governance Framework

The CalmWave AI Workflow Suite was governed as an internal decision-support system, not as an autonomous authority.

Governance was designed to ensure that the suite could improve speed, consistency, and access to expertise without obscuring accountability, weakening review standards, or increasing risk.

The framework focused on six core areas:

* human accountability
* role and scope control
* information handling
* factual integrity
* review and escalation
* ongoing oversight

## Governance Objectives

The governance model was designed to answer the following questions:

1. Who is accountable for the final output?
2. What is each GPT allowed to do?
3. What information can the systems use?
4. How should uncertainty and unsupported claims be handled?
5. When is human review mandatory?
6. How are failures, drift, and misuse identified and corrected?

The objective was not to eliminate all risk.

The objective was to make risk visible, assign ownership clearly, and prevent AI-generated work from bypassing normal judgment and approval processes.

## 1. Human Accountability

Human users remained responsible for all consequential decisions and public-facing outputs.

The GPTs could assist with:

* research
* synthesis
* drafting
* analysis
* planning
* prioritization
* recommendations
* workflow coordination

They could not assume final accountability for:

* business strategy
* clinical or medical claims
* legal or regulatory interpretation
* financial decisions
* external communications
* customer-facing commitments
* executive decisions
* publication or distribution

### Accountability principle

> AI may support the work, but a named human remains accountable for the decision and the final output.

Human review was not treated as a procedural checkbox. The reviewer needed enough context and authority to assess whether the output was accurate, appropriate, and ready to use.

## 2. Role and Scope Governance

Each GPT had a defined role, intended use case, and operating boundary.

This was necessary to prevent specialist drift and reduce the risk of users treating every GPT as a general-purpose authority.

### Each GPT required

* a clearly stated purpose
* defined target users
* expected inputs
* standard outputs
* known limitations
* prohibited uses
* escalation conditions
* review requirements

### Examples of scope boundaries

* ABM Researcher could synthesize account intelligence but could not treat inference as verified fact.
* WaveForm could assess brand alignment but could not independently redefine approved positioning.
* Amelie could challenge strategy but could not make final executive decisions.
* Charlie could draft copy but could not invent claims or customer evidence.
* Simon could interpret performance data but could not claim causation without sufficient evidence.
* Juno could recommend tests but could not present hypotheses as confirmed UX findings.
* Gem could organize work but could not assign accountability without human confirmation.

### Out-of-scope behavior

When a request exceeded a GPT’s intended role, the system should:

1. identify the scope mismatch
2. explain the limitation
3. redirect the user to the appropriate specialist or human owner
4. avoid completing the task under false authority

## 3. Human-in-the-Loop Review

Review requirements were determined by the consequence and risk of the output.

### Low-risk outputs

Examples:

* internal brainstorming
* rough outlines
* meeting summaries
* draft task lists
* early creative exploration

These outputs still required user judgment, but formal approval was generally not necessary.

### Moderate-risk outputs

Examples:

* campaign drafts
* website recommendations
* account briefs
* email sequences
* performance interpretations
* executive presentation drafts

These required review by the appropriate marketing, functional, or business owner before use.

### High-risk outputs

Examples:

* clinical or medical claims
* legal or regulatory language
* external statements
* sensitive customer communications
* high-stakes executive recommendations
* claims affecting reputation, compliance, or patient trust

These required explicit subject-matter review and could not be treated as final based on AI output alone.

### Review principle

> The greater the consequence, uncertainty, permanence, or external exposure, the stronger the review requirement.

## 4. Information Classification

Not all information was appropriate for use in the suite.

Information handling should follow a simple classification model.

### Public

Information already publicly available and approved for external use.

Examples:

* published website content
* public reports
* public company information
* approved campaign assets
* public social media content

Generally suitable for use, subject to source and recency checks.

### Internal

Non-public information used for routine business operations.

Examples:

* internal plans
* working documents
* draft messaging
* internal analysis
* non-public workflows

Could be used only when necessary and appropriate for the task.

### Confidential

Information that could create material business, privacy, legal, or reputational risk if exposed.

Examples:

* unreleased strategy
* customer details
* internal performance data
* proprietary positioning
* contracts
* sensitive financial information
* confidential partner information

Use should be minimized and subject to stricter controls.

### Restricted

Information that should not be entered into the systems.

Examples:

* protected health information
* patient-identifiable information
* passwords
* API keys
* access credentials
* private legal advice
* regulated personal data
* unnecessary sensitive employee information

Restricted information should not be used unless the system and environment were explicitly approved for that category of data.

## 5. Data Minimization

The suite followed a minimum-necessary principle.

Users should provide only the information required to complete the task.

The systems should not request:

* personal information unrelated to the task
* full records when excerpts would be sufficient
* sensitive customer details where anonymized data would work
* credentials
* private identifiers
* broad data access for narrowly defined tasks

### Data minimization principle

> Do not provide more information than the workflow requires.

When possible, users should:

* redact names
* anonymize examples
* summarize sensitive context
* remove identifiers
* use synthetic data for testing
* avoid uploading entire internal repositories unnecessarily

## 6. Confidentiality and Access

Access to the suite should reflect job responsibilities and business need.

Not every user required access to every GPT, knowledge source, or workflow.

### Access principles

* limit access to approved users
* separate sensitive workflows where appropriate
* review access periodically
* remove access when roles change
* retire inactive systems
* avoid public sharing of internal GPTs
* avoid embedding confidential material in publicly accessible configurations

Access control was especially important when GPTs used uploaded knowledge or internal operating documents.

## 7. Knowledge Source Governance

A GPT’s output quality depended heavily on the quality of the information available to it.

Knowledge sources should be:

* approved
* relevant
* current
* attributable
* appropriately scoped
* free from unnecessary sensitive information

### Source requirements

Each important knowledge source should have:

* an owner
* a date
* a clear status
* a defined purpose
* a review cadence
* a process for replacement or retirement

### Source risks

Governance should account for:

* outdated documents
* conflicting versions
* draft materials mistaken for approved guidance
* unofficial language treated as policy
* obsolete product information
* unverified external sources
* incomplete context

### Source precedence

Where sources conflicted, the system should not silently choose one.

It should:

1. identify the conflict
2. state which source appears newer or more authoritative
3. explain the effect on the output
4. request human confirmation where necessary

## 8. Factual Integrity

The systems were expected to distinguish clearly between evidence and interpretation.

Outputs should separate:

* verified facts
* user-provided information
* sourced findings
* inferred conclusions
* assumptions
* recommendations
* unresolved questions

### Prohibited behaviors

The GPTs should not:

* fabricate sources
* invent customer evidence
* alter statistics
* imply certainty unsupported by data
* create quotes that appear real
* generate false case studies
* invent approvals
* present assumptions as confirmed facts
* conceal missing information

### Verification expectations

Users should verify:

* names
* dates
* metrics
* claims
* citations
* product details
* customer references
* regulatory language
* competitive comparisons
* time-sensitive information

## 9. Claims Governance

Claims required particular scrutiny because they could create legal, regulatory, reputational, or trust risk.

### High-risk claims included

* clinical efficacy
* medical outcomes
* safety
* compliance
* performance guarantees
* comparative superiority
* customer results
* financial impact
* market leadership
* quantified outcomes

### Required controls

High-risk claims should be:

* supported by approved evidence
* traceable to a source
* reviewed by the appropriate owner
* written with appropriate qualification
* consistent with approved language
* withheld when support was insufficient

The GPTs should never “improve” a claim by making it broader, stronger, or more certain than the source material allowed.

## 10. Brand Governance

WaveForm served as the central brand-governance specialist within the suite.

Its role was to help maintain consistency across:

* voice
* tone
* terminology
* positioning
* value propositions
* claim language
* audience adaptation
* channel expression

However, brand governance remained rooted in approved human-authored standards.

WaveForm could evaluate and apply those standards. It could not replace them.

### Brand governance controls

* use approved messaging as the reference point
* flag deviations
* distinguish intentional adaptation from inconsistency
* prevent unsupported language from becoming normalized
* avoid generic AI phrasing
* preserve audience and channel context
* escalate unclear positioning decisions

## 11. Privacy and Sensitive Information

The suite was not intended to process patient-identifiable or otherwise restricted personal information.

Users should avoid entering:

* protected health information
* patient names
* treatment records
* medical histories
* personal identifiers
* private employee matters
* unnecessary customer details
* confidential legal or financial records

Where sensitive material was necessary for a legitimate business process, the workflow required confirmation that the environment and use case were approved.

### Privacy principle

> Convenience does not override data-handling obligations.

## 12. Security Practices

Users should not enter or upload:

* passwords
* secret keys
* API credentials
* authentication tokens
* private certificates
* system access details
* confidential code secrets

Repositories documenting the suite should exclude:

* `.env` files
* credentials
* internal exports
* private knowledge files
* live GPT configurations
* proprietary prompts
* confidential screenshots
* customer or patient information

Public portfolio materials should use synthetic or sanitized examples only.

## 13. External Research Governance

Research outputs required additional scrutiny because public sources vary in quality, recency, and reliability.

Research-focused systems should:

* identify sources
* distinguish primary from secondary sources
* note publication dates
* flag outdated information
* identify conflicts
* avoid relying on a single weak source
* separate sourced findings from inference
* state when information could not be verified

### Research principle

> A plausible summary is not a substitute for traceable evidence.

## 14. Analytics Governance

Simon and other analytics workflows were expected to preserve analytical integrity.

The systems should distinguish between:

* observation
* correlation
* hypothesis
* interpretation
* causal conclusion
* recommendation

### Analytics controls

* preserve original numbers
* identify missing baselines
* avoid false precision
* disclose incomplete data
* avoid causal claims without support
* distinguish statistically meaningful change from normal variation
* show calculation logic where useful
* identify data-quality limitations

The goal was to prevent polished narrative from outrunning the evidence.

## 15. Escalation Framework

The GPTs should escalate rather than proceed when:

* information was materially incomplete
* sources conflicted
* a high-risk claim lacked support
* confidential information appeared unexpectedly
* the user requested legal, clinical, or regulatory authority
* the task exceeded the GPT’s role
* the output could materially affect reputation or patient trust
* a decision required executive or subject-matter ownership
* uncertainty could meaningfully change the recommendation

### Escalation response

An appropriate escalation should include:

1. what cannot be confirmed
2. why the issue matters
3. what risk exists
4. who should review it
5. what information is needed next

Escalation should be specific and actionable, not a vague disclaimer.

## 16. Prohibited Uses

The suite should not be used to:

* make autonomous clinical decisions
* diagnose or recommend treatment
* provide final legal advice
* approve regulated claims
* generate deceptive evidence
* impersonate real individuals
* fabricate customer testimonials
* conceal AI involvement where disclosure is required
* process restricted information without approval
* bypass organizational review
* automate employment decisions
* generate discriminatory targeting or messaging
* publish unverified external claims

## 17. Change Management

Changes to a GPT could affect accuracy, scope, tone, and risk.

Material changes should be treated as product changes rather than casual prompt edits.

### Changes requiring review

* new system instructions
* expanded scope
* new knowledge files
* altered output formats
* changed escalation logic
* new external data sources
* changes to claims guidance
* modifications affecting brand behavior
* public sharing or broader access

### Change process

1. document the proposed change
2. identify the expected benefit
3. identify new risks
4. test against representative scenarios
5. rerun relevant golden-set and edge-case tests
6. compare against the previous version
7. approve or revise
8. record the release

## 18. Versioning and Documentation

Each GPT should have a documented version and change history.

Minimum documentation should include:

* name
* owner
* purpose
* current version
* last review date
* approved knowledge sources
* known limitations
* required review level
* recent changes
* retirement status

This reduced the risk of teams using outdated or unofficial versions.

## 19. Ownership

Every GPT required a human owner.

The owner was responsible for:

* maintaining scope
* approving material changes
* reviewing knowledge sources
* monitoring recurring failures
* coordinating testing
* clarifying escalation rules
* determining when the GPT should be updated, consolidated, or retired

Ownership could not be assigned to “the AI team” in the abstract.

A named person or function needed to be accountable.

## 20. Monitoring and Failure Review

Governance continued after launch.

Useful monitoring signals included:

* recurring factual errors
* repeated user confusion
* frequent overrides
* off-brand outputs
* inappropriate certainty
* attempts to use the GPT outside its scope
* stale source material
* duplicated capability
* low adoption
* outputs requiring extensive correction

### Failure review record

Each material failure should capture:

* prompt
* output
* expected behavior
* observed failure
* risk
* likely cause
* corrective action
* owner
* regression test
* resolution status

Failures were treated as evidence for improving the system, not as isolated user mistakes.

## 21. Periodic Review

Each GPT should be reviewed periodically to determine whether it remained useful, accurate, and appropriately governed.

Review should consider:

* continued business need
* role clarity
* knowledge freshness
* quality performance
* user adoption
* governance compliance
* overlap with other GPTs
* risk profile
* maintenance burden

Possible review outcomes included:

* continue
* revise
* restrict
* consolidate
* replace
* retire

## 22. Retirement

A GPT should be retired when:

* the business need no longer existed
* ownership was unclear
* knowledge could not be maintained
* quality remained inconsistent
* risk outweighed value
* another system replaced the capability
* the organization or workflow changed materially
* access could no longer be governed appropriately

Retirement should include:

* disabling or removing access
* archiving documentation
* identifying replacement workflows
* removing outdated knowledge sources
* preserving relevant evaluation records
* communicating the change to users

The CalmWave suite is represented in this portfolio as retired.

No live configurations, proprietary instructions, or internal knowledge sources are included.

## Governance Roles

### GPT Owner

Responsible for the health and continued relevance of an individual GPT.

### Functional Reviewer

Evaluates whether outputs are accurate and useful within the relevant discipline.

### Brand Reviewer

Reviews brand, messaging, voice, and claim alignment where required.

### Subject-Matter Expert

Reviews technical, clinical, legal, regulatory, or otherwise specialized content.

### End User

Uses the system responsibly, supplies appropriate context, verifies outputs, and follows review requirements.

### Executive Sponsor

Provides direction, resolves ownership conflicts, and determines acceptable risk for material use cases.

## Governance Checklist

Before a GPT is introduced or materially expanded, confirm:

* Is there a clear business purpose?
* Is there a named owner?
* Is the role distinct?
* Are inputs and outputs defined?
* Are prohibited uses documented?
* Are information-handling requirements clear?
* Are knowledge sources approved?
* Are human review requirements defined?
* Are escalation conditions explicit?
* Has the GPT been tested?
* Is there a monitoring process?
* Is there a retirement path?

## Core Governance Principle

> A responsible AI system does not hide uncertainty, blur accountability, or bypass judgment. It makes each of those visible by design.

