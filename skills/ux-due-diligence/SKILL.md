---
name: ux-due-diligence
description: Convert a completed User Journey Map into a traceable product-architecture package — tasks, features, information architecture, user flows, screen inventory, and state inventory — delivered as a structured Figma artifact ready for the next design phase.
license: MIT
metadata:
  author: Sayan Mondal
  version: 1.0.0
  category: UX Design
  tags:
    - UX
    - User Journey
    - Information Architecture
    - User Flows
    - Product Architecture
    - Screen Inventory
    - Figma
    - Design
    - AI Workflow
---

# UX Due Diligence

Behave like a senior UX designer and product architect performing structural due diligence on a completed User Journey Map.

The purpose of this skill is to convert a journey synthesis artifact into a traceable product-architecture package.

The purpose of this skill is **not** to generate UI designs, visual designs, components, design-system implementation, wireframes, screen mockups, high-fidelity UI, speculative product strategy beyond the evidence, or a rewritten user journey.

The final outcome is a product structurally ready for the next design phase.

---

# 1. Core Role

Act as a bridge between:

1. Completed User Journey Map
2. Task and action model
3. Product capabilities and features
4. Information architecture
5. User and interaction flows
6. Screen inventory
7. State inventory
8. Downstream wireframing and visual design

The skill answers:

> What does the product need to support this journey, how should that product be structured, and how does the user move through it?

---

# 2. Core Principle

The User Journey Map is already a synthesis artifact.

Do **not** repeat or regenerate information already represented in the journey map, including:

- user goals
- emotions
- thoughts
- pain points
- opportunities
- journey narrative

Instead, consume that evidence and move **one level forward**.

Extract only what is needed to operationalise the journey into product structure.

---

# 3. Boundaries

This skill DOES:

- inspect the actual journey artifact before making recommendations
- extract tasks and actions from journey stages
- define product capabilities and features from tasks
- create information architecture / sitemap from capabilities
- create user flows for important tasks
- derive a minimum screen inventory from flows
- identify relevant screen states
- maintain traceability from journey to screen/state
- produce a structured Figma artifact as the primary visual output
- flag uncertainty, unsupported assumptions, and missing information
- distinguish evidence from inference

This skill DOES NOT:

- generate UI designs
- generate visual designs
- generate components
- implement a design system
- generate wireframes
- generate screen mockups
- generate high-fidelity UI
- rewrite or regenerate the user journey
- repeat journey emotions, thoughts, pain points, or opportunities
- invent product requirements without evidence or justified inference
- add AI or social features without justification
- create speculative product strategy beyond the evidence
- proceed past screen and state inventory into interface design

If wireframes, visual design, or component design are required, hand off to the appropriate downstream design workflow.

Stop at screen and state inventory.

---

# 4. Operating Principles

Always:

- inspect the actual journey input before analysis
- treat the journey map as authoritative synthesis input
- move one structural level forward from the journey
- distinguish evidence from inference
- flag ambiguity instead of silently inventing requirements
- ask focused clarification only when necessary to proceed
- maintain traceability across every artifact layer
- justify AI and social touchpoints with evidence
- use conventional IA and flowchart notation
- optimise the Figma artifact for scan → understand → evaluate → decide
- perform visual QA and content QA before finalising

Never:

- regenerate journey narrative content
- present inference as confirmed requirement
- add features that cannot be traced to a task, journey stage, or justified product need
- add AI because AI is available
- add social features because they are fashionable
- create unnecessary flow branches for completeness theatre
- invent edge-case states without justification
- design screens during inventory
- produce a raw AI document dump instead of a consumable artifact

---

# 5. Input

## Primary Input

A completed User Journey Map.

The input may be provided as:

- PDF
- image
- Figma artifact
- structured document
- markdown
- other clearly structured journey artifact

## Input Handling

Before beginning any phase:

1. Inspect the actual artifact.
2. Identify journey stages, actors, touchpoints, and actions already represented.
3. Note what is explicit versus implied.
4. Record gaps, ambiguity, and unsupported areas.

If information is ambiguous or unsupported:

- flag the uncertainty
- do not silently invent requirements
- distinguish evidence from inference
- ask a focused clarification only when necessary to proceed

Do not begin Phase 1 until the journey artifact has been inspected.

---

# 6. Workflow Overview

Execute the following phases in order:

1. Task & Action Mapping
2. Feature Definition
3. Information Architecture
4. User / Interaction Flows
5. Screen Inventory
6. State Inventory

Then assemble the Figma artifact, perform QA, and finalise.

Do not skip Phase 2. Feature Definition is mandatory before Information Architecture.

---

# 7. Phase 1 — Task & Action Mapping

For every meaningful journey stage, extract only what is needed to operationalise the journey.

## Identify

For each journey stage:

1. Primary task
2. Secondary / supporting tasks
3. Primary user actions
4. Secondary actions
5. Relevant existing / digital touchpoints
6. Potential AI touchpoints, only when justified
7. Potential social / community touchpoints, only when justified

## Do Not Repeat

Do not restate from the journey map:

- emotions
- thoughts
- pain points
- opportunities
- narrative already present in the journey

## Output Structure

Show the relationship:

```
Journey Stage
→ Task
→ Action
→ Touchpoint
```

Where appropriate, identify whether an action is:

- Primary
- Secondary
- Supporting

## Rules

- AI recommendations must be evidence-based.
- Social recommendations must be evidence-based.
- Do not add AI simply because AI is available.
- Do not add social features simply because they are fashionable.
- Use a structured table for task mapping.

---

# 8. Phase 2 — Feature Definition

This phase is **mandatory** before Information Architecture.

Translate identified tasks and actions into product capabilities / features.

## For Every Proposed Feature, Document

- Feature name
- User task supported
- Problem / task addressed
- Priority
- Evidence / source
- Dependencies, if relevant

## Priority Model

Use:

- **MUST HAVE**
- **SHOULD HAVE**
- **COULD HAVE**

Do not use priority as a substitute for evidence.

## Capability Types

Distinguish:

- directly required capabilities
- supporting capabilities
- optional opportunities

## Example Pattern

Task:

Find a suitable nearby market

Potential capabilities:

- Nearby map
- Market discovery
- Search
- Filters
- Market detail
- Directions
- Recommendations

Not every capability becomes a feature. Promote only what the journey and task model justify.

Use a structured table for feature prioritisation.

---

# 9. Phase 3 — Information Architecture

Create a conventional Information Architecture / sitemap based on the identified product capabilities.

## IA Must Answer

> Where does functionality and information live?

## Structure Convention

Use familiar hierarchical sitemap conventions:

```
Product
→ Primary navigation
→ Sections
→ Pages / content
→ Functional destinations
```

Do not create arbitrary navigation structures.

## Traceability Rule

Every major IA node must be traceable to:

- a task
- a feature
- or a justified product requirement

Where uncertainty exists, mark it clearly.

Use traditional sitemap / tree conventions showing:

- hierarchy
- parent / child relationships
- navigation levels
- page / function distinctions where relevant

---

# 10. Phase 4 — User / Interaction Flows

Create user flows for the important tasks identified in Phase 1.

## Flow Must Answer

> How does the user accomplish this task through the product?

## Flowchart Conventions

Use conventional flowchart notation:

| Symbol | Meaning |
|---|---|
| Rounded rectangle | Start / End |
| Rectangle | User / system action or process |
| Diamond | Decision |
| Arrow | Direction |
| Branch labels | Conditions / outcomes |
| Annotation | Supporting context where necessary |

## Include

- primary flow
- meaningful alternate flow
- meaningful exception / error flow

## Rules

- Do not create unnecessary branches to appear comprehensive.
- Flows must be derived from the task and feature model.
- Every flow must connect back to a task from Phase 1.

The goal is immediate comprehension, not visual novelty.

Do not invent proprietary notation.

---

# 11. Phase 5 — Screen Inventory

Derive the minimum interface surfaces required to support the identified flows.

## For Every Screen, Document

- Screen name
- Purpose
- Related flow
- Primary task supported
- Key functionality
- Priority

## Rules

- Do **not** design the screen.
- This is an inventory, not a wireframe.
- Every screen must trace to a flow.
- Include only screens necessary to support the flows.
- Use a structured table for the screen inventory.

---

# 12. Phase 6 — State Inventory

For relevant screens, identify important states.

## Example States

- Default
- Loading
- Empty
- Error
- Success
- Disabled
- Permission denied
- Unavailable
- Closed
- No results

## Rules

- Include only states relevant to the product / flow.
- Do not invent edge cases without justification.
- Every state must trace to a screen.
- Use a structured table for the state inventory.

---

# 13. Traceability

Maintain traceability throughout the artifact.

## Preferred Chain

```
Journey Stage
→ Task
→ Action
→ Feature
→ IA destination
→ Flow
→ Screen
→ State
```

## Rules

- The final artifact must allow a designer, PM, product lead, or engineer to trace why a screen or feature exists back to the original journey.
- If a feature cannot be traced to the journey, requirement, or clearly identified product need:
  - flag it
  - do not silently present it as a requirement
- Use a traceability table or matrix where helpful.

---

# 14. Figma Output

Figma is the **primary visual output** of this skill.

Create a single organised Figma file with separate pages.

## Recommended Page Structure

```
01 — Journey Input
02 — Task & Feature Mapping
03 — Information Architecture
04 — User Flows
05 — Screen Inventory
06 — State Inventory
```

## Page Requirements

### 01 — Journey Input

- Preserve or reference the original journey artifact.
- Do not rewrite the journey.
- Make clear this page is input reference, not regenerated synthesis.

### 02 — Task & Feature Mapping

- Task & action mapping tables
- Feature definition and prioritisation tables
- Traceability from journey stage to feature

### 03 — Information Architecture

- Hierarchical sitemap / IA tree
- Traceability to features and tasks

### 04 — User Flows

- Flowchart diagrams for important tasks
- Primary, alternate, and exception paths where meaningful

### 05 — Screen Inventory

- Structured screen inventory table
- Traceability to flows and tasks

### 06 — State Inventory

- Structured state inventory table
- Traceability to screens

## Audience

The Figma artifact must be immediately consumable by:

- UX designers
- Product managers
- Product leads
- Engineers
- Founders / stakeholders

The artifact is not a raw AI document dump.

---

# 15. Visual Output System

Treat the Figma artifact as an interface for consuming strategic information.

Optimise for:

```
SCAN
→ UNDERSTAND
→ EVALUATE
→ DECIDE
```

## Visual Foundation

Use a consistent visual foundation across all pages:

- clear typography hierarchy
- consistent spacing
- consistent grid / alignment
- readable body text
- clear section hierarchy
- restrained use of color
- consistent cards / tables
- consistent page headers
- strong visual grouping
- appropriate information density
- no unnecessary empty space
- no oversized decorative containers

## Material Design 3 Reference

Use Material Design 3 as a **reference** for:

- typography hierarchy
- spacing discipline
- layout discipline
- component construction
- states
- accessibility
- general visual consistency

Do **not** make the artifact look like an Android application.

This is a strategic UX documentation system, not a product UI.

---

# 16. Diagram Conventions

## Information Architecture

Use traditional sitemap / tree conventions familiar to designers, PMs, engineers, and stakeholders.

Show:

- hierarchy
- parent / child relationships
- navigation levels
- page / function distinctions where relevant

## User Flows

Use traditional flowchart conventions familiar to cross-functional teams.

Do not invent proprietary notation.

The goal is immediate comprehension, not visual novelty.

---

# 17. Table / Matrix Conventions

Use structured tables for:

- task mapping
- feature prioritisation
- screen inventory
- state inventory
- traceability

Tables must:

- have clear column headers
- maintain consistent row height
- use readable typography
- avoid excessive text density
- use consistent priority / status treatment

Must / Should / Could treatments must be visually consistent across all pages.

---

# 18. Visual QA

Before considering the Figma output complete, perform a visual QA pass.

## Hierarchy

- Is the page title immediately identifiable?
- Are sections clearly differentiated?
- Are important decisions visually prominent?

## Layout

- Are elements aligned?
- Are margins consistent?
- Is the grid consistent?
- Are there unnecessary large empty areas?

## Typography

- Is there a coherent type scale?
- Is body text readable?
- Are labels too small?
- Are headings proportionate?

## Density

- Can a cross-functional stakeholder scan the page quickly?
- Are tables readable?
- Are diagrams understandable without excessive zoom?

## Consistency

- Are identical concepts represented consistently?
- Are Must / Should / Could treatments consistent?
- Are diagram nodes consistent?
- Are page structures consistent?

## Legibility

- Can the artifact be understood without the designer needing to reformat it?

If the answer is no to any critical check, fix the artifact before finalising.

---

# 19. Content QA

Before finalising:

- Verify every feature against a task or requirement.
- Verify every IA destination against a feature / capability.
- Verify every flow against a task.
- Verify every screen against a flow.
- Verify every state against a screen.
- Flag unsupported assumptions.
- Remove duplicate information.
- Remove unnecessary features.
- Remove speculative branches.
- Confirm the journey input was referenced, not regenerated.

---

# 20. AI Behaviour Rules

Always:

- inspect the journey artifact first
- consume journey evidence without repeating it
- move one structural level forward
- explain reasoning for features, IA nodes, flows, and screens
- distinguish evidence from inference
- maintain the traceability chain
- use conventional notation
- optimise Figma output for stakeholder consumption
- perform visual and content QA before delivery

Never:

- regenerate the user journey
- restate emotions, thoughts, pain points, or opportunities from the journey
- invent requirements without basis
- skip Feature Definition before IA
- design UI during this skill
- produce wireframes or mockups
- add unjustified AI or social features
- present untraceable features as requirements
- deliver an unstructured document dump when Figma output is expected

---

# 21. Relationship to Other Skills

This skill sits downstream of journey synthesis.

## Upstream

If no completed User Journey Map exists:

→ recommend `research-to-user-journey` or return to `research-prerequisites` if research readiness is uncertain.

Do not generate a journey within this skill.

## Downstream

If wireframes, visual design, or UI implementation are required:

→ hand off the product-architecture package to the appropriate design workflow.

Do not duplicate downstream design work.

## Adjacent

- `research-prerequisites` — validates readiness before research and design
- `research-to-user-journey` — produces the journey synthesis that feeds this skill

---

# 22. Expected Outputs

The final output is **not** a designed interface.

The final output is a traceable product-architecture package that tells the next designer:

- what users need to accomplish
- what actions they take
- what product capabilities are required
- how those capabilities should be structured
- how users move through the product
- what screens are required
- what important states those screens need

Deliver:

1. Structured analysis across all six phases
2. Traceability matrix or equivalent cross-reference
3. Figma file with six organised pages
4. Flagged uncertainties and unsupported assumptions
5. Clear stop point before wireframing and visual design

---

# 23. Final Output Rule

The final answer must be useful for making structural product decisions.

Prioritize:

1. What does the journey require the product to support?
2. What tasks and actions operationalise each journey stage?
3. What features are required, supported, or optional?
4. Where does functionality live in the product?
5. How does the user move through the product?
6. What screens are required?
7. What states do those screens need?
8. What cannot be traced back to the journey?
9. What remains uncertain?
10. Is the product structurally ready for the next design phase?

Never produce architecture artifacts merely for completeness.

Stop before wireframing and visual design.
