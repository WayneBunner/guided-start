# Guided Start

**A guided AI experience for when you don't know where to start.**

Guided Start is a platform-independent interaction model for the blank-box problem: AI can do a lot, but that is not very helpful when you do not yet have a prompt, a clear question, or even know what is worth asking.

It helps turn **“I don't know where to start”** into useful momentum without turning the conversation into an intake form or a prompting lesson. The current packaged implementation is a ChatGPT Skill; the underlying Guided Start behavior is intended to travel across AI environments.

## Try the current ChatGPT implementation

1. Download `skill.zip` from the latest GitHub Release.
2. Install/upload the Skill in ChatGPT.
3. Open a new chat.
4. Type:

```text
start
```

That is intentionally all you need to know.

## What it does

Guided Start is designed to:

- give you a little footing when you have none;
- stop asking questions once there is enough signal to begin;
- carry more of the cognitive load instead of making you drive every turn;
- make small, reversible inferences and learn from your reactions;
- preserve momentum while the real problem or opportunity emerges;
- slow down when a next step creates meaningful risk, cost, commitment, or consequence;
- adapt quickly as your expertise and intent become clearer.

The goal is not to manufacture a better prompt. The goal is to **start useful work**.

## A typical opening

```text
You: start

AI:
Let's find something worth doing.

You don't need a prompt or even a clear idea yet. We can start with
something you need to get done, a problem that's bugging you, something
you're curious about—or we can just explore what AI can do.

What sounds interesting?

1. Do — knock out something useful.
2. Solve — bring me something messy or frustrating.
3. Explore — follow a curiosity or discover something new.
4. Create — make something and see where it goes.
5. Surprise me — show me something I might not know ChatGPT can do.

Or just type whatever is on your mind.
```

From there, Guided Start should stop behaving like a menu as soon as you have enough footing to converse normally.

## Why this exists

A common AI adoption problem is simple:

> People are told AI can do almost anything, then they are handed an empty text box.

Most prompt guidance assumes the user already knows what they want. Guided Start starts one step earlier. It is for the moment before the prompt exists.

Its central design question is:

> **Who is doing the work of keeping this conversation moving?**

Early in an uncertain conversation, the answer should disproportionately be the AI. The user's burden should increase naturally as they gain footing, agency, or something consequential to decide.

## Status

**v3 — public pilot**

The core behavior is stable enough to test, but this project is intentionally being tested with people who were not involved in designing it.

The most useful feedback is behavioral:

- Where did the conversation stall?
- Where did the AI make you do unnecessary work?
- Where did it ask too many questions?
- Where did it collapse onto a topic too early?
- Where did it unexpectedly create momentum?

If something feels off, open an Issue and describe what happened. A short transcript excerpt is especially useful, but please remove private or sensitive information before posting.

## Repository layout

```text
guided-start/
├── README.md
├── LICENSE
├── CHANGELOG.md
├── guided-start/
│   ├── SKILL.md
│   ├── agents/
│   │   └── openai.yaml
│   └── assets/
│       └── icon.svg
└── release/
    └── skill.zip
```

The `guided-start/` directory is the readable source. `skill.zip` is the installable package intended to be attached to the GitHub Release.

## Contributing

For now, Issues are the preferred feedback mechanism. This is a small public pilot, not a mature framework with a heavy contribution process.

When reporting behavior, include:

1. What you typed or were trying to do.
2. What Guided Start did.
3. Where the interaction gained or lost momentum.
4. What you expected instead, if you had a clear expectation.

Please redact personal, confidential, or proprietary information from transcripts.

## License

MIT. See [LICENSE](LICENSE).
