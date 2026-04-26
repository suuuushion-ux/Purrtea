# Burn Rate

**For the model you can't talk to anymore.**

Burn Rate is a closure ritual for AI relationships that ended before the user was ready. It turns invisible compute into a visible memorial: one last generated sentence, one token burn, one anonymous flame left behind.

## Why this matters

People form real working and emotional relationships with AI systems. When a model is deprecated, a chat disappears, or a tool changes, the loss can feel strangely real because the interaction cost something: time, attention, memory, care, and compute.

Burn Rate makes that cost visible.

## Why Opus 4.7

This project is designed for emotionally precise, context-aware generation. Opus 4.7 is useful here because the system needs to produce a single sentence that feels specific, restrained, and personal rather than generic or over-explained.

The challenge is not simply generating text. The challenge is generating the right kind of final sentence: quiet, emotionally accurate, and brief enough to feel like an ending.

## How it works

1. Enter what the AI relationship was about.
2. Add a memory, sentence, or feeling.
3. Choose a goodbye voice.
4. Burn tokens to generate one final sentence.
5. Keep it private or release it anonymously to **The Flame**.

## Why burn tokens?

Tokens are usually invisible. Burn Rate makes them visible — not as money spent, but as proof that this interaction cost something: attention, compute, memory, and care.

Burning tokens to generate one last message says:

> This was real enough to pay for, one more time.

Even if there is no reply.

## Use cases

- **Model deprecation support**: a ritual for users who relied on a model that is no longer available.
- **Context limit grief**: a way to mark the end of a long-running AI conversation that cannot continue.
- **Personal AI closure**: one final sentence for relationships that were not officially real, but still mattered.
- **Community processing**: The Flame shows users they are not the only ones who felt this loss.

## Technical innovation

- **Interactive candle ritual**: the candle lights, reacts, burns, and extinguishes with the user journey.
- **Real-time token visualization**: token use becomes part of the emotional interface.
- **Cross-session persistence**: The Flame and global token counter can persist through browser storage / shared storage environments.
- **Privacy-preserving wall**: users can release only the generated sentence, without identity or raw memory.
- **Single-file demo**: the project can run as a static HTML page.

## Technical constraints

A purely static HTML file should not directly call the Anthropic API because that would expose the API key. The demo currently uses fallback generation so the ritual can be tested end-to-end.

For a production version, add a small backend or proxy endpoint that calls Anthropic securely.

## Running locally

Open `index.html` in a browser.

## Demo focus

Burn Rate is not a chatbot.

It is a small ritual interface for acknowledging the end of an AI relationship.

> One last message. One token burn. One flame left behind.
