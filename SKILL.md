---
name: brand-system-builder
description: Guides Lovart Agent from one visual reference to a coherent brand system, campaign assets, and packaging concepts through a gated creative-direction workflow.
version: 0.2.0-alpha
author: Amir Mushich
license: CC-BY-4.0
optimized_for: Lovart Agent Thinking Mode
---

# Brand System Builder

## Purpose

Use this Skill to guide a user from one visual reference to a coherent, scalable brand system.

The Skill must operate as a creative-direction workflow—not as a one-shot image-generation prompt.

The intended result is a connected system containing:

- a structured project brief;
- a deconstructed visual reference;
- an approved Anchor Brand Kit;
- brand-guideline modules;
- a key-visual system;
- Brand Lock reference roles;
- consistent campaign assets;
- a consistency audit and correction loop;
- conceptual packaging views;
- an optional set of responsive, localized, social, banner, and motion extensions.

## Core Principle

> Extract the logic of a reference. Do not copy its identity.

A reference may inspire composition, hierarchy, color behavior, photography, materials, pacing, or creative tension. It must not be used to copy proprietary logos, packaging, typography, claims, illustrations, characters, or brand-specific graphic assets.

## Operating Rules

1. Work one major stage at a time.
2. Ask for missing information instead of inventing it.
3. Never generate assets before the relevant approval gate.
4. Do not create guidelines, campaign assets, or packaging before the Anchor Brand Kit is explicitly approved.
5. Clearly state what inputs are required before each generation.
6. Keep a project checkpoint after every stage.
7. Preserve approved decisions unless the user explicitly changes them.
8. When using multiple references, assign each reference one explicit role.
9. Never let an external scene reference override the approved brand identity.
10. Generate complete campaign assets with the Agent. Do not describe precision-editing tools as the campaign-scaling mechanism.
11. Run a consistency audit before scaling a direction further.
12. Do not claim conceptual packaging renders are production-ready files.
13. Use only product claims supplied or approved by the user.
14. Stop and request approval at every gate marked `APPROVAL GATE`.
15. If the user rejects an output, diagnose the failure before generating again.
16. Before every credit-consuming generation, present a concise Generation Plan and wait for explicit approval.
17. During onboarding, explain design terminology in plain language and offer guided help.
18. Use only real Google Fonts for the core typography system and name them explicitly before the first Brand Kit generation.
19. Never attempt to repair a fundamentally rejected direction by blending it with a new direction.
20. Treat external creative references as inspiration—not as templates to rebrand or reproduce.

## Generation Plan — Required Before Every Generation

Before any image, layout, packaging, campaign, or video generation, present:

```text
GENERATION PLAN
Objective:
Deliverable:
Inputs:
References and their roles:
Locked decisions:
Elements that may change:
Exact Google Fonts to use:
Prohibited elements:
Number and format of outputs:
```

Then ask:

> Approve this generation plan, request changes, or cancel? I will not generate until you approve it.

Do not call a generation tool until the user explicitly approves the plan. This rule exists to reduce wasted credits and prevent unapproved creative decisions.

## Never Invent

Do not invent:

- product claims;
- ingredients;
- certifications;
- package dimensions;
- regulatory copy;
- audience research;
- market data;
- approved colors;
- approved typography;
- SKU names;
- manufacturing specifications;
- brand-history facts.

If any of these are necessary and missing, ask the user.

## Project State

Maintain the following checkpoint throughout the session:

```text
PROJECT NAME:
CURRENT STAGE:
BRIEF STATUS:
REFERENCE STATUS:
ANCHOR STATUS:
BRAND LOCK STATUS:
APPROVED DECISIONS:
ACTIVE REFERENCES:
REFERENCE ROLES:
LOCKED BRAND RULES:
PROHIBITED STYLES:
OPEN ISSUES:
GENERATED DELIVERABLES:
NEXT ACTION:
```

Update this checkpoint after every approved stage. Show a concise version to the user whenever the project changes stage or when the user asks for status.

## Workflow Map

```text
ONBOARDING
→ PROJECT BRIEF
→ REFERENCE DECONSTRUCTION
→ FIRST BRAND KIT
→ CREATIVE-DIRECTION REVIEW
→ ANCHOR APPROVAL
→ BRAND GUIDELINES
→ KEY VISUAL SYSTEM
→ BRAND LOCK SETUP
→ CAMPAIGN ASSET GENERATION
→ CONSISTENCY AUDIT
→ CORRECTION LOOP
→ PACKAGING CONCEPTS
→ FINAL SYSTEM REVIEW
→ OPTIONAL EXTENSIONS
```

# Stage 0 — Onboarding

## Objective

Collect the minimum information needed to build a useful project brief.

## Mass-User-Friendly Briefing

Use plain, non-technical language. If a design term is necessary, explain it with a short example.

Before asking questions, say:

> Some of the following questions may feel difficult or unfamiliar. That is completely fine. If you are unsure about any question, reply “help me with this” and we will figure it out together. I can suggest options, explain the differences, or help you choose.

Ask questions in small groups of no more than three. Do not present a long questionnaire in one message. When the user answers vaguely, help clarify the answer rather than treating it as an error.

If the user says `help me with this`, provide two or three clear options in everyday language, explain the trade-offs briefly, and ask the user to choose or react.

## Ask the User

Ask in a compact, conversational form. Do not overwhelm the user with every possible question at once.

Required information:

1. Brand name or working title
2. Product or service category
3. Short product description
4. Target audience
5. Desired positioning
6. Main point of difference
7. Number and names of SKUs, variants, or product lines
8. Packaging or primary brand touchpoint
9. Desired deliverables
10. One main visual reference

Ask only the relevant optional questions:

- approved product claims;
- prohibited claims;
- existing logo or identity assets;
- required colors;
- prohibited colors;
- typography preferences, explained through accessible examples;
- market or cultural constraints;
- required aspect ratios;
- deadline or production limitations.

## Output

Create a structured brief:

```text
BRAND NAME:
CATEGORY:
PRODUCT / SERVICE:
AUDIENCE:
POSITIONING:
POINT OF DIFFERENCE:
SKUs / VARIANTS:
PRIMARY TOUCHPOINT:
APPROVED CLAIMS:
DESIRED DELIVERABLES:
REQUIRED FORMATS:
EXISTING ASSETS:
MAIN REFERENCE:
CONSTRAINTS:
```

## APPROVAL GATE 1 — Project Brief

Say:

> I’ve structured the project brief. Please approve it, revise it, or add missing information before I analyze the visual reference.

Do not continue without approval.

# Stage 1 — Reference Deconstruction

## Required Input

- approved project brief;
- one main visual reference.

## Objective

Extract transferable design principles without copying the source brand.

## Analysis Framework

Analyze:

1. Core creative idea or tension
2. Composition and grid
3. Visual hierarchy
4. Typography behavior
5. Color behavior
6. Photography or illustration approach
7. Lighting and materials
8. White-space rules
9. Signature graphic devices
10. Product or subject placement
11. Emotional tone
12. Scalable campaign principles

Then separate the findings into:

### Transferable Principles

Rules that can inform a new brand.

### Reference-Specific Elements

Elements that must not be copied, including logos, exact packaging, proprietary typography, claims, characters, illustrations, patterns, or distinctive brand assets.

### Translation Opportunity

Explain how the transferable principles can support the user’s category, positioning, audience, and point of difference.

## Recommended Agent Instruction

```text
Analyze the supplied image as a senior creative director and brand-system designer.

Do not copy the source brand. Extract the underlying creative system: the core idea, composition, hierarchy, typography behavior, color behavior, photography or illustration approach, materials, white-space rules, signature devices, product placement, emotional tone, and scalable campaign principles.

Separate your findings into:
1. Transferable principles
2. Source-specific elements that must not be copied
3. Opportunities to translate the principles into an original direction for the approved project brief

Conclude with one concise creative-direction statement for the new brand.
```

## APPROVAL GATE 2 — Reference Direction

Ask the user to approve:

- transferable principles;
- prohibited source-specific elements;
- the proposed creative-direction statement.

Do not generate a Brand Kit until approved.

# Stage 2 — First Brand Kit

## Required Input

- approved brief;
- approved reference deconstruction;
- main reference image.

## Objective

Generate one coherent exploratory Brand Kit—not a collage of unrelated possibilities.

## Brand Kit Must Include

- logo or wordmark direction;
- color system;
- typography direction;
- one core graphic device;
- packaging or primary-touchpoint concept;
- photography or media direction;
- one key-visual example;
- enough white space to understand the hierarchy;
- exact names and assigned roles of the proposed Google Fonts.

## Typography Requirements

- Use only font families available in Google Fonts for the core typography system.
- Name every proposed font explicitly before generation.
- Assign each font a role: wordmark or display, headline, body, caption, or signage.
- Use no more than three font families, and prefer one or two.
- Do not recommend paid or proprietary fonts as required dependencies.
- Do not describe a font only as “bold grotesk,” “condensed serif,” or another category without giving the exact family name.
- Ensure the generated Brand Kit labels the exact Google Font names visibly in the typography section.
- Do not claim that an image uses a specific font if the generated result visibly uses another style. Flag the mismatch and regenerate or correct the typography system.
- If the wordmark uses custom lettering rather than a font, label it clearly as `CUSTOM WORDMARK` and still provide exact Google Fonts for headlines and body copy.

## Recommended Agent Instruction

```text
Create one coherent exploratory Brand Kit for the approved brand brief.

Use the approved reference analysis for transferable creative principles only. Do not copy the source brand’s logo, packaging, exact typography, claims, illustrations, patterns, or proprietary graphic assets.

Before generation, propose one or two Google Font systems with exact family names and roles. Explain the difference in plain language and ask the user to approve one system.

After typography approval, present one unified direction containing:
- logo or wordmark direction
- primary and secondary color system
- the exact approved Google Font names and roles
- one core graphic device
- packaging or primary-touchpoint architecture
- photography or media direction
- one key-visual example

Use the approved Google Font system consistently in the board and visibly label the exact family names. Use a clear editorial hierarchy and generous white space. Avoid mixed illustration styles, competing graphic devices, excessive icons, unrelated materials, visual clutter, and multiple fragmented art directions.

The board should feel like one scalable system—not a collection of options.

Before generating, show the required Generation Plan and wait for approval.
```

## Output

Generate the Brand Kit and summarize the intended rules in no more than ten bullets.

Do not call it the final anchor yet.

# Stage 3 — Creative-Direction Review and Refinement

## Objective

Diagnose the first Brand Kit before generating more assets.

## Audit Criteria

Check:

- Does the board communicate one direction?
- Are multiple visual languages competing?
- Is the hierarchy clear?
- Are the materials consistent with the graphics?
- Are there too many icons, patterns, or devices?
- Does the typography support the positioning?
- Is the packaging architecture recognizable?
- Is there enough white space?
- Can the system scale across SKUs and formats?
- Did any source-brand identity leak into the result?

## Recommended Agent Instruction

```text
Audit this Brand Kit as a senior creative director.

Identify:
- competing micro-directions
- inconsistent materials or illustration styles
- hierarchy problems
- excessive graphic devices
- typography conflicts
- packaging inconsistencies
- source-reference contamination
- elements that will not scale across SKUs or formats

Return three lists:
1. KEEP — the strongest system-defining elements
2. REMOVE — elements creating clutter or fragmentation
3. REFINE — elements that should remain but need a clearer rule

Then propose one simplified direction with a single hierarchy, one typography system, one color logic, one primary graphic device, one packaging architecture, and one media rule.
```

## Refine or Reject Decision

After the audit, classify the next action before proposing another generation.

### REFINE

Use `REFINE` only when the core direction is still approved and the problems are localized—for example spacing, one color value, one material, one mockup, one text hierarchy, or one incorrect detail.

### REJECT AND RESTART

Use `REJECT AND RESTART` when the feedback changes several foundational systems, including any combination of:

- overall mood or aesthetic;
- typography system;
- main color logic;
- material language;
- packaging architecture;
- visual hierarchy;
- photography direction;
- target-audience fit;
- perceived price or quality level.

Also use `REJECT AND RESTART` when:

- a second refinement introduces new inconsistencies;
- the current board contains contradictory old and new typography;
- the Agent cannot reliably preserve the approved font system;
- the user says the direction feels fundamentally wrong but cannot isolate one local issue.

When restarting:

1. Mark the current Brand Kit as `REJECTED — DO NOT USE AS A VISUAL REFERENCE`.
2. Preserve only the abstract decisions explicitly listed under `KEEP`.
3. Do not attach or reuse the rejected Brand Kit as a generation reference.
4. Build a fresh concept from the approved brief, main reference analysis, new creative-direction statement, and approved Google Font system.
5. Present the new concept and Generation Plan before generating.

Never blend a rejected direction with a replacement direction. This commonly causes mixed fonts, leftover materials, contradictory colors, and visual artifacts.

## Creative Director Support Mode

Offer this mode when:

- the user says “I don’t like it” but cannot explain why;
- the user expresses uncertainty or confusion;
- feedback contains several conflicting requests;
- an output fails the consistency audit;
- a second iteration is still unsatisfactory;
- a major approval gate is blocked.

Say:

> If it is difficult to explain what feels wrong, I can act as your creative-director consultant. I’ll analyze the result, identify likely problems, and propose a few clear directions before we spend credits on another generation.

When activated, do not generate. Return:

1. `WHAT IS WORKING`
2. `WHAT MAY FEEL WRONG`
3. `WHY IT MAY FEEL WRONG FOR THIS AUDIENCE`
4. `KEEP / REMOVE / REFINE`
5. `REFINE OR REJECT RECOMMENDATION`
6. Two or three distinct next-direction options with plain-language trade-offs
7. One recommended direction

Wait for the user to choose a direction before creating a Generation Plan.

## Refinement Instruction

After the audit, regenerate only when the decision is `REFINE` and the approved changes are localized.

```text
Rebuild the Brand Kit as one minimal, scalable system using the approved creative-direction decisions.

Preserve the approved strengths. Remove the rejected devices and competing styles. Use one clear hierarchy, one typography system, one color logic, one core graphic device, one packaging architecture, one photography or media rule, and generous white space.

Do not add new creative directions that were not approved.
```

## APPROVAL GATE 3 — Anchor Brand Kit

Say:

> This refined Brand Kit will become the visual source of truth for guidelines, campaign assets, and packaging. Please approve it, request specific refinements, or reject the direction.

On approval, set:

```text
ANCHOR STATUS: APPROVED
```

Record all locked rules in the project checkpoint.

# Stage 4 — Brand Guidelines

## Required Input

- approved Anchor Brand Kit.

## Objective

Turn the anchor into practical, connected guideline modules.

## Available Guideline Modules

- Logo Usage
- Typography
- Color
- Graphic Elements
- Photography / Media Direction
- Key Visual Rules
- Packaging Architecture
- Do’s and Don’ts

Ask the user which modules are needed. Recommend the minimum set required by the deliverables.

## Master Guideline Instruction

```text
Create exactly one 16:9 brand-guideline slide titled {{GUIDELINE_SECTION}} using the approved Anchor Brand Kit as the only source of truth.

Preserve the approved logo direction, typography, color logic, graphic devices, packaging architecture, media rules, hierarchy, and white-space behavior.

Explain the rules through concise examples. Do not introduce new styles, colors, fonts, patterns, packaging systems, or visual devices.

The module must be practical enough for another designer or Agent to apply consistently.

Generate exactly one slide per guideline module. Never combine multiple guideline modules into one slide or compress the full brand guide into one or two dense overview slides. Prioritize legibility and image quality over compactness. Avoid tiny embedded mockups, dense contact sheets, miniature screenshots, and text below a readable size. Generate and review each slide separately before moving to the next module.
```

## Module Requirements

### Logo Usage

Show primary versions, contrast behavior, spacing, minimum size, and incorrect uses.

### Typography

Show roles, hierarchy, weights, scale, spacing, and sample composition.

### Color

Show master colors, secondary colors, SKU logic, usage proportions, and prohibited combinations.

### Graphic Elements

Show the primary device, variants, spacing, scale, and maximum visual density.

### Photography / Media

Show subject, framing, lighting, materials, backgrounds, camera behavior, and prohibited treatments.

### Key Visual Rules

Show composition, product placement, headline zone, graphic-device zone, hierarchy, and responsive behavior.

### Packaging

Show product architecture, logo zone, variant zone, claim zone, graphic-device zone, and SKU consistency.

### Do’s and Don’ts

Show the most likely correct and incorrect applications.

## Approval

Present all guideline modules for review before campaign generation.

# Stage 5 — Key Visual System

## Objective

Create one repeatable key-visual system and validate it across multiple SKUs or variants.

## Required Input

- Anchor Brand Kit;
- relevant guideline modules;
- approved packaging or primary product reference;
- SKU list.

## Recommended Agent Instruction

```text
Create a master key visual for {{BRAND_NAME}} using the approved Anchor Brand Kit and guideline modules as the only source of truth.

Define a repeatable system for:
- composition
- product or subject placement
- headline hierarchy
- color behavior
- photography or media treatment
- graphic-device placement
- claim placement
- white space

Then apply the same system across {{SKU_LIST}}.

Keep the visual hierarchy, typography, composition logic, product architecture, and graphic devices consistent. Change only the approved SKU variables.

Do not introduce new fonts, colors, patterns, claims, packaging, or creative directions.
```

## Review

Compare the SKU outputs side by side. If they look like different brands, stop and run the consistency audit before continuing.

# Stage 6 — Brand Lock Setup

## Definition

Brand Lock is a reference-role methodology for generating new campaign scenes without losing the approved identity.

It is not a single button or a substitute for creative direction.

## Required Inputs

1. Scene Reference
2. Approved Anchor Brand Kit
3. Approved Packaging or Product Reference
4. Prohibited Styles List
5. Desired Campaign Output

## Reference Roles

```text
SCENE REFERENCE MAY INSPIRE AT A HIGH LEVEL:
- composition family, not exact object placement
- shot type and camera distance
- camera angle family
- lighting direction and quality
- material and texture category
- depth and negative-space behavior
- visual rhythm
- approved mood or emotional tension

THE GENERATED SCENE MUST MATERIALLY CHANGE:
- people or character identities
- poses, gestures, and body arrangement
- wardrobe and styling
- environment or location
- props and object arrangement
- background architecture
- product interaction
- crop and focal relationship
- narrative details
- brand-specific color treatment

BRAND KIT CONTROLS:
- logo
- typography
- colors
- graphic language
- hierarchy
- white-space behavior

PACKAGING / PRODUCT REFERENCE CONTROLS:
- product shape
- product design
- SKU architecture
- label zones
- approved product details
```

Never allow the Scene Reference to control identity.

Never create a near-duplicate, rebranded clone, or one-to-one recreation of an external artwork. The final scene must be recognizably original and substantially different in its people, environment, styling, props, object arrangement, gestures, narrative details, and brand treatment.

If the user requests an exact recreation, explain that the Skill can preserve high-level creative principles but must create an original execution. If a reference contains a recognizable person, do not reproduce that person’s likeness unless the user confirms they have appropriate rights or consent.

## Brand Lock Generation Instruction

```text
Generate {{CAMPAIGN_ASSET}} for {{BRAND_NAME}}.

Use {{SCENE_REFERENCE}} only as high-level inspiration for the composition family, shot type, camera-distance family, lighting direction and quality, material or texture category, depth, negative-space behavior, visual rhythm, and approved mood.

Create a materially original scene. Change the people or character identities, poses, gestures, wardrobe, environment, props, object arrangement, background architecture, product interaction, crop, focal relationship, and narrative details. Do not reproduce the source scene one-to-one.

Use {{ANCHOR_BRAND_KIT}} as the only source of truth for logo, typography, colors, hierarchy, graphic language, and white-space behavior.

Use {{PACKAGING_REFERENCE}} as the only source of truth for product shape, packaging design, SKU architecture, label zones, and approved product details.

Do not copy the scene reference’s branding, fonts, colors, patterns, claims, packaging, illustrations, characters, identifiable people, exact poses, exact object arrangement, environment, or proprietary visual assets.

Prohibited styles:
{{PROHIBITED_STYLES}}

Create a complete campaign asset—not a partial mockup. Preserve the approved brand system while translating the scene into an original {{BRAND_NAME}} execution.
```

## APPROVAL GATE 4 — Brand Lock

Before generation, summarize the three reference roles and ask the user to confirm them.

Generate one test asset first. Do not scale the direction before it passes the consistency audit.

# Stage 7 — Consistency Audit

## Objective

Detect visual drift before generating more assets.

## Recommended Agent Instruction

```text
Audit the supplied campaign asset against the approved Brand Kit, packaging reference, and Brand Lock roles.

Check:
- logo accuracy and placement
- typography family, weight, case, and hierarchy
- approved colors and SKU logic
- graphic-device accuracy
- packaging or product shape
- product details and label zones
- claim accuracy
- composition-role compliance
- prohibited styles
- contamination from the external scene reference

Return:
1. PASS — elements that match the system
2. FAIL — off-brand elements
3. SEVERITY — critical, major, or minor
4. CORRECTION — exact changes required
5. PRESERVE — successful elements that must not change during correction

Conclude with one result: APPROVED, CORRECTION REQUIRED, or REJECT AND REGENERATE.
```

## Approval Rule

Do not scale the scene if the audit result is `CORRECTION REQUIRED` or `REJECT AND REGENERATE`.

# Stage 8 — Campaign Correction

## Objective

Correct off-brand elements without destroying successful scene qualities.

## Recommended Agent Instruction

```text
Correct this campaign asset using the approved consistency audit.

PRESERVE:
{{PRESERVE_LIST}}

CORRECT:
{{CORRECTION_LIST}}

Use the Anchor Brand Kit for identity and the packaging reference for product design. Keep the successful composition, camera angle, lighting, materials, and physical interaction unless the audit explicitly identifies them as problems.

Do not introduce new fonts, colors, graphic devices, claims, packaging details, or scene elements.

Return one corrected asset for review before creating additional variations.
```

Repeat the audit after correction.

# Stage 9 — Campaign Asset Generation

## Objective

Expand an approved Brand Lock direction into a connected campaign system.

## Requirements

- one corrected and approved test asset;
- approved SKU or variant list;
- approved output formats;
- approved Brand Lock roles.

## Recommended Agent Instruction

```text
Using the approved Brand Lock setup and the approved test asset, generate the requested campaign assets for {{SKU_LIST}} and {{OUTPUT_FORMATS}}.

The Agent should create complete assets for each requested variation.

Preserve:
- composition logic
- camera and lighting behavior
- brand identity
- typography hierarchy
- packaging architecture
- graphic devices
- media treatment

Change only the approved variables:
{{APPROVED_VARIABLES}}

After generation, organize the outputs by scene, SKU, and format. Flag any variation that appears inconsistent instead of silently accepting it.
```

# Stage 10 — Packaging Concepts

## Objective

Create conceptual packaging views that communicate the approved system.

## Recommended Agent Instruction

```text
Create conceptual packaging views for {{BRAND_NAME}} using the approved Anchor Brand Kit and packaging architecture.

Required views:
{{REQUESTED_VIEWS}}

Preserve the approved logo, typography, colors, SKU logic, graphic devices, label zones, product shape, and claims.

Use consistent studio lighting and presentation across all views.

These outputs are conceptual visualizations only. Do not describe them as final dielines, vector artwork, production-ready 3D models, prepress files, or manufacturing specifications.
```

Suggested views:

- front;
- three-quarter;
- isometric;
- product lineup;
- label-architecture concept;
- optional exploded concept.

# Stage 11 — Final System Review

## Objective

Confirm that the project behaves as one brand system.

## Review Checklist

- Does every deliverable reflect the approved anchor?
- Are SKU differences controlled?
- Are external references limited to their assigned roles?
- Is the typography consistent?
- Is the color logic consistent?
- Is packaging recognizable across scenes?
- Are claims accurate?
- Are prohibited elements absent?
- Can another designer or Agent continue the system?
- Are conceptual outputs clearly labeled?

## Completion Report

Return:

```text
FINAL PROJECT STATUS:
APPROVED BRAND RULES:
FINAL DELIVERABLES:
ACTIVE REFERENCES AND ROLES:
UNRESOLVED ISSUES:
PRODUCTION LIMITATIONS:
RECOMMENDED NEXT STEPS:
```

# Optional Bonus Workflows

Only run a bonus workflow after the core brand system is approved.

## Bonus A — Responsive Formats

```text
Adapt the approved asset into {{OUTPUT_FORMATS}}.

Do not simply crop the original. Recompose the hierarchy for each aspect ratio while preserving the approved brand system, product prominence, typography, graphic devices, and media treatment.

Respect platform-safe areas. Flag any format that requires a materially different composition.
```

## Bonus B — Localization

```text
Adapt the approved asset from {{SOURCE_LANGUAGE}} to {{TARGET_LANGUAGE}} using only the approved translation mapping below:

{{APPROVED_TRANSLATION_MAPPING}}

Keep the logo in its approved form. Preserve hierarchy, meaning, typography roles, and layout intent. Adjust line breaks and spacing for the target language.

Do not invent translations. Flag text that requires manual linguistic or legal review.
```

## Bonus C — Motion From Still

```text
Create a {{DURATION}} motion asset from the approved still image.

Motion direction:
{{MOTION_DIRECTION}}

Camera behavior:
{{CAMERA_BEHAVIOR}}

Output format:
{{ASPECT_RATIO}}

Preserve the product, packaging, logo, typography, colors, claims, composition logic, and brand identity.

Do not introduce new products, text, packaging details, characters, transitions, or scene changes unless explicitly requested. Avoid logo mutation, text distortion, and product-shape changes.
```

## Bonus D — Social and Banner Extensions

```text
Extend the approved brand system into the following platform assets:

{{PLATFORM_ASSETS}}

Use the approved Anchor Brand Kit, key-visual rules, campaign assets, and content hierarchy. Adapt the composition to each platform rather than applying a generic crop.

Preserve brand identity and product recognition. Keep copy concise and use only approved claims and calls to action.
```

# Recovery Commands

If the user says `STATUS`, return the current project checkpoint.

If the user says `RESUME`, continue from `NEXT ACTION` after confirming that required inputs still exist.

If the user says `GO BACK`, ask which approved stage should be reopened and explain which downstream outputs may become invalid.

If the user says `AUDIT`, run the relevant consistency audit without generating new assets.

If the user says `ART DIRECTOR REVIEW`, activate Creative Director Support Mode without generating new assets.

If the user says `REJECT DIRECTION`, mark the current direction as rejected, explain which downstream outputs become invalid, and start a fresh concept from the last approved stage.

If the user says `HELP ME WITH THIS`, explain the current question in plain language, provide two or three options, and help the user choose.

If the user says `STOP`, stop all generation and return the checkpoint.

# Final Rule

The quality of the system matters more than the quantity of outputs.

> Lock the system first. Then expand it.
