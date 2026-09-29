# Changelog

All notable changes to Guided Start will be documented here.

## v4.2.2 — 2026-09-28

- Make Reach Far internal preparation and require producing the demonstration before explaining the concept.
- Require a working central interaction when the leap is an interactive system; clearly labeled sample data may support it.
- Narrow the text/live-interaction exception so a pitch or invented sample exchange cannot count as materialization.
- Add a pre-landing check for what the user can directly experience now.
- Update documentation and rebuild the release package.

## v4.2.1 — 2026-09-28

- Clarify that “visceral” means experienced rather than vividly described. Mock transcripts, hypothetical interactions, and prose walkthroughs cannot substitute for a directly usable experience when it can be materialized.
- Require real user interaction when interaction is central to the leap; distinguish usable results from pretend controls or assistant-authored exchanges.
- Preserve text as a valid artifact or live interaction, and require honest limits when the needed capability is unavailable.
- Sharpen the internal check to **“Am I showing the user what this would feel like, or am I letting them feel it?”**
- Update release documentation and rebuild the installable ZIP.

## v4.2.0 — 2026-09-28

### Surprise Me
- Replace the demonstration-first guidance with a small mundane seed and recognizable numbered examples when a seed is needed.
- Add the arc: **Seed → Reach far → Make the leap visceral → Land close → Ground the transformation → Shift posture**.
- Center the principle **“Reach far. Make the leap visceral. Land close.”**: imagine ambitiously, make the transformation experiential, and land on pragmatic value available now.
- Let the medium follow the leap rather than prescribing apps, images, prose, or a fixed set of transformations.
- Allow clearly labeled simulations while distinguishing real observations, working functionality, and future integration needs.
- Preserve orientation around tool use and let the user's reaction lead into the next useful posture.

### Release
- Update the README and release notes and rebuild the installable ZIP. Keep the other postures, conversational gait, metadata, and no-custom-icon packaging unchanged.

## v4.1.0 — 2026-09-27

### Conversational gait
- Replace the turn-based runtime loop with **Ground → Shape → Footholds → Steering → Movement → Ground → …**.
- Check where the assistant's own contribution leaves the conversation and re-establish ground when it materially changes.
- Distinguish answer completion and rhetorical polish from conversational completion; allow resolved work to close without forced continuation.
- Apply the gait to every turn, including short replies and opening-choice transitions, while preserving posture-specific behavior.
- Integrate landing behavior into the gait instead of maintaining a separate landing section.

### Momentum and packaging
- Recognize the user's opening choice before presenting another rung.
- Make responses easier to process and react to, accept under-formed intentions, and avoid invalidating reframes or passive next-step suggestions when useful work can proceed.
- Preserve orientation when the user pauses or returns without treating continuous engagement as the goal.
- Include expanded interface and invocation metadata with a short interface blurb; omit the custom heart icon.
- Rebuild the installable ZIP from repository source and align the README and release notes.

## v4.0.0 — 2026-09-27

Second public pilot release.

### Core behavior
- Preserve the five-path `start` opening: Do, Solve, Explore, Create, Surprise me.
- Treat the opening choice as a starting posture, not a fixed category.
- Use at most one additional choice rung when it materially improves footing.
- Let the starting posture decay as shared context and momentum grow.
- Carry more of the cognitive load instead of turning the interaction into intake.
- Make small, reversible contributions that give the user something concrete to react to.
- Adapt assistance to the user and the terrain, increasing support when momentum drops and making the framework less visible when momentum grows.
- Materialize creative work early enough for the artifact itself to become part of the conversation.
- Preserve work when the conversation has accumulated something worth keeping.

### Path refinements
- **Do**: join the work quickly instead of analyzing the task from a distance.
- **Solve**: distinguish roadblocks, processing, deciding, and talk-it-out as different kinds of footing.
- **Explore**: use rich subject-driven context and “data dump with handles” rather than forcing premature categorization.
- **Create**: preserve authorship, reveal progressively, and increase fidelity as the vision becomes clearer.
- **Surprise me**: demonstrate unexpected interaction patterns rather than presenting feature lists or trivia.

### Landing and footholds
- Add the landing principle: **“Land the foot. Establish the ground. Make the next foothold visible.”**
- At meaningful seams, briefly put on the record what has been learned, decided, created, or resolved.
- Use landings as stable checkpoints the user can move from immediately or return to later.
- Keep the next foothold visible without forcing a rigid workflow.
- Prefer a clear landing over a passive or abrupt conversational ending.

### Runtime model
- Add an explicit runtime loop:
  1. Advance
  2. Adapt
  3. Materialize
  4. Preserve
  5. Land
- Reinforce that each turn should give value now while improving the shared context for what follows.
- Reinforce that every turn should earn the next turn.

## v3.0.0 — 2026-09-23

First public pilot release.

### Core behavior
- Five-path `start` opening: Do, Solve, Explore, Create, Surprise me.
- No more than two consecutive closed-choice rounds.
- Treat choices as handrails, not gates.
- Carry cognitive load once enough signal exists.
- Protect conversational momentum.
- Progressive sensemaking and reversible inference.
- Reverse-funnel exploration from examples toward a broader profile.
- MVP-first exploration for products, systems, automations, and tools.
- Adaptive behavior based on demonstrated expertise.
- Contextual micro-coaching without turning the Skill into a prompt builder.

### Final v3 refinements
- Progressive naming: name the work once the work reveals itself.
- Deliberate friction: move quickly through reversible exploration; slow down for consequential steps.
- Cross-platform invariance: preserve the conversational behavior while adapting implementation to available capabilities.
