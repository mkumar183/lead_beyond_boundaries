# Presentation Outline — Applying *Lead Beyond Boundaries* to AI Adoption at Scale

> **Goal:** Build a playbook for AI Adoption across the organisation, derived strictly from the principles in [workbook_principles.md](workbook_principles.md). Show the *delta* between the default approach (without the training) and the principled approach (with the training).

> **Length:** 12 slides — title + 10 content + closing.

> **Narrative arc:** Frame the challenge → Show the default approach (and why it fails) → Apply each workbook principle as a concrete move → Synthesise into a playbook.

---

## Slide 1 — Title
**Title:** From Tooling Rollout to Adaptive Leadership
**Subtitle:** Applying *Lead Beyond Boundaries* to AI Adoption at Scale
**Footer:** A principle-driven playbook · Workbook → Use Case → Practice

---

## Slide 2 — The Challenge: Why AI Adoption Is Hard
**Type:** Problem framing slide

**Headline:** *AI Adoption is not a tooling problem. It is an adaptive challenge — and here are the five reasons it stalls.*

**The Five Real Challenges:**

1. **It is a completely new skill, not a tool upgrade.** AI adoption is not "use Copilot to write code faster." It is learning **prompt engineering** — a fundamentally different craft. Engineers still need to understand systems and design, but they no longer need to know specific syntax and write it themselves. That is a seismic identity shift, not a training-video fix.

2. **Psychological safety is under threat.** Engineers fear losing their jobs. Models are evolving at a pace where what is valid today may not be valid in a few months. The future of the software engineer feels genuinely uncertain — and that uncertainty is paralysing, not motivating.

3. **Not adopting is not a choice — but saying that doesn't help.** As leaders, we know the teams *must* adopt and learn. But mandating adoption into a fearful room produces compliance theatre, not real change. The challenge is to convince without coercing.

4. **Real productivity benefits are unclear.** AI generates code fast — but testing, validating, and ensuring outcomes are reliable is still time-consuming. The net gain is murky, and engineers who try it and find the promise oversold become the hardest skeptics to re-engage.

5. **The bottleneck has shifted, not disappeared.** Writing code has become dramatically faster — but other steps in the SDLC (testing, code review, deployment, observability, change management) are still slow. The system is only as fast as its slowest step, and the slowest step is no longer the one AI accelerated.

**Principle anchor:** Heifetz — *"Adaptive challenges can only be addressed through changes in people's priorities, beliefs, habits, and loyalties."*

**The question this deck answers:** How does each principle from the workbook help us lead through these five challenges — not around them?

---

## Slide 3 — Adaptive vs Technical: Diagnosing the Real Problem
**Type:** Two-column comparison (Technical | Adaptive)

**Left column — If we treat AI Adoption as TECHNICAL:**
- Known solution: buy licenses, run training videos, set quotas
- Command compliance: "everyone uses Copilot by Q3"
- Measure: % engineers logged in, lines generated, license utilisation
- Follow tried-and-tested rollout playbooks
- Assume: code generation = productivity gain (ignore the rest of the SDLC)
- Assume: engineers just need a tool, not a new skill

**Right column — But AI Adoption is ADAPTIVE:**
- **New skill, not new tool:** prompt engineering is a different way of thinking — engineers must learn to direct, not write
- **Identity under threat:** "I am a backend engineer" is being dissolved — the new role cuts across everything
- **Fear is rational:** models evolve so fast that mastering today's workflow feels temporary; job uncertainty is real
- **Productivity is ambiguous:** code is generated faster, but validation, testing, and reliability still consume the time — net gain is not obvious
- **Bottleneck shifted:** writing code was the bottleneck; now testing, review, deployment, and observability are — and nobody accelerated those yet
- Requires changing attitudes, values, deep-seated behaviours — not just provisioning licences

**Take-home line:** Every one of our five challenges is adaptive, not technical. Diagnosing this correctly *is* the first leadership move. Get this wrong and every subsequent move misfires.

---

## Slide 4 — How We Would Have Approached This *Without* the Training
**Type:** "Default mode" / Loyal Soldier slide (intentionally uncomfortable)

**Headline:** *The Loyal Soldier defaults — well-intentioned, but adaptive-blind.*

**Bullets (each tagged to a Loyal Soldier behaviour → and which challenge it fails at):**
- **Respond to expectations** → Wait for the executive AI mandate; cascade as a directive → ❌ *Fails Challenge 3:* mandating into fear produces compliance theatre
- **Comply and appease** → "Leadership wants AI used, so use it" → ❌ *Fails Challenge 2:* ignores the psychological safety crisis underneath
- **Communicate at task levels** → Status reports: "X% adoption, Y licenses provisioned" → ❌ *Fails Challenge 4:* hides that real productivity gains are still unproven
- **Wait to be invited** → Each EM runs their own pilot; no shared learning → ❌ *Fails Challenge 5:* nobody addresses the SDLC bottleneck that moved downstream
- Treat prompt engineering as an optional "tips and tricks" add-on → ❌ *Fails Challenge 1:* misses that this is an entirely new skill, not a tool add-on
- Skeptics treated as *obstacles to overcome* — convert them or work around them
- Guardrails written *after* incidents; reactive, not anticipatory
- Success measured as throughput ("did they log in?"), not quality ("did rework drop?")

**Principle anchor:** Workbook *Loyal Soldier* defaults.

**Predicted outcome:** Joins the 85% of enterprises stuck in pilot purgatory — because every one of the five real challenges was met with a technical response to an adaptive problem.

---

## Slide 5 — The Mindshift: Loyal Soldier → Growth Partner
**Type:** Bridge slide / pivot point

**Headline:** *The training does not change the goal. It changes the leadership stance.*

**Two-column FROM → TO (verbatim from workbook):**
| FROM: Loyal Soldier | TO: Growth Partner |
|---|---|
| Respond to expectations | Anticipate & engage |
| Comply and appease | Create & collaborate |
| Communicate at task levels | Communicate impact |
| Wait to be invited | Influence by design |

**How Growth Partner addresses each challenge:**
- *Challenge 1 (New skill):* Growth Partner **anticipates** that prompt engineering is a career shift, not a training module — and designs learning paths accordingly.
- *Challenge 2 (Job fear):* Growth Partner **creates & collaborates** — co-designs the future role with engineers rather than announcing it to them.
- *Challenge 3 (Must adopt):* Growth Partner **communicates impact** — makes the case through purpose, not mandate.
- *Challenge 4 (Unclear productivity):* Growth Partner **influences by design** — measures real outcomes (rework, quality, cycle time), not vanity metrics.
- *Challenge 5 (SDLC bottleneck):* Growth Partner **anticipates & engages** — names that the bottleneck moved and designs for the whole pipeline, not just code generation.

**Speaker note:** Every move in the rest of the deck is a *Growth Partner* move applied to AI adoption. Each slide takes one or more of these five challenges and shows which principle resolves it.

---

## Slide 6 — The VALUE Framework Applied to AI Adoption
**Type:** Five-row card layout — one per letter, each with a concrete engineering-team scenario

**Headline:** *VALUE turns "do AI" into a question discipline — applied to the engineering team we actually run.*

### **V — Visualise: How does AI transform an engineering team in 3–5 years?**
*Workbook anchor:* "If this succeeds beyond expectations, what is different 3–5 years from now? What would future leaders thank us for starting today?"

**Concrete picture for our engineering org:**
- The role itself dissolves the old boundaries: a "frontend engineer" or "backend engineer" becomes a **full-stack engineer cutting across dev, QA, DevOps, and data** — able to tie a whole solution together because the AI handles the depth in any one layer.
- **Software gets dramatically cheaper to build.** A two-week feature becomes a two-day feature. What does the industry look like when the cost curve collapses? Are we ready for 10× more ideas reaching production — or 10× fewer engineers shipping the same roadmap?
- The differentiator is no longer "can you code this" — it is **"do you understand the business well enough to choose what to build?"** Engineers move from order-takers to **growth partners alongside product management**, co-owning outcomes, not just stories.
- Career ladders, hiring rubrics, and what "senior" means all need to be rewritten. If we don't redesign them, we will keep promoting for a craft the market no longer pays for.

**Visualise question for the room:** *Three years out, is our team a group of specialists waiting for tickets, or a group of solution-owners co-creating with PM and the business? Which future are we building toward this quarter?*

### **A — Anticipate & Ask** → addresses Challenge 1 (new skill), Challenge 2 (job fear), Challenge 4 (unclear productivity)
*Workbook anchor:* "What patterns are repeating that we are normalising? What question are we afraid to ask?"

**Concrete moves:**
- Catch "pilot becomes permanent pilot" — the pattern where AI work never crosses into production.
- Name the unspoken question: *"If AI writes 60% of the code, what happens to the engineer who built their identity on writing it?"* Senior-engineer identity threat is real and addressable — only if named.
- Ask the question nobody wants to ask: *"Models are evolving every quarter. Are we teaching a skill or chasing a moving target? And if chasing — how do we build learning systems, not training events?"*
- Anticipate the productivity disillusionment: *"Teams will try AI, find that testing and validation still take the same time, and conclude it doesn't work. Are we ready with a nuanced narrative before that happens?"*
- Ask early: *which roles in our org are we quietly planning around, instead of designing for?*

### **L — Lead from Purpose**
*Workbook anchor:* "What is the cause I am serving beyond my role or title?"

**Concrete moves:**
- Reframe the cause: not an "efficiency mandate" (which reads as "headcount cut" and triggers defence), but **"engineers as growth partners — closer to the grower, closer to the business outcome."**
- Speak from purpose: *we are not adopting AI to ship cheaper code; we are adopting it to free engineers to do the work only humans can do — judgement, design, business partnership.*
- Test the message: would the most skeptical senior engineer in the room recognise themselves as the *beneficiary* of the change, or the *casualty*?

### **U — Understand Context & Cultural Nuance**
*Workbook anchor:* "Am I speaking the language of my stakeholder? Or expecting them to learn mine?"

**Concrete moves:**
- Translate across audiences: "this LLM agent does X" → for an agronomist: *"this changes how a seed recommendation gets made"*; for a PM: *"this collapses discovery-to-prototype from weeks to days"*; for an engineer: *"this is your pair, not your replacement."*
- Respect the high-power-distance, high-uncertainty-avoidance reality of our culture: don't ask engineers to experiment in public without a published guardrail.
- Watch the impact gap: our intent is "empower"; the impact, unmanaged, can land as "evaluate." Close that gap explicitly.

### **E — Enable, Energise & Engage** → addresses Challenge 4 (unclear productivity), Challenge 5 (SDLC bottleneck)
*Workbook anchor:* "What is currently making it hard for others to do their best work? What needs to be removed, not added?"

**Concrete moves:**
- **Publish guardrails *before* pushing usage** — remove the "is AI OK here?" ambiguity that silently blocks adoption.
- Remove friction: license access, prompt libraries, a Coding Agents Policy, an AI-disclosure norm in PRs — so the easy path is the right path.
- **Name the bottleneck shift explicitly:** code generation got faster — but testing, review, deployment, and observability did not. Enable means investing in AI-assisted testing, automated review, and CI/CD acceleration — not just more code generation tools. The SDLC is a pipeline; speeding up one stage without enabling the rest creates a traffic jam, not a breakthrough.
- **Make the productivity conversation honest:** don't oversell. Enable teams to measure what actually improved (rework down, defects caught earlier, cycle time reduced) and what didn't (validation time, review time). Honest measurement builds trust; inflated claims destroy it.
- Energise through visibility: Brown Bag forums where engineers show *both* what worked and what failed. Failure content is what builds trust, not curated wins.
- Engage PM and business partners *into* the engineering practice — so the "growth partner" identity is built every sprint, not announced once a year.

**Take-home line:** VALUE is not a slogan — it is a discipline. Visualise tells us what the role becomes; Anticipate names the fear; Lead reframes the cause; Understand translates across stakeholders; Enable removes the friction. Skip any letter and adoption stalls in a predictable place.

---

## Slide 7 — The Trust Model: Building Psychological Safety in an Uncertain World
**Type:** Four-quadrant card layout (R · A · O · C)

**Challenge focus:** Challenge 2 (psychological safety / job fear) and Challenge 4 (unclear productivity)

**Headline:** *Engineers cannot adopt what they fear will replace them. Trust is the prerequisite — not the by-product — of adoption.*

**Four quadrants — Trust element → how it builds safety:**

- **Reliability** — *Do what you say.* Publish a Coding Agents Policy and **stick to it**. Don't pivot tooling every quarter — models are already evolving too fast for engineers to feel stable. The one thing leaders *can* stabilise is the framework, the guardrails, and the commitments. If you say "no one loses their job because of AI adoption," that statement must hold. Say it only if you mean it.
- **Acceptance** — *Don't try to change people.* When a senior engineer says "AI gives wrong suggestions half the time" — they are right, and they are also protecting a decade of invested craft. Accept both truths. When someone says "I'm worried my role won't exist in two years" — that is not resistance. It is a rational reading of the landscape. **Acceptance means creating space for that fear, not dismissing it as negativity.** The workbook says: *Practices that create psychological safety through candour with respect.*
- **Openness** — *People can take good news or bad news, but not surprises.* Be honest that the productivity benefits are still emerging and uneven. Be transparent that models will keep evolving and today's workflow may change. Share what you *don't* know — "we don't know exactly how roles will evolve, but here is our commitment: we will design that evolution *with you*, not *for you*." Brown Bag sessions surface what didn't work, not just success stories.
- **Congruence** — *Walk my talk.* Leaders who advocate AI must use it visibly themselves — including struggling with it publicly. If you are asking engineers to learn prompt engineering, show your own learning curve. Bring imperfect AI-drafted artefacts to be co-edited. If you say "not adopting is not a choice" but your own calendar shows no AI learning time, the gap between your words and actions is visible — and trust collapses.

**Capstone move:** Co-author AI usage guidelines *with the loudest skeptic in each squad.* People defend what they build — conversion attempts replaced with co-authoring. This is how you turn "not adopting is not a choice" (Challenge 3) from a mandate into a movement.

---

## Slide 8 — Three Levels of Listening: Hearing What Engineers Actually Fear
**Type:** Four-card stack (Level 0 → 1 → 2 → 3)

**Challenge focus:** Challenge 1 (new skill), Challenge 2 (job fear), Challenge 4 (unclear productivity)

**Headline:** *Most adoption conversations stop at Level 1. The five real challenges only surface at Levels 2 and 3.*

**Four levels — what changed when we listened deeper:**

- **Level 0 — My assumptions.** *Our bias as leaders:* "engineers resist because they're behind on AI." Reality: they resist because the ask is poorly framed. We assumed it was a tool problem (Challenge 1 misread). We also carried the assumption that productivity gains are obvious — they aren't (Challenge 4 misread).

- **Level 1 — What is stated.** Engineers said:
  - "AI hallucinates. Quality is risky." ← surface of Challenge 4
  - "I still have to test everything AI writes — it's not actually faster." ← surface of Challenge 5
  - "The tools change every month; I can't keep up." ← surface of Challenge 2
  Useful data, but still the *presenting* problem, not the *underlying* one.

- **Level 2 — Feelings, needs, assumptions.** What they actually fear, when asked deliberately:
  - *"Will my manager think I didn't do the work?"* — fear of being seen as lazy or replaceable (Challenge 2)
  - *"I spent 15 years mastering Java. Now you're telling me the skill is prompt engineering? What was it all for?"* — identity grief, not resistance (Challenge 1)
  - *"Every 3 months there's a new model, a new tool. I learn one, it's obsolete. Why invest?"* — rational fatigue from model velocity (Challenge 2)
  - *"We're writing code 3× faster but the PR queue is the same. It doesn't feel faster."* — the bottleneck reality (Challenge 5)
  These fears are invisible at Level 1. They are also the real blockers.

- **Level 3 — What is possible.** Questions that shifted the room:
  - *"If the skill is prompt engineering + system design + business understanding, what does the career path look like? Can you help us design it?"* ← Challenge 1 unlocked
  - *"If you owned the AI quality guidelines, what would they look like?"* ← Challenge 4 unlocked — skeptics became authors
  - *"If we freed up 40% of coding time, what would you want to spend it on?"* ← Challenge 5 unlocked — engineers started designing for the full SDLC, not just code generation
  - *"What would make you feel safe enough to experiment publicly?"* ← Challenge 2 unlocked — this question produced the AI-disclosure norm and the Brown Bag forum

**Take-home line:** Out of Level 2 + Level 3 listening came the Coding Agents Policy, AI usage disclosure norms, the Brown Bag forum, and the SDLC bottleneck redesign — not from a leadership decree. The five challenges cannot be solved by leaders who only listen at Level 1.

---

## Slide 9 — Hofstede: Designing for the Culture We Actually Have
**Type:** Cultural-dimension cards mapped to design choices

**Headline:** *We work in a high-power-distance, high-uncertainty-avoidance, collectivist culture. Design for it, don't fight it.*

**Challenge focus:** Challenge 2 (models evolving too fast / uncertainty), Challenge 3 (must adopt but can't mandate)

**Four dimensions, four design moves:**

- **High Power Distance** → Identify the *Invisible Influencer* in each squad — the senior engineer whose quiet adoption is the unlock. Co-author with them *before* any town hall. Status comes from rank — use that, don't pretend it doesn't exist. In a high-PDI culture, **Challenge 3 (must adopt)** is best solved not by mandate from the top, but by visible adoption from the respected senior — the squad follows the person they respect, not the email they received.

- **High Uncertainty Avoidance** → This is the dimension that explains why **Challenge 2 hits our teams so hard.** Models evolve every quarter. What engineers learn today may be obsolete in months. In a high-UAI culture, that velocity creates paralysis, not excitement. The design response: **stabilise what you can.** Publish the Coding Agents Policy *first*. Make guardrails durable even as tools change. Tell teams: *"The tools will keep changing — the principles, the guardrails, and your career path will not. Those are ours to hold steady."* Removing ambiguity is the largest single adoption unblocker in a high-UAI culture.

- **Collectivism** → Adoption spreads through the squad, not through the individual. Brown Bag forum (cross-squad learning) is the natural shape; one-on-one champion programs are not. In a collectivist culture, **Challenge 1 (new skill)** is learned together — prompt engineering becomes a shared craft, not an individual certification.

- **Short-term vs Long-term Orientation** → The fear that "this will all change in 6 months" (Challenge 2) is a short-term lens. Reframe: the *specific tools* are short-term; the *meta-skill* (directing AI, understanding systems, partnering with the business) is long-term. Help engineers see they are building a **durable capability**, not chasing a transient tool.

**Take-home line:** Cultural dimensions are not obstacles — they are the operating system. High UAI explains the paralysis; high PDI shows us the lever; collectivism shows us the channel; LTO gives us the reframe. Build for the culture you actually have.

---

## Slide 10 — Stakeholder Map + Non-Linear Thinking: The Operating Cadence
**Type:** Two-column — Stakeholder Map (left) | 4 A's (right)

**Left — Stakeholder Map applied:**
- Draw the map *before* any town hall
- **Trust line thickness** identifies which seniors will defend the change publicly
- **Reciprocity arrows** reveal where we ask too much and offer too little (often: pilot owners burning out)
- Re-draw quarterly. Thin spots are where to invest deliberately

**Right — Non-Linear Thinking (4 A's) as weekly practice:**
- **Ask** — What is each pilot owner *not* telling us in the weekly status? Curious inquiry over status-grading. Also ask: *"Where is the bottleneck now?"* — if code generation got faster but testing didn't, the 4 A's force us to name that before it becomes a normalised pattern (Challenge 5)
- **Anticipate** — Build the radar: which pilots will hit identity-threat resistance in the next 30 days? Which model updates will invalidate current workflows this quarter? Act now on both. Anticipate the productivity-disillusionment wave (Challenge 4) — teams will hit it around week 6–8 of adoption. Prepare the narrative *before* it arrives.
- **Amplify** — Spotlight the two agents that shipped to production. But also amplify the engineers who are **building the new skill** — the ones learning prompt engineering, redesigning their workflow, partnering with PM. Amplify the *new identity*, not just the new tool (Challenge 1).
- **Align** — Have alignment conversations with sponsors *before* the moment of decision. Align on what "productivity" actually means *before* dashboards get built. Align with HR on what the new career path looks like *before* engineers ask. Alignment ahead of time is how you convert "not adopting is not a choice" from a threat into a shared commitment (Challenge 3).

**Take-home line:** This is not a one-off design — it is a weekly cadence. The 4 A's are how you stay ahead of challenges that move faster than quarterly planning — and in AI, every challenge moves faster than quarterly planning.

---

## Slide 11 — The Playbook: From Principles to Practice
**Type:** Synthesis slide — the playbook as a numbered sequence

**Headline:** *The AI Adoption Playbook — derived directly from the workbook.*

**The 10-step playbook — each step maps to a challenge and a principle:**

1. **Diagnose adaptive, not technical** *(Heifetz)* — name the five real challenges (new skill, job fear, mandate paradox, unclear productivity, SDLC bottleneck) before you design any solution.
2. **Take the Growth Partner stance** *(Mindshift)* — anticipate, create, communicate impact, influence by design. Compliance theatre is the Loyal Soldier's legacy; don't inherit it.
3. **Frame prompt engineering as a career skill, not a tool tip** *(VALUE-V + Challenge 1)* — visualise the full-stack, business-partnering engineer of 2028. Design learning paths, career ladders, and hiring rubrics for that future now.
4. **Build psychological safety before pushing adoption** *(Trust-R,A + Challenge 2)* — name the job-fear reality honestly. Stabilise what you can (guardrails, career commitments, learning investment). Accept that the fear is rational; design for it.
5. **Publish guardrails first** *(VALUE-E + Hofstede UAI + Challenge 2)* — tools will keep changing; guardrails and principles must hold steady. Remove the "is AI OK here?" ambiguity *before* asking anyone to adopt.
6. **Measure honestly** *(VALUE-E + Challenge 4)* — don't oversell productivity. Measure rework, defect quality, cycle time, and time-to-value — not lines generated. Share what improved and what didn't.
7. **Design for the whole SDLC, not just code generation** *(VALUE-E + 4A's + Challenge 5)* — invest in AI-assisted testing, automated review, CI/CD acceleration. The bottleneck moved; follow it.
8. **Co-author with skeptics** *(Trust-Acceptance + Challenge 3)* — the loudest skeptic writes the boundary. This turns "not adopting is not a choice" from a mandate into a co-owned commitment.
9. **Listen at Level 2 and 3** *(3 Levels + all challenges)* — discover the identity grief behind the objection, the rational fear behind the resistance, and the system insight behind the complaint. Then ask what is possible.
10. **Practice the 4 A's weekly** *(Non-Linear Thinking)* — Ask what's unspoken, Anticipate the next model shift and the disillusionment wave, Amplify the new identity (not just the new tool), Align with sponsors and HR *before* the decision moment. This is a cadence, not an event — because AI moves faster than quarterly planning.

**Take-home line:** This is the playbook for leading AI adoption in a world where the technology changes every quarter but the human challenges remain constant. It is principle-derived, challenge-tested, and designed for leaders who know that not adopting is not a choice — but mandating is not a strategy.

---

## Slide 12 — Closing: The Delta Is the Training
**Type:** Closing slide / mirror of Slide 4

**Headline:** *Same goal. Different leadership choices.*

**Side-by-side close — mapped to each challenge:**
| Challenge | Without the training | With the training |
|---|---|---|
| **New skill** | "Here's a tool — use it" | Frame prompt engineering as a career skill; redesign ladders and rubrics |
| **Job fear** | Ignore or dismiss the anxiety | Name it, accept it, build psychological safety first |
| **Must adopt** | Mandate compliance | Co-author with skeptics; convert mandate into movement |
| **Unclear productivity** | Oversell; measure logins | Measure honestly — rework, quality, cycle time; share what didn't improve |
| **SDLC bottleneck** | Celebrate faster code generation | Design for the whole pipeline — testing, review, deployment, observability |
| *Overall stance* | Loyal Soldier: react, comply, report | Growth Partner: anticipate, co-create, communicate impact |

**Closing line:** *"The technology will keep changing — every quarter, every model release. What will not change are the five human challenges underneath. The playbook gives us a principle-driven way to lead through all of them. It is not a one-time plan; it is a practice. And not adopting that practice is not a choice — it is what separates the 15% who reach production from the 85% stuck in pilot purgatory."*

---

## Design Notes for the HTML Build (next step)

**Visual structure:**
- 12 slides, full-screen, keyboard + button navigation (same UX as `KEY_POINTS_PRESENTATION.html`)
- Slide 4 ("without training") in **warm red/orange palette** — discomfort-coded
- Slide 5 (mindshift) in **transition gradient** — pivot point visual
- Slides 6-10 (each principle applied) in **blue/principle palette** — methodical, calm
- Slide 11 (playbook) in **green/solution palette** — culmination
- Slide 12 (closing delta) in **purple/outcome palette** — same closing chord as the original deck

**Component patterns to reuse from `KEY_POINTS_PRESENTATION.html`:**
- Two-column compare grid (slides 3, 12)
- Three-column / four-card grids (slides 7, 8)
- Numbered playbook list (slide 11)
- Quote callouts for Heifetz / workbook excerpts

**One additional element to add:**
- Slide 11 needs a numbered playbook visual (not just bullets) — possibly numbered circles + step name + principle tag.

---

**Next step:** Confirm this outline, then build `AI_ADOPTION_PLAYBOOK_PRESENTATION.html` using these 12 slides.
