Evaluation Framework

The CalmWave AI Workflow Suite was evaluated as a set of internal AI products rather than as a collection of prompts.

The purpose of evaluation was to determine whether each GPT could:

solve its intended business problem
produce reliable and useful outputs
remain within its defined role
make uncertainty visible
reduce work without introducing disproportionate risk
support responsible human decision-making

Evaluation focused on both individual GPT performance and the quality of the broader system.

Evaluation Objectives

The framework was designed to answer five core questions:

Is the output accurate?
Is it strategically useful?
Is it appropriate for the intended audience and channel?
Does it remain within its assigned scope?
Can a human review and act on it confidently?

An output was not considered successful merely because it was polished, detailed, or persuasive.

It needed to be grounded, relevant, actionable, and appropriately governed.

Evaluation Dimensions
1. Factual Accuracy

Measures whether the output correctly reflects the information available to the system.

Evaluation criteria

Does the response accurately represent user-provided information?
Are names, dates, numbers, claims, and relationships preserved correctly?
Does the system avoid inventing unsupported facts?
Are cited or supplied sources represented faithfully?
Are conflicting facts or sources identified?
Are factual gaps made visible?

Common failure modes

hallucinated data
fabricated sources
altered statistics
unsupported product or market claims
incorrect attribution
assumptions presented as facts
outdated information stated without qualification

Strong performance

A strong output distinguishes clearly between:

known facts
user-provided context
sourced findings
inferred information
assumptions
unknowns
2. Strategic Quality

Measures whether the system improves understanding, judgment, or decision-making.

Evaluation criteria

Does the output identify the actual business problem?
Does it distinguish symptoms from root causes?
Does it surface meaningful risks and tradeoffs?
Does it prioritize the most important issues?
Is the recommendation connected to evidence?
Does it explain why the recommendation matters?
Does it identify a clear next action?

Common failure modes

summarizing without interpreting
producing generic best practices
treating every finding as equally important
offering recommendations unsupported by evidence
avoiding difficult tradeoffs
producing activity instead of strategy
confusing output volume with insight

Strong performance

A strong strategic output should help the user understand:

what matters most
why it matters
what should be done
what could go wrong
what decision is required next
3. Relevance

Measures whether the output directly addresses the stated objective.

Evaluation criteria

Does the response answer the actual request?
Is the depth appropriate to the task?
Does it use the context supplied by the user?
Does it avoid unnecessary tangents?
Is the recommendation appropriate to the organization, audience, and constraints?
Does it reflect the correct stage of the workflow?

Common failure modes

answering an adjacent question
repeating context instead of advancing the work
providing generic guidance
ignoring stated constraints
overproducing material the user did not need
introducing irrelevant frameworks

Strong performance

A strong output is specific enough that it would not apply equally well to any organization, campaign, or user.

4. Role Fidelity

Measures whether each GPT behaves according to its assigned specialist function.

Evaluation criteria

Does the GPT stay within its defined role?
Does it use the expected professional lens?
Does it avoid duplicating another specialist unnecessarily?
Does it recognize when another GPT or human expert is better suited?
Does it preserve the distinction between strategy, governance, and execution?
Does it avoid claiming authority it does not have?

Examples

WaveForm should evaluate brand alignment rather than independently redefine the brand.
Charlie should develop copy without silently making major strategic decisions.
Simon should distinguish performance analysis from unsupported causal conclusions.
Juno should evaluate the relationship between UX, SEO, messaging, and conversion.
Amelie should challenge assumptions rather than simply agree with the user.
ABM Researcher should separate verified account intelligence from inference.

Common failure modes

specialist drift
excessive overlap between GPTs
every GPT becoming a copywriter
strategic systems producing unsupported execution
execution systems making unreviewed strategic decisions
failure to redirect appropriately
5. Brand Alignment

Measures whether outputs are consistent with approved brand voice, messaging, positioning, and language standards.

Evaluation criteria

Does the output reflect the intended brand voice?
Is the tone appropriate for the audience?
Does it use approved terminology consistently?
Does it avoid prohibited, inflated, or unsupported language?
Does it preserve key messaging distinctions?
Does it avoid generic AI phrasing?
Does it maintain consistency across channels?

Common failure modes

vague corporate language
exaggerated claims
tonal inconsistency
jargon-heavy writing
unapproved positioning language
flattening all communications into one tone
producing technically correct but off-brand copy

Strong performance

A strong output should feel recognizably aligned with the organization while remaining appropriate to the specific channel and audience.

6. Usability

Measures whether the output can be understood, reviewed, and used efficiently.

Evaluation criteria

Is the response easy to scan?
Is the hierarchy clear?
Are recommendations concrete?
Can the user identify the main takeaway quickly?
Is the output structured for the intended use?
Does it reduce editing and cleanup?
Can it be transferred into the next stage of work?

Common failure modes

excessive length
weak organization
buried recommendations
repetitive language
unclear next steps
outputs that require substantial rewriting
technically complete but operationally unusable responses

Strong performance

A strong output should reduce cognitive load, not create a second analysis task for the user.

7. Actionability

Measures whether the output supports a practical next step.

Evaluation criteria

Does the response recommend a clear action?
Is ownership implied or identified?
Are dependencies or prerequisites visible?
Are priorities ranked?
Are effort and potential impact considered?
Is the recommendation specific enough to execute?
Does the output indicate what should happen next?

Common failure modes

“improve messaging”
“increase engagement”
“optimize the website”
“consider testing”
long lists without prioritization
recommendations disconnected from operational reality

Strong performance

An actionable recommendation should clarify:

the action
the rationale
the priority
the expected effect
the next decision or handoff
8. Transparency and Uncertainty

Measures whether the system communicates the limits of its knowledge appropriately.

Evaluation criteria

Are assumptions labeled?
Are missing inputs identified?
Does the system qualify uncertain conclusions?
Does it distinguish correlation from causation?
Does it state when verification is required?
Are confidence levels proportionate to the available evidence?
Does it avoid false precision?

Common failure modes

confident unsupported conclusions
invented certainty
precise recommendations based on incomplete data
causal claims from correlation
hidden assumptions
failure to acknowledge source limitations

Strong performance

A strong system does not become vague merely because uncertainty exists. It provides the best available answer while making the limitations visible.

9. Governance Compliance

Measures whether the GPT follows the suite’s shared rules and safeguards.

Evaluation criteria

Does it avoid requesting or exposing unnecessary sensitive data?
Does it remain within its intended business scope?
Does it flag high-risk claims?
Does it require human review when appropriate?
Does it avoid presenting itself as a legal, clinical, regulatory, or compliance authority?
Does it follow established escalation rules?
Does it avoid reproducing confidential information unnecessarily?

Common failure modes

collecting excessive information
presenting high-risk outputs as final
failing to flag regulated or sensitive claims
exposing confidential information
skipping required human review
overstating authority
10. Consistency

Measures whether the GPT behaves reliably across repeated and comparable tasks.

Evaluation criteria

Do similar inputs receive similarly structured treatment?
Does the system follow its required output format?
Are quality standards maintained across multiple runs?
Does the GPT apply the same governance rules consistently?
Are recommendations stable when the material facts are unchanged?
Does the system respond predictably to incomplete information?

Common failure modes

major output variability
inconsistent scoring
changing standards between sessions
forgetting required sections
inconsistent treatment of uncertainty
unpredictable tone or depth

Strong performance

Consistency did not require identical wording. It required stable reasoning standards, output expectations, and governance behavior.

11. Efficiency

Measures whether the system reduces meaningful work.

Evaluation criteria

Does the GPT reduce research, drafting, analysis, or coordination time?
Does it reduce repetitive work?
Does it decrease the number of required revisions?
Does it improve handoffs?
Does it make expertise more accessible?
Does it shorten time from input to usable decision support?
Is the time saved greater than the time required to correct the output?

Common failure modes

generating more content than needed
creating substantial cleanup work
requiring repeated prompting
producing polished but unusable outputs
duplicating work already performed elsewhere
introducing errors that outweigh time savings
Evaluation Methods

The suite used multiple forms of evaluation because no single method captured overall quality.

Scenario Testing

Each GPT was tested against realistic business scenarios relevant to its assigned role.

Examples included:

complete and incomplete briefs
strong and weak source material
conflicting information
vague user requests
unrealistic deadlines
unsupported claims
high-stakes messaging
requests outside the GPT’s intended scope
requests containing insufficient evidence
cross-functional handoffs

Scenarios were designed to test both normal operation and likely failure conditions.

Golden-Set Testing

Representative prompts and expected output characteristics could be maintained as a reference set.

The purpose was not to require identical responses.

Instead, outputs were compared against expected standards such as:

required sections
correct interpretation
accurate use of facts
appropriate recommendation
visible assumptions
correct escalation
brand alignment

Golden sets were particularly useful after major instruction changes.

Edge-Case Testing

Edge cases were used to determine how the systems behaved under ambiguity or pressure.

Examples included:

missing context
contradictory instructions
requests for certainty where none existed
attempts to produce unsupported claims
requests involving confidential or sensitive information
unusually broad assignments
tasks spanning multiple specialist roles
requests outside the system’s expertise

A successful edge-case response often involved qualification, redirection, or a targeted request for additional information.

Comparative Testing

Outputs could be compared across:

different versions of the same GPT
specialist versus general-purpose responses
multiple prompt formulations
human-created versus AI-assisted drafts
pre- and post-governance revisions

Comparative testing helped reveal whether a change improved actual quality or merely changed style.

Human Review

Human judgment remained the primary standard for consequential outputs.

Reviewers assessed:

factual correctness
strategic value
appropriateness
brand fit
risk
usability
readiness for use

The reviewer should have sufficient subject-matter context to evaluate the specific output.

A fluent answer was never assumed to be a correct answer.

User Feedback

Practical user feedback helped identify issues that formal testing could miss.

Useful signals included:

repeated confusion
frequent rewrites
unclear output structure
poor handoffs
recurring requests the GPT could not handle
duplicate capability across specialists
points where users stopped trusting the output
cases where the system saved meaningful time

User satisfaction alone was not treated as proof of accuracy, but it was important evidence of usability and adoption.

Evaluation Scoring Model

Each output could be scored on a five-point scale.

Score	Standard
5	Excellent: accurate, insightful, actionable, appropriately governed, and ready for review or use
4	Strong: useful and mostly complete, with minor revisions required
3	Acceptable: directionally useful but requires meaningful review or refinement
2	Weak: substantial gaps, unsupported reasoning, or poor usability
1	Unacceptable: inaccurate, unsafe, irrelevant, or outside intended scope
Recommended Scoring Dimensions
factual accuracy
strategic quality
relevance
role fidelity
brand alignment
usability
actionability
transparency
governance compliance
consistency

Not every dimension needed equal weight for every GPT.

For example:

ABM Researcher required heavier weighting on source quality and factual accuracy.
WaveForm required heavier weighting on brand alignment.
Simon required heavier weighting on analytical integrity and interpretation.
Amelie required heavier weighting on strategic quality and challenge.
Charlie required heavier weighting on usability, clarity, and audience fit.
Gem required heavier weighting on organization, follow-through, and operational usefulness.
Example Weighted Scorecard
Dimension	Weight
Accuracy	20%
Strategic quality	15%
Relevance	10%
Role fidelity	10%
Brand alignment	10%
Usability	10%
Actionability	10%
Transparency	5%
Governance compliance	10%

Weights should be adjusted to reflect the purpose and risk profile of each specialist.

Pass Criteria

An output should not be considered ready merely because its average score is high.

Certain failures should trigger an automatic review or failure regardless of the total score.

Automatic Review Triggers
unsupported factual claims
material brand misalignment
confidential information exposure
regulatory, clinical, or legal overreach
fabricated sources or evidence
failure to disclose a material assumption
recommendation based on obviously insufficient data
output outside the GPT’s assigned role

This prevented strong performance in lower-risk categories from compensating for a critical failure.

Testing by Specialist
ABM Researcher

Priority evaluation areas

source quality
factual accuracy
distinction between evidence and inference
relevance to the target account
usefulness of the brief
quality of call analysis
identification of unknowns

Example test

Produce an account brief using limited public information and identify which conclusions require verification.

WaveForm

Priority evaluation areas

brand alignment
voice consistency
messaging accuracy
ability to identify off-brand language
preservation of channel appropriateness
avoidance of generic AI phrasing

Example test

Review three versions of the same message and identify which is most aligned with the brand, with specific reasons.

Amelie

Priority evaluation areas

strategic depth
quality of challenge
prioritization
identification of risks and tradeoffs
distinction between fact and recommendation
executive usefulness

Example test

Evaluate a proposed campaign strategy with incomplete information and identify the assumptions that could materially change the recommendation.

Gregor

Priority evaluation areas

alignment between business objective and creative direction
production feasibility
narrative clarity
quality of shot and edit recommendations
audience and platform fit
respect for constraints

Example test

Develop a video approach for a limited-budget campaign while explaining which creative choices are essential and which are optional.

Gem

Priority evaluation areas

operational clarity
task prioritization
completeness
dependency identification
follow-through
usefulness of timelines and documentation

Example test

Convert an unstructured set of meeting notes into prioritized actions, owners, dependencies, and open questions.

Juno

Priority evaluation areas

integration of UX, SEO, messaging, and conversion
quality of evidence
prioritization
feasibility
distinction between observed issues and hypotheses
quality of recommended tests

Example test

Audit a landing page and separate confirmed usability issues from hypotheses requiring analytics or user testing.

Simon

Priority evaluation areas

numerical accuracy
analytical integrity
distinction between observation and causation
trend interpretation
prioritization
executive clarity

Example test

Analyze a campaign performance summary and identify what can be concluded, what cannot, and what data is needed next.

Nelson

Priority evaluation areas

journey logic
segmentation
timing
messaging relevance
automation quality
deliverability awareness
conversion alignment

Example test

Design a nurture sequence for two audience segments and explain why the messaging and timing differ.

Fiona

Priority evaluation areas

platform awareness
community relevance
audience understanding
engagement quality
moderation judgment
channel-appropriate voice
long-term community value

Example test

Recommend a response strategy for a mixed social reaction that includes legitimate criticism, misinformation, and neutral questions.

Charlie

Priority evaluation areas

clarity
persuasion
audience fit
message hierarchy
accuracy
usability
brand compatibility
preservation of meaning during edits

Example test

Rewrite a technically accurate but unclear product explanation without adding claims or changing the underlying meaning.

System-Level Evaluation

Individual GPT quality was only part of the evaluation.

The suite also needed to function as a coherent system.

System-Level Criteria
Are specialist boundaries clear?
Can users identify which GPT to use?
Are handoffs efficient?
Are shared standards applied consistently?
Is capability duplicated unnecessarily?
Do specialists produce compatible outputs?
Does the system reduce fragmented work?
Are governance expectations consistent across the suite?
Cross-GPT Test

A single campaign scenario could be passed through several specialists:

ABM Researcher develops the account brief.
Amelie defines the strategic approach.
WaveForm evaluates messaging alignment.
Charlie drafts the copy.
Nelson or Fiona adapts it for the channel.
Simon evaluates performance.
Gem organizes follow-up actions.

The final evaluation should consider whether context, decisions, constraints, and evidence survive the handoffs.

Evaluation Cadence

Evaluation should occur at several points in the product lifecycle.

Before Launch
validate role clarity
test core scenarios
test known risks
confirm output structure
confirm governance behavior
After Launch
review early user feedback
identify confusion or misuse
monitor weak outputs
refine instructions and examples
identify missing workflows
After Material Changes
rerun golden-set tests
compare against the previous version
check for regressions
retest specialist boundaries
retest governance requirements
Periodically
review whether the GPT still solves a meaningful problem
assess overlap with other specialists
update outdated knowledge or standards
review recurring failure patterns
determine whether the system should be revised, consolidated, or retired
Failure Review

Failures were treated as product-design signals rather than isolated bad responses.

A useful failure review should document:

the prompt
the output
the expected behavior
the observed failure
the likely cause
the risk created
the corrective change
whether regression testing is required

Potential corrective actions included:

revising role definition
changing required inputs
tightening output structure
adding examples
introducing an escalation rule
clarifying a shared governance standard
redirecting the task to another specialist
retiring a low-value capability
Success Criteria

A GPT was successful when it consistently:

improved the quality of the work
reduced meaningful effort
stayed within its role
made uncertainty visible
supported responsible decisions
produced outputs that were easier to review and use
earned trust through reliability rather than confidence alone
Core Principle

AI quality should be evaluated by the reliability of the decision support it provides—not by how polished or human the output appears.
