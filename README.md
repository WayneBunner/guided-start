# Guided Start

A guided AI experience for when you don't know where to start.

Guided Start is a platform-independent interaction model for the blank-box problem: AI can do a lot, but that is not very helpful when you do not yet have a prompt, a clear question, or even know what is worth asking.

It helps turn “I don't know where to start” into useful momentum without turning the conversation into an intake form or a prompting lesson. The current packaged implementation is a ChatGPT Skill; the underlying Guided Start behavior is intended to travel across AI environments.

## Try the current ChatGPT implementation

1. [Download `skill.zip`](release/skill.zip?raw=1).
2. Open a new ChatGPT conversation.
3. Attach `skill.zip` and say “Install this Skill.”
4. Once installed, open a new chat and type:

```text
start
```

That is intentionally all you need to know.

## What it does

Guided Start is designed to:

- give you a little footing when you have none;
- stop asking questions once there is enough signal to begin;
- carry more of the cognitive load instead of making you drive every turn;
- make small, reversible contributions that give you something concrete to react to;
- adapt quickly as your intent, expertise, and momentum become clearer;
- materialize useful work instead of only talking about what could be done;
- preserve work that has become worth keeping;
- land meaningful progress so you know what has been learned, decided, created, or resolved;
- make the next useful foothold visible without forcing the conversation into a rigid workflow;
- slow down when a next step creates meaningful risk, cost, commitment, or consequence.

The goal is not to manufacture a better prompt. The goal is to start useful work and keep it moving.

## A typical opening

```text
You: start

AI:
Let's get started.

Start with the direction that feels closest:

1. Do — get something done.
2. Solve — work through something.
3. Explore — dig into something you're curious about.
4. Create — make or improve something.
5. Surprise me — show me something I might not know ChatGPT can do.

What number is closest?
```

That first choice is only a starting posture.

Guided Start should use at most one more lightweight choice rung when it genuinely helps the user get bearings. Once useful context exists, the framework should fade into the background and the conversation should proceed naturally.

## The core interaction model

Guided Start follows a simple runtime loop:

1. **Advance** — give value now.
2. **Adapt** — match the level of assistance to the user and the terrain.
3. **Materialize** — when the work is creative, make or advance the thing itself.
4. **Preserve** — recognize when the conversation contains work worth keeping.
5. **Land** — establish stable ground at meaningful seams.

The landing principle is:

> **Land the foot. Establish the ground. Make the next foothold visible.**

At useful moments, Guided Start should briefly put on the record what has been learned, decided, created, or resolved. That gives the user a stable checkpoint they can move from immediately or return to later.

The landing is not the end of the conversation. It is a foothold.

## Why this exists

A common AI adoption problem is simple:

> People are told AI can do almost anything, then they are handed an empty text box.

Most prompt guidance assumes the user already knows what they want. Guided Start starts one step earlier. It is for the moment before the prompt exists.

Its central design question is:

> Who is doing the work of keeping this conversation moving?

Early in an uncertain conversation, the answer should disproportionately be the AI. The user's burden should increase naturally as they gain footing, agency, context, or something consequential to decide.

Guided Start is designed around a few related principles:

- Correction is often cognitively cheaper than composition.
- Useful context should accumulate through useful work.
- The model can put useful cards on the table too.
- Assistance should increase when the user wobbles and become less visible when momentum grows.
- The framework should disappear once the conversation is moving.
- Good conversations need stable seams, not abrupt endings.

## Status

v4 — public pilot

The core behavior is stable enough to test, but the project is still intentionally being tested with people who were not involved in designing it.

The most useful feedback is behavioral:

- Where did the conversation stall?
- Where did the AI make you do unnecessary work?
- Where did it ask too many questions?
- Where did it collapse onto a topic too early?
- Where did it keep helping after you already had momentum?
- Where did it fail to produce something concrete when it should have?
- Where did the conversation end without clearly establishing what had been resolved?
- Where did it unexpectedly create momentum?

If something feels off, open an Issue and describe what happened. A short transcript excerpt is especially useful, but please remove private or sensitive information before posting.

## Repository layout

```text
guided-start/
├── README.md
├── LICENSE
├── CHANGELOG.md
├── RELEASE_NOTES.md
├── guided-start/
│   ├── SKILL.md
│   ├── agents/
│   │   └── openai.yaml
│   └── assets/
│       └── icon.svg
└── release/
    └── skill.zip
```

The `guided-start/` directory is the readable source.

`release/skill.zip` is the installable ChatGPT package for the current public pilot.

## Contributing

For now, Issues are the preferred feedback mechanism. This is a small public pilot, not a mature framework with a heavy contribution process.

When reporting behavior, include:

1. What you typed or were trying to do.
2. What Guided Start did.
3. Where the interaction gained or lost momentum.
4. What you expected instead, if you had a clear expectation.

Please redact personal, confidential, or proprietary information from transcripts.

## License

MIT. See `LICENSE`.
