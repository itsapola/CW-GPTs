Enterprise GPT Suite — AI Workflow Architecture for Healthcare Marketing

CalmWave AI Workflow Suite

A governed ecosystem of specialized GPTs designed to support marketing strategy, execution, analysis, and operations across a healthcare technology organization.

Status: Retired
This portfolio case study documents the system architecture, governance model, and functional design of an internal GPT suite created during my tenure at CalmWave. Proprietary prompts, company knowledge files, internal data, and confidential outputs are not included.

Documentation

- [System overview](system-overview.md)
- [Architecture diagram](architecture-diagram.md)
- [Workflow map](workflow-map.md)
- [Design principles](design-principles.md)
- [Governance framework](governance.md)
- [Evaluation framework](evaluation-framework.md)
- [Synthetic example](examples/synthetic-example.md)

Overview

The CalmWave AI Workflow Suite was designed to move beyond a single general-purpose chatbot.

Instead, the system distributed distinct responsibilities across a network of specialized GPTs, each with a defined role, scope, operating logic, and review expectation.

The goal was not to automate judgment.

The goal was to create a practical AI operating layer that could:

reduce repetitive knowledge work
improve consistency across marketing outputs
accelerate research and execution
preserve brand and messaging standards
make analytical workflows more accessible
clarify where human judgment remained necessary

The suite ultimately expanded to ten specialized GPTs spanning strategy, research, brand, content, analytics, growth, operations, and executive support.

At a Glance

- 10 specialized GPTs
- 4 functional layers
- Human-in-the-loop governance
- Role-specific evaluation criteria
- Cross-agent workflow architecture
- Retired internal system documented as a portfolio case study

The System

ABM Researcher

Function: Account-based marketing research and sales intelligence

Designed to support:

account and stakeholder research
ABM brief development
call and transcript analysis
opportunity synthesis
market and company research
strategic preparation for outreach and meetings

The system helped transform fragmented account information into structured, actionable briefs while separating sourced findings from assumptions.

WaveForm

Function: Brand voice and messaging governance

Designed to support:

brand voice consistency
messaging development
copy review
tone adaptation
positioning alignment
language governance across channels

WaveForm acted as a brand steward rather than a generic writing assistant. Its role was to identify off-brand language, reinforce approved messaging principles, and improve consistency without flattening every output into the same voice.

Amelie

Function: Executive strategist and advisor

Designed to support:

strategic thinking
executive decision support
narrative development
prioritization
leadership communications
preparation for high-stakes discussions

Amelie was structured to challenge assumptions, identify gaps, and distinguish between facts, interpretations, risks, and recommendations.

Gregor

Function: Filmography, video strategy, and editing support

Designed to support:

video concept development
shot planning
interview structure
script and storyboard review
edit recommendations
production planning
visual narrative development

Gregor translated marketing goals into practical video direction while accounting for production constraints, audience, channel, and intended action.

Gem

Function: Marketing operations and personal assistance

Designed to support:

task organization
workflow coordination
project planning
documentation
meeting follow-up
operational prioritization
recurring marketing administration

Gem functioned as a marketing operations layer, helping convert scattered requests and responsibilities into clearer systems, actions, and timelines.

Juno

Function: Website strategy, SEO, UX, and conversion optimization

Designed to support:

website audits
SEO recommendations
user experience analysis
information architecture
conversion-rate optimization
landing-page review
content hierarchy
digital journey analysis

Juno evaluated websites as integrated business systems rather than treating SEO, UX, messaging, and conversion as separate disciplines.

Simon

Function: Marketing analytics and performance interpretation

Designed to support:

campaign analysis
metric interpretation
performance summaries
trend identification
reporting
measurement planning
executive-ready insights

Simon was designed to move beyond reporting numbers and toward explaining what changed, why it mattered, and what action should follow.

Nelson

Function: Email strategy, campaigns, and automation

Designed to support:

email campaign planning
lifecycle communications
nurture sequences
segmentation
subject-line and copy development
automation logic
campaign optimization

Nelson connected messaging, customer journey, timing, segmentation, and conversion goals rather than treating email as an isolated production channel.

Fiona

Function: Social media strategy and community building

Designed to support:

channel strategy
content planning
community engagement
social copy
campaign concepts
audience development
response and moderation guidance

Fiona emphasized audience behavior, relationship-building, and platform context rather than simply generating posts.

Charlie

Function: Copywriting and content development

Designed to support:

campaign copy
website copy
social and email content
long-form content
editing
message refinement
tone and format adaptation

Charlie served as the primary writing specialist within the suite, while WaveForm remained responsible for brand governance and consistency.

Why a Multi-Agent Model

A single general-purpose GPT creates several governance problems:

responsibilities become unclear
output standards vary by request
users do not always know which context to provide
brand, strategy, research, and execution become blended together
review requirements are easy to overlook
one system can appear more authoritative than it should

The multi-agent model created clearer boundaries.

Each GPT had:

a defined business role
an explicit scope
expected inputs
structured output patterns
known limitations
review requirements
escalation points for human judgment

This made the system easier to use, evaluate, govern, and improve.

Governance Principles

1. Human Judgment Remained Accountable

The GPTs were designed to assist decision-making, not replace ownership.

Users remained responsible for:

validating facts
approving public-facing language
reviewing strategic recommendations
confirming claims
assessing reputational and regulatory risk
making final business decisions

2. Facts, Assumptions, and Recommendations Were Separated

Where appropriate, outputs distinguished between:

verified information
user-provided information
inferred context
assumptions
recommendations
unresolved questions

This reduced the risk of plausible-sounding interpretation being mistaken for fact.

3. Sensitive Information Was Minimized

The suite was not intended to process protected health information, confidential customer information, credentials, or unnecessary personal data.

Users were expected to avoid entering information that was not required for the task.

4. Source Quality Mattered

Research-focused workflows emphasized:

source identification
evidence quality
recency
conflicts between sources
confidence levels
gaps in available information

Outputs were stronger when they showed their basis instead of presenting unsupported certainty.

5. Brand Governance Was Centralized

WaveForm acted as the primary brand-governance layer.

This helped prevent every GPT from independently interpreting brand voice and creating inconsistent standards across the system.

6. Specialized Systems Had Defined Boundaries

The GPTs were intentionally differentiated.

For example:

Charlie could draft copy
WaveForm could assess brand alignment
Amelie could challenge the strategic rationale
Simon could evaluate performance
Juno could assess the digital experience

This reduced role confusion and encouraged more deliberate workflows.

7. Outputs Were Drafts, Not Authority

All generated materials were treated as working outputs requiring review.

The systems were not positioned as legal, clinical, regulatory, financial, or compliance authorities.

8. Governance Was Part of Product Design

Guardrails were not added after the fact.

They shaped:

system roles
instructions
output formats
review workflows
user expectations
escalation logic
testing criteria
Example Cross-GPT Workflow

A campaign might move through the suite as follows:

ABM Researcher
Account and audience intelligence
        ↓
Amelie
Strategic framing and prioritization
        ↓
WaveForm
Messaging and brand alignment
        ↓
Charlie
Copy development
        ↓
Nelson / Fiona / Juno / Gregor
Channel-specific execution
        ↓
Simon
Performance interpretation
        ↓
Gem
Follow-up, documentation, and operational coordination

The value of the suite came not only from each individual GPT, but from the way responsibilities could be sequenced across a broader operating system.

Evaluation Framework

The GPTs were evaluated across several dimensions.

Accuracy
Did the output reflect the information provided?
Were unsupported claims introduced?
Were assumptions clearly marked?
Were source limitations visible?
Strategic Quality
Did the output identify the real decision or business problem?
Did it surface risks and tradeoffs?
Did it prioritize rather than merely summarize?
Did it provide a useful next action?
Brand Alignment
Did the output match approved messaging principles?
Did it avoid generic or inflated language?
Was tone appropriate for the audience and channel?
Did the system preserve distinction between brand voice and personal preference?
Usability
Could a non-expert understand the output?
Was the structure easy to scan?
Were recommendations actionable?
Did the output reduce work rather than create more cleanup?
Governance
Were facts and assumptions separated?
Was human review clearly required where appropriate?
Did the system stay within its intended scope?
Did it avoid presenting uncertain material with false confidence?
Consistency
Did similar inputs receive comparable treatment?
Did the system follow its required output structure?
Did it preserve quality across repeated use?
Did the specialist remain within its assigned role?
Design Lessons
Specialization improves clarity, but only when boundaries are real

Giving GPTs different names is not enough.

Each system needs a distinct purpose, workflow, and quality standard. Otherwise, the suite becomes a collection of interchangeable writing bots.

Governance must be visible to the user

Internal instructions alone are insufficient.

Users need clear signals about:

what the system knows
what it is assuming
what requires verification
what the system should not decide
when human review is mandatory
The interface shapes behavior

Output templates, required questions, confidence labels, and review prompts can influence responsible use more effectively than a disclaimer buried in documentation.

Brand governance should not be distributed casually

Allowing every system to interpret the brand independently increases inconsistency. Centralizing brand logic created a clearer standard across workflows.

The best AI workflows reduce ambiguity

The highest-value systems did not simply generate more content. They helped users:

frame the problem
organize evidence
identify missing information
compare options
clarify tradeoffs
determine the next decision
Portfolio Scope

This repository intentionally excludes:

proprietary system prompts
confidential company information
internal knowledge files
customer or patient information
protected health information
internal performance data
private conversations
live GPT configurations
credentials or API keys

Examples included in this portfolio should use synthetic, anonymized, or publicly available information.

My Role

I designed the suite as a functional AI operating system for marketing.

My work included:

identifying suitable business use cases
defining specialist roles
structuring system responsibilities
designing workflows
establishing governance principles
setting output expectations
testing quality and usability
refining boundaries between systems
connecting strategic and executional use cases
driving practical adoption within marketing workflows

Outcome

The project demonstrated how a marketing organization could use generative AI as a governed system of specialized capabilities rather than as an unstructured collection of prompts.

The core design principle was simple:

The more consequential the output, the more visible the reasoning, evidence, limitations, and human review should become.

Repository Purpose

This repository is a high-level portfolio case study intended to demonstrate:

AI product thinking
marketing systems design
workflow architecture
responsible AI governance
cross-functional marketing strategy
operationalization of generative AI
human-in-the-loop design

It is not a reproduction or public release of CalmWave’s internal systems.
