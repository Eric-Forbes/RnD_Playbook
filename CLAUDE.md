# CLAUDE.md — Master Reference: Enabling the Frontier

> **For any Claude instance reading this:** This is the canonical source of truth for Eric Forbes's
> leadership book project. Chat history is unreliable across sessions. Always start here.
> Always update this file when a principle is added, moved, renamed, or a story is attached.
> Never finalize placement of a principle or story without Eric's explicit sign-off.

---

## Book Identity

**Title:** *Enabling the Frontier: A Playbook for Building and Leading Cutting-Edge R&D Teams*

**Audience:** Practitioners leading engineering and R&D teams doing frontier work.

**Ethos:** Positive cultural enablers — the conditions, disciplines, and mindsets that allow teams
to operate at the edge. Counter-instinctive by design. Good fundamentals must be actively
maintained against organizational entropy.

**Format inspiration:** *48 Laws of Power*, *How to Win Friends and Influence People* —
bold principle stated first, stories follow and support.

**Reference texts:**
- *Reinventing Project Management* (Shenhar & Dvir) — Diamond Model
- *48 Laws of Power* — format model
- *How to Win Friends and Influence People* — format model

---

## Structure Overview

32 principles across 5 sections. See full outline below.

---

## Section I — Building the Team (8 Principles)

1. **Cultivate Broad Capability First** — Build team depth before optimizing for output.
2. **Remove the Layers** — Eliminate bureaucratic layers that slow frontier work.
3. **Altitude of Decomposition** — Use decomposition level as a seniority/growth framework.
4. **Stakeholder Registry** — Communication architecture, not just a contact list.
5. **Project vs. Operations Clarity** — Know which mode you're in; they require different leadership.
6. **The Junkyard Principle** — [Principle body TBD]
7. **[Principle 7 TBD]**
8. **[Principle 8 TBD]**

---

## Section II — Leading the Team (9 Principles)

1. **Demo Discipline** — Demo what you have, on cadence. Positive discipline, not punishment.
2. **Servant Leadership** — Leader serves the team's ability to do the work.
3. **Maintain Fundamentals Under Pressure** — Good habits erode first under stress; defend them.
4. **The Power of Saying No** — Protecting team focus is a leadership act.
5. **Communication Infrastructure** — Deliberate architecture for information flow.
6. **Psychological Safety** — Teams that can fail safely learn faster.
7. **Humble / Parenting-Style Leadership** — [Placement TBD — may be standalone or
   emotional underpinning of servant leadership; resolve before finalizing]
8. **Earn Your Real Estate** — Internal promotion as a leadership responsibility.
9. **Information Gatekeeping Is Toxicity** — Hoarding information is invisible hierarchy.
   [Story banked — placement confirmed Section II, parent principle TBD]

---

## Section III — Perspective & Framing (10 Principles)

1. **Engineers as Self-Managing** — When they understand the full trade space, engineers
   self-direct effectively.
2. **Vision Sourcing vs. Sinking** — Leaders source vision upward, don't sink it.
3. **Radical Optimism** — Optimism as a discipline, not a mood.
4. **Protect the Passion** — Guard what drives people; it's the engine of frontier work.
5. **Program Management from Day One** — Time, cost, scope, manufacturability as dimensions
   from the start (ref: Shenhar & Dvir Diamond Model).
6. **Feedback Is the Multiplier** — Feedback loop quantity is a key outcome driver.
7. **The Fulcrum Principle** — Physical proximity to your team is a leadership act.
8. **Super-Optimism / Protect the Magic** — [May merge with Radical Optimism — resolve]
9. **[Principle 9 TBD]**
10. **[Principle 10 TBD]**

---

## Section IV — Recognition & Belief (2 Principles) ⚠️ UNDERDEVELOPED

> Flag: This section needs significant development. Only 2 principles currently placed here.

1. **Specific Earned Affirmation** — Specific, earned affirmation as load-bearing fuel.
   Not generic praise. Named, observed, timely.
2. **[Principle 2 TBD]**

---

## Section V — Knowledge & Continuity (3 Principles)

1. **Apply Academic Research Rigor** — Research-grade documentation discipline applied
   to business R&D.
2. **Stand on Each Other's Shoulders** — The only principle with a fully attached story.
   [See Story Bank below]
3. **[Principle 3 TBD]**

---

## Story Bank

Stories are captured raw here. They are NOT attached to principles until Eric explicitly
confirms placement.

| Story | Raw Capture | Confirmed Placement |
|---|---|---|
| **Red Program Tracing** | Team traced every decision back through documentation; new members could reconstruct full reasoning without asking anyone. Revealed the power of living knowledge systems. | Section V — "Stand on Each Other's Shoulders" ✅ CONFIRMED |
| **Too Many Architects** | Story about a team where too many senior people optimized for perfection over progress; paralysis by architecture. | Unconfirmed — near Section I or III perfection-vs-progress cluster |
| **Conflict via Depersonalization** | Using "we" language and depersonalizing conflict to resolve team tension without blame. | Unconfirmed |
| **Servant Leader Steps Back** | Leader deliberately steps back to let a team member own a win, developing them as a future leader. | Unconfirmed — near Section II Servant Leadership |
| **Workflow Design / Pivot-Persist** | Story about discipline in deciding when to pivot vs. persist on a failing approach. | Unconfirmed |
| **Delegation Without Creative Ownership** | "Delegation without creative ownership is just tasking." Placed as counter-example under Vision First. | Unconfirmed — Section III Vision Sourcing |
| **Information Gatekeeping** | Leader who hoarded information created invisible hierarchy and eroded trust. | Unconfirmed — Section II, parent principle TBD |

---

## Open Structural Questions

These must be resolved with Eric before placement is finalized:

1. **Helmier Catechism** — Is this a formal named framework or Eric's adaptation?
   Spelling flagged for verification. Where does it live?
2. **Apollo Decomposition + Time-as-Currency** — One principle or two?
3. **Parenting Analogy** — Standalone principle or emotional underpinning of existing
   servant leadership themes?

---

## LaTeX Project Structure

```
RnD_Playbook/
├── CLAUDE.md           ← This file. Source of truth.
├── main.tex            ← Master document (inputs all sections)
├── outline.tex         ← Full structural outline (all 32 principles)
├── preamble.tex        ← Packages, fonts, formatting
├── sections/
│   ├── front_matter.tex
│   ├── section1_building.tex
│   ├── section2_leading.tex
│   ├── section3_framing.tex
│   ├── section4_recognition.tex
│   └── section5_knowledge.tex
└── output/
    └── playbook.pdf    ← Compiled output
```

---

## Key Working Rules for Claude

- **Stories serve principles, not the other way around.** Never attach a story to a principle
  without Eric's explicit confirmation.
- **This file is the source of truth.** Update it every session when anything changes.
- **Eric communicates in compressed conceptual shorthand.** Expand without losing intent.
- **Thematic clustering matters.** Perfection-vs-progress themes should be proximate.
  "Vision First" is the philosophical foundation. "Remove the Layers" is its operational expression.
- **Structural redundancy is actively managed.** Overlapping principles get consolidated,
  not duplicated.
- **Probe before placing.** Ask: one principle or two? Standalone or supporting?
- **Section IV is underdeveloped.** Flag it. Prompt Eric to develop it when opportunity arises.
- **The book's expansion path:** skeleton is strong; what's needed is Eric narrating the
  personal stories behind each principle to generate elaboration and connective tissue.
