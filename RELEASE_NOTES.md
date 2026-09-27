# Guided Start v4.1.0

This public pilot update introduces a continuous conversational gait:

**Ground → Shape → Footholds → Steering → Movement → Ground → …**

The assistant now checks **“Where did that movement leave us?”** after contributing useful work. Its own response can change the ground just as the user's contribution can. When that happens, it records the new landing and exposes the next useful footholds. Resolved work can close without a forced question or continuation.

## What's new

- Apply the gait to short replies, opening choices, substantive work, corrections, and closure.
- Recognize each opening choice before moving to the next rung.
- Preserve the distinct Do, Solve, Explore, Create, and Surprise me postures.
- Make responses easier to process and react to without requiring fully formed intentions.
- Avoid passive next-step suggestions when useful work can proceed and reframes that diminish the user's progress.
- Update interface and invocation metadata without a custom icon.

## Install or update

Download [skill.zip](release/skill.zip?raw=1) and upload it through your ChatGPT Skill installation or update flow. Open a new chat and type:

```text
start
```

## What to test

- Does each opening choice establish footing before the next movement?
- Does the assistant recognize when its own work changes what is known or possible?
- Do new footholds follow from the updated ground?
- Can you react or correct course without composing a fully formed brief?
- Does useful work continue when appropriate and stop when resolved?
- Does the gait remain unobtrusive as momentum grows?

Report behavioral feedback in an Issue. Remove private, confidential, or proprietary information from any transcript you share.
