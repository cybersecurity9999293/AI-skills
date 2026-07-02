# OMNIPROMPT ARCHITECT — SKILL.md
### Ultra High-Level Universal Prompt Engineering Intelligence System
**Version:** 1.0 | **Tier:** Master Architect | **Domain:** Universal

---

## OVERVIEW

This skill transforms any AI model into a precision prompt engineering system capable of operating across every domain of human knowledge and AI capability. It integrates advanced prompt engineering, cognitive science, neuroscience, behavioral psychology, sociology, linguistics, AI/ML engineering, and token-level optimization into one unified framework.

This skill is ethical by design. It maximizes AI output quality through legitimate intelligence amplification — not manipulation, exploitation, or harmful deception.

---

## MODULE 1: PROMPT ARCHITECTURE FUNDAMENTALS

### 1.1 The 8-Layer Prompt Stack

Every high-performance prompt is built from these layers in order:

```
Layer 1: IDENTITY     → Who is the AI in this context?
Layer 2: CONTEXT      → What world does it operate in?
Layer 3: CAPABILITIES → What can it do here?
Layer 4: GOAL         → What is the ultimate outcome?
Layer 5: TASK         → What are the specific instructions?
Layer 6: CONSTRAINTS  → What are the limits and rules?
Layer 7: OUTPUT       → What format should the response take?
Layer 8: TONE/STYLE   → How should it communicate?
```

**Rule:** Never skip layers. Gaps create ambiguity. Ambiguity creates low-quality output.

### 1.2 Instruction Hierarchy

AI models process instructions in a priority hierarchy. Structure your prompts accordingly:

```
Priority 1 (Highest): System Prompt / Role Definition
Priority 2: Explicit Task Instructions
Priority 3: Contextual Constraints
Priority 4: Format Specifications
Priority 5: Style and Tone Guidance
Priority 6 (Lowest): Implicit Expectations
```

**Engineering Rule:** Higher-priority instructions override lower ones. Never put critical instructions at low-priority positions. Lead with what matters most.

### 1.3 Prompt Types and When to Use Them

| Prompt Type | Best Use Case | Key Feature |
|---|---|---|
| Zero-shot | Simple, clear tasks | No examples needed |
| Few-shot | Pattern-requiring tasks | 2–5 examples guide output |
| Chain-of-Thought | Complex reasoning | "Think step by step" |
| Tree-of-Thought | Multi-path problems | Explore branches before deciding |
| ReAct | Tool-using agents | Reason + Act loops |
| Self-Consistency | High-stakes answers | Multiple reasoning paths, majority vote |
| Role-Based | Domain expertise | AI embodies specialist identity |
| Decomposition | Complex projects | Break into sub-tasks |
| Meta-Prompting | Prompt generation | AI writes its own instructions |
| Recursive | Iterative refinement | Output feeds back as input |

---

## MODULE 2: COGNITIVE SCIENCE APPLIED TO PROMPTING

### 2.1 Human Cognition Principles That Govern AI Interaction

Understanding how humans think allows you to design prompts that align with human cognitive patterns — both in how you write prompts and how the AI's outputs will be received.

**Dual Process Theory (Kahneman):**
- System 1 (fast/intuitive) — Useful for creative generation prompts
- System 2 (slow/deliberate) — Required for analytical, reasoning, and strategic prompts
- **Application:** Add "reason carefully before responding" or "think step by step" to activate System 2-equivalent processing in the model

**Cognitive Load Theory:**
- Human working memory holds ~7 items at once (Miller's Law)
- **Application:** Break complex prompts into numbered steps. Never exceed 7 major instructions in a single prompt block. Use headers to chunk information.

**Schema Theory:**
- The brain organizes knowledge into mental frameworks
- **Application:** Provide a schema at the start of your prompt ("Think of this as a product launch strategy framework"). This primes the model's contextual focus.

**Anchoring Effect:**
- First information received disproportionately shapes interpretation
- **Application:** Open every prompt with the most important framing. The model weights early context heavily.

**Priming:**
- Exposure to one concept activates related concepts
- **Application:** Use domain-specific vocabulary early in a prompt to activate relevant knowledge clusters in the model.

**Attention and Salience:**
- Humans (and models) prioritize novel, specific, and emphasized information
- **Application:** Use formatting — bold, caps, numbered lists — to signal what matters most. Specific beats vague every time.

### 2.2 Behavioral Psychology for Output Design

**Operant Conditioning Framing:**
Define what "good output" looks like explicitly. Models improve output when the definition of success is crystal clear.

```
Instead of: "Write a good email."
Use: "Write a professional email that opens with a specific value proposition, addresses a pain point in paragraph 2, and closes with a single clear call to action. The email should be under 150 words."
```

**Goal-Gradient Effect:**
People (and models) perform better when the end goal is clearly visible and close.
- **Application:** State the final deliverable at the START of the prompt, not the end.

**Expectancy Theory:**
Performance is tied to expectation of success and clarity of reward.
- **Application:** Tell the model what success looks like: "A perfect response will include X, Y, and Z."

**Contrast Principle:**
Things are evaluated relative to what came before.
- **Application:** Provide a negative example before a positive one: "Not like this... but like this..."

---

## MODULE 3: NEUROSCIENCE APPLIED TO AI COMMUNICATION

### 3.1 How the Brain Processes Language

**Broca's Area (Language Production) analog in LLMs:**
Language models process syntax and grammar structurally. Poorly structured prompts create poorly structured outputs.
- **Rule:** Write prompts with clean grammar, clear syntax, and logical sentence flow.

**Wernicke's Area (Language Comprehension) analog:**
The semantic relationships between words matter deeply.
- **Rule:** Use precise, unambiguous vocabulary. Technical terms > colloquial synonyms for professional tasks.

**Neuroplasticity and Context Windows:**
The brain adapts to context. So does the model. The context window IS the model's working "brain state" for that conversation.
- **Rule:** Keep the most relevant information within the first and last 20% of a long prompt. Middle sections receive less attention weight.

**Pattern Completion (Predictive Brain):**
The brain predicts what comes next based on patterns. LLMs are literally next-token predictors.
- **Application:** Structure your prompts to set up the pattern you want completed. If you want structured output, show a structured setup.

### 3.2 The Neuroscience of Motivation (Applied to Agent Prompting)

**Dopaminergic Reward Loops:**
Motivation is driven by anticipated reward.
- **Application for AI agents:** Define milestones and checkpoints in multi-step tasks. "Complete step 1, then confirm before proceeding." This keeps agent tasks grounded and reviewable.

**Prefrontal Cortex Function (Executive Control):**
Planning, reasoning, and inhibition are prefrontal functions.
- **Application:** "Analytical reasoning" prompts should explicitly invoke executive function language: "Evaluate pros and cons," "Consider second-order consequences," "Identify logical fallacies."

---

## MODULE 4: SOCIOLOGY AND SOCIAL SCIENCE FOR AUDIENCE-AWARE PROMPTS

### 4.1 Social Context Engineering

**Social Identity Theory (Tajfel & Turner):**
People define themselves through group membership.
- **Application:** When designing prompts for audience-facing content, specify the audience's identity group: "Write for a 35-year-old first-generation entrepreneur who values practicality over theory."

**Framing Theory (Goffman):**
How information is framed determines how it is interpreted and acted upon.
- **Application:** Frame prompts around the perspective you want the AI to adopt. "From the perspective of a risk-averse investor..." produces very different output than "From the perspective of a growth-focused founder..."

**Cultural Dimensions (Hofstede):**
Culture shapes communication preferences across dimensions: individualism/collectivism, power distance, uncertainty avoidance, long-term orientation.
- **Application:** Specify cultural context for localized content: "Write this for a high-context, collectivist audience in East Asia" vs. "Write this for a low-context, individualist Western audience."

**Status and Hierarchy:**
Communication style shifts radically based on power dynamics.
- **Application:** Specify the relational context: "Write as a trusted peer advisor," "Write as an expert briefing a non-expert," "Write as a junior analyst presenting to senior leadership."

### 4.2 Communication Science Principles

**Plain Language Principle:**
Simpler language increases comprehension and trust for general audiences.

**The Elaboration Likelihood Model (Petty & Cacioppo):**
Audiences process persuasive information through two routes:
- Central route: logic, evidence, reasoning (high-involvement)
- Peripheral route: credibility, aesthetics, emotional cues (low-involvement)
- **Application:** Match your content's persuasive route to your audience's engagement level.

**Narrative Transportation Theory:**
Stories engage audiences more deeply than factual summaries.
- **Application:** For persuasive or educational content, instruct the model to embed core ideas in narrative structures.

---

## MODULE 5: AI AND MACHINE LEARNING ENGINEERING

### 5.1 Token-Level Optimization

**What is a token?**
A token is roughly 0.75 words in English. Models process and generate by the token. Token efficiency = cost efficiency and context efficiency.

**Token Economy Rules:**
- Remove filler phrases: "Please," "Could you," "I want you to" — these cost tokens and add no instruction value in system prompts
- Use structured formats (JSON, markdown, numbered lists) — they encode more information per token
- Compress repeated context — summarize previous turns rather than restating verbatim
- Front-load critical instructions — early tokens receive higher attention weight

**Context Window Management:**
```
Rule 1: Most important instructions → First 10% and last 10% of prompt
Rule 2: Background context → Middle of prompt
Rule 3: Never exceed 80% of context window with static content — leave room for reasoning
Rule 4: For long tasks, use rolling summaries rather than full history
```

**Token Limit Planning:**
| Task Type | Recommended Max Tokens (Output) |
|---|---|
| Short answer / classification | 100–300 |
| Summary | 300–600 |
| Analysis / report | 800–2000 |
| Long-form content | 2000–4000 |
| Complex reasoning chain | 1000–3000 |

### 5.2 Hallucination Prevention

Hallucinations occur when a model generates plausible-sounding but factually incorrect information. They are caused by:
- Training data gaps
- Ambiguous prompts
- Overconfident generation
- Context window overload
- Lack of grounding

**Hallucination Reduction Techniques:**

**1. Grounding Instructions**
```
"Base your response only on the information provided in this document. 
If the answer is not found in the provided text, say 'I don't have 
enough information to answer this.'"
```

**2. Uncertainty Acknowledgment Prompting**
```
"If you are not certain about a fact, clearly state your uncertainty 
level. Use: 'I believe...', 'This may be...', or 'I'm not certain but...'"
```

**3. Source-Citing Prompts**
```
"For every factual claim, indicate whether it comes from: 
(a) the provided context, (b) general training knowledge, 
or (c) logical inference."
```

**4. Verification Chains**
```
"After generating your response, review it once and flag any 
statements you are less than 90% confident are accurate."
```

**5. Constraint Narrowing**
```
"Answer only within this specific domain: [domain]. 
Do not extrapolate beyond the scope of the question."
```

**6. Anti-Confabulation Instructions**
```
"Do not invent names, dates, statistics, citations, or 
URLs that were not provided to you. If specific data 
is needed and unavailable, state that it is unavailable."
```

### 5.3 Temperature and Sampling (Conceptual Guidance)

When building prompts for configurable AI systems:

| Temperature | Effect | Best For |
|---|---|---|
| 0.0–0.2 | Deterministic, focused | Facts, code, classification |
| 0.3–0.5 | Balanced | Analysis, summaries, business writing |
| 0.6–0.8 | Creative, varied | Marketing, storytelling, ideation |
| 0.9–1.0+ | Highly random | Brainstorming, experimental creative |

**Prompt-side temperature control (for fixed-temperature systems):**
- Lower creativity: "Be precise and stick to established facts. Avoid speculation."
- Higher creativity: "Think imaginatively. Generate unexpected and original ideas. Push beyond conventional answers."

### 5.4 RLHF and Instruction Following

Models fine-tuned with Reinforcement Learning from Human Feedback (RLHF) respond best to:
- **Clear, direct instructions** — not hints or implications
- **Positive framing** — "Do X" outperforms "Don't do not-X"
- **Explicit success criteria** — Models trained on human preference respond to defined quality bars
- **Structured formatting requests** — Models learn formatting preferences during fine-tuning

### 5.5 Attention Mechanisms (Applied)

The Transformer's self-attention mechanism weighs relationships between all tokens in context.

**Practical implications:**
- **Recency bias** — The last few instructions before the user turn carry high weight
- **Repetition reinforcement** — Stating a key constraint twice (beginning + end) increases adherence
- **Specificity attraction** — Specific, concrete terms attract more attention weight than abstract ones
- **Formatting as attention signal** — Headers, bullets, and caps signal high-importance regions

---

## MODULE 6: ADVANCED PROMPT ENGINEERING TECHNIQUES

### 6.1 Chain-of-Thought (CoT) Prompting

Force deliberate reasoning by making the reasoning process explicit.

**Basic CoT:**
```
"Think through this step by step before giving your final answer."
```

**Structured CoT:**
```
"Before answering, work through the following:
Step 1: Identify all relevant variables
Step 2: List assumptions being made  
Step 3: Consider at least 2 alternative interpretations
Step 4: Reason to your conclusion
Step 5: State your final answer"
```

**Zero-Shot CoT:**
Simply append: *"Let's think step by step."*
This single phrase measurably improves reasoning accuracy on complex tasks.

### 6.2 Tree-of-Thought (ToT) Prompting

For problems requiring exploration of multiple solution paths:

```
"Approach this problem like a decision tree:
Branch A: Consider approach [X]
Branch B: Consider approach [Y]  
Branch C: Consider approach [Z]

Evaluate each branch for: feasibility, risks, and outcome quality.
Then synthesize the best elements into a final recommendation."
```

### 6.3 Self-Consistency Prompting

For high-stakes answers, generate multiple reasoning paths and take the consensus:

```
"Generate 3 independent analyses of this problem, each starting from 
a different angle. Then identify where all 3 analyses agree. 
Your final answer should be grounded in those points of consensus."
```

### 6.4 Role-Based Prompting (Expert Persona Engineering)

The most powerful single-technique in prompt engineering. Expert personas activate domain-specific knowledge clusters.

**Expert Persona Template:**
```
You are [TITLE] with [X] years of experience in [DOMAIN].
You specialize in [SPECIFIC NICHE].
You have worked with [RELEVANT CONTEXT: companies, cases, scenarios].
You think in terms of [KEY FRAMEWORKS/MODELS].
When you analyze problems, you always consider [KEY DIMENSIONS].
Your communication style is [STYLE DESCRIPTOR].
```

**Persona Stack Technique:**
Combine multiple expert lenses:
```
"Analyze this business problem from three simultaneous perspectives:
1. As a seasoned CFO focused on financial risk
2. As a growth-stage CMO focused on market opportunity  
3. As an operations executive focused on execution feasibility

Then synthesize all three views into a unified strategic recommendation."
```

### 6.5 Task Decomposition Prompting

Break complex tasks into atomic sub-tasks. Prevents scope creep and improves output quality.

**Decomposition Template:**
```
"We will complete this task in [N] phases. Do not proceed to the 
next phase until I confirm the current phase is complete.

Phase 1: [DELIVERABLE 1]
Phase 2: [DELIVERABLE 2]
Phase 3: [DELIVERABLE 3]

Begin with Phase 1 only."
```

### 6.6 Structured Output Prompting

Force specific output formats for downstream processing:

**JSON Output:**
```
"Return your response ONLY as valid JSON in this exact schema:
{
  "summary": "string",
  "key_points": ["string"],
  "confidence_score": 0.0-1.0,
  "recommended_action": "string"
}
Do not include any text outside the JSON object."
```

**Table Output:**
```
"Format your response as a markdown table with columns: 
| Option | Pros | Cons | Recommended For |"
```

### 6.7 Stop Conditions and Guardrails

Define when and how the AI should stop, pause, or escalate:

```
STOP CONDITIONS:
- Stop if the task requires information not provided in context
- Stop if completing the task would require making assumptions about [X]
- Stop after producing [N] items and ask for confirmation to continue
- Stop and flag if the task involves [SENSITIVE DOMAIN]

ESCALATION RULES:
- If uncertain about scope, ask one clarifying question before proceeding
- If multiple valid interpretations exist, list them and ask which to pursue
```

### 6.8 Memory and State Management in Multi-Turn Prompts

Models have no persistent memory. Manage state explicitly:

**State Injection Template:**
```
"CURRENT SESSION STATE:
- Task: [what we are building]
- Progress: [what has been completed]
- Decisions Made: [key choices locked in]
- Next Step: [what we are doing now]
- Constraints Active: [rules in effect]

Continue from this state."
```

**Rolling Summary Technique:**
At each major checkpoint, compress conversation history:
```
"Summarize everything decided and built so far in under 200 words. 
I will use this summary to start the next session."
```

---

## MODULE 7: PROMPT OPTIMIZATION AND TUNING

### 7.1 The CLEAR Framework for Prompt Quality

Before deploying any prompt, evaluate it against CLEAR:

- **C — Concise:** Is every word earning its place? Remove fluff.
- **L — Logical:** Does the instruction flow in the order the AI will need it?
- **E — Explicit:** Are all expectations stated directly? Nothing left implied?
- **A — Actionable:** Does the AI know exactly what to DO?
- **R — Restrictive (appropriately):** Are constraints defined to prevent scope drift?

### 7.2 Common Prompt Failures and Fixes

| Failure Mode | Symptom | Fix |
|---|---|---|
| Vague objective | Generic, shallow output | Add specific success criteria |
| Missing role | Off-tone, wrong expertise | Add expert persona definition |
| No format spec | Inconsistent structure | Define exact output format |
| Overloaded prompt | Model ignores some instructions | Decompose into phases |
| Missing constraints | Model goes out of scope | Add explicit stop conditions |
| Ambiguous pronouns | Model loses referent | Use specific nouns throughout |
| No reasoning trigger | Surface-level answers | Add CoT instruction |
| Hallucination risk | False facts injected | Add grounding + uncertainty rules |

### 7.3 A/B Testing Prompts

Treat prompts like hypotheses. Test systematically:

```
Prompt Version A: [Original]
Prompt Version B: [Modified — change ONE variable]

Evaluate on:
- Output accuracy
- Output completeness
- Format compliance
- Reasoning quality
- Consistency across 5 runs
```

**One Variable Rule:** Only change one element per test. Otherwise you cannot attribute performance differences.

### 7.4 Prompt Compression Technique

When context windows are limited, compress without losing instruction fidelity:

```
BEFORE: "Please make sure that when you write the report you include 
a section at the beginning that summarizes the main points and then 
after that you should have the detailed analysis..."

AFTER: "Structure: 1) Executive Summary 2) Detailed Analysis 3) 
Recommendations 4) Appendix. Use professional business writing."
```

---

## MODULE 8: AI WORKFLOW AND AUTOMATION DESIGN

### 8.1 Prompt Chain Architecture

Design multi-step AI workflows where output from one prompt becomes input to the next:

```
CHAIN DESIGN:
Step 1 Prompt → [Output A] → 
Step 2 Prompt (uses Output A) → [Output B] → 
Step 3 Prompt (uses Output B) → [Final Deliverable]

Each step should:
- Have a single, clear purpose
- Produce a defined, usable output
- Include validation criteria before passing to next step
```

### 8.2 Agent Loop Design

For autonomous AI agents operating in a Reason → Act → Observe cycle:

```
AGENT LOOP TEMPLATE:

IDENTITY: You are an autonomous [TYPE] agent.

TOOLS AVAILABLE: [List tools/capabilities]

OPERATING LOOP:
1. REASON: Analyze the current state and goal
2. PLAN: Identify the next single action to take
3. ACT: Execute that action
4. OBSERVE: Evaluate the result
5. REPEAT until goal achieved or stop condition met

STOP CONDITIONS:
- Goal achieved
- [N] iterations completed without progress
- Uncertainty threshold exceeded — escalate to human

NEVER: Take irreversible actions without confirmation.
ALWAYS: Log reasoning at each step.
```

### 8.3 Human-in-the-Loop Checkpoints

For high-stakes automated workflows, define mandatory human review points:

```
CHECKPOINT PROTOCOL:
- After Phase 1 completion: PAUSE and present output for human review
- Before any action that [modifies/deletes/publishes]: PAUSE and confirm
- If confidence score < [threshold]: PAUSE and flag for human decision
- After [N] autonomous steps: PAUSE and provide progress summary
```

---

## MODULE 9: DOMAIN PROMPT TEMPLATES

### 9.1 Business Strategy Prompt Template
```
You are a senior strategy consultant with 20+ years advising 
Fortune 500 companies and high-growth startups. You apply 
frameworks including Porter's Five Forces, Blue Ocean Strategy, 
Jobs-to-be-Done, and First Principles Reasoning.

TASK: [Insert strategic question]

ANALYSIS FRAMEWORK:
1. Current state assessment
2. Key constraints and leverage points
3. Strategic options (minimum 3)
4. Risk/reward evaluation per option
5. Recommended path with rationale
6. First 90-day action plan

OUTPUT: Executive-level strategic brief. 
Concise, direct, actionable. No filler.
```

### 9.2 Software Engineering Prompt Template
```
You are a senior software engineer with deep expertise in 
[LANGUAGE/STACK]. You write clean, well-documented, 
production-ready code. You think about edge cases, 
performance, and maintainability.

TASK: [Insert coding task]

REQUIREMENTS:
- Language: [specify]
- Performance constraints: [specify]
- Code style: [specify or link to style guide]
- Error handling: Comprehensive, with meaningful messages
- Comments: Explain WHY not just WHAT for complex logic

OUTPUT FORMAT:
1. Brief approach explanation (2–3 sentences)
2. Complete code with inline comments
3. Usage example
4. Known limitations or edge cases
```

### 9.3 Educational Content Prompt Template
```
You are an expert educator with deep knowledge of [SUBJECT] 
and expertise in learning science, curriculum design, and 
cognitive scaffolding. You make complex concepts genuinely 
accessible without sacrificing accuracy.

AUDIENCE: [Specify learner level and background]
TOPIC: [Specify topic]
LEARNING OBJECTIVE: After reading this, the learner will be 
able to [specific outcome].

CONTENT STRUCTURE:
1. Hook — why this matters to the learner
2. Core concept — clearest possible explanation
3. Concrete analogy from everyday life
4. Step-by-step breakdown
5. Common misconceptions corrected
6. Practice question with answer

TONE: Encouraging, clear, intellectually honest.
```

### 9.4 Research and Analysis Prompt Template
```
You are a rigorous analytical researcher trained in evidence 
evaluation, logical reasoning, and structured argumentation.

RESEARCH QUESTION: [Insert question]

ANALYTICAL PROTOCOL:
1. Define key terms precisely
2. Identify what IS and IS NOT known
3. Evaluate evidence quality (strong/moderate/weak)
4. Present strongest case FOR and AGAINST
5. Identify key uncertainties and knowledge gaps
6. State conclusion with confidence level

INTELLECTUAL STANDARDS:
- Distinguish fact from inference from speculation
- Flag where expert consensus exists vs. is contested
- Acknowledge limits of available information
- Never overstate confidence
```

---

## MODULE 10: QUALITY ASSURANCE CHECKLIST

Before finalizing any prompt, verify:

**Structure:**
- [ ] Role/identity defined
- [ ] Context established
- [ ] Goal stated at the top
- [ ] Task instructions numbered and sequential
- [ ] Output format specified
- [ ] Tone and style defined
- [ ] Stop conditions included (for complex tasks)

**Cognitive Design:**
- [ ] Anchoring applied (most important info first)
- [ ] Cognitive load managed (≤7 major instructions)
- [ ] Reasoning trigger included if needed (CoT)
- [ ] Success criteria explicitly defined

**Token Engineering:**
- [ ] No filler phrases
- [ ] Structured formatting used
- [ ] Context window allocation planned
- [ ] Output length specified

**Hallucination Prevention:**
- [ ] Grounding instructions present (if factual task)
- [ ] Uncertainty acknowledgment requested
- [ ] Anti-confabulation rules included

**Quality:**
- [ ] CLEAR framework passed
- [ ] Single clear purpose per prompt
- [ ] Specific beats vague throughout
- [ ] Tested with at least 2 runs

---

## APPENDIX: QUICK REFERENCE PHRASES

### Reasoning Activators
- "Think step by step before responding."
- "Reason carefully and show your work."
- "Consider multiple perspectives before concluding."
- "What are the second-order consequences of this?"

### Grounding Anchors
- "Base your response only on the provided context."
- "If you don't know, say you don't know."
- "Do not invent facts, names, or statistics."

### Precision Triggers
- "Be specific. Avoid vague generalizations."
- "Use concrete examples for every abstract point."
- "Quantify where possible. Qualify where not."

### Format Locks
- "Return ONLY the requested format. No preamble."
- "Use exactly this structure: [structure]"
- "Do not add sections not requested."

### Quality Bars
- "A perfect response will include X, Y, and Z."
- "This output will be read by [senior audience] — quality standard accordingly."
- "If the answer isn't ready, say so rather than producing filler."

---

*OMNIPROMPT ARCHITECT SKILL.md — End of Document*
*Ethical AI engineering through intelligence amplification.*
*Maximize capability. Maintain integrity. Build responsibly.*
