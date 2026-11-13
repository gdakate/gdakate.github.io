---
layout: page
title: "The Sandbox: Human–AI Deception Arena"
description: Real-time multiplayer game where humans and LLM agents play anonymously; humans spotted AI 73% of the time vs. 40% for AI raters
importance: 2
category: research
---

**CSE 590 Research Project · Stony Brook University · Jan 2026 – May 2026**

`FastAPI` · `WebSocket` · `Multi-Agent LLMs` · `Async Python` · `Evaluation`

**Code:** [github.com/gdakate/The-Sandbox](https://github.com/gdakate/The-Sandbox)

### Problem

As LLM agents show up in group conversations, can people tell which participants are AI, and are AI models any better at it?
Answering that needs a controlled environment where humans and agents play the same game under the same anonymization.

### Approach

- **Game design.** A multiplayer social-deduction game (hints, discussion, voting) where human players and LLM agents share one anonymized lobby.
- **Multi-provider agents.** Integrated Claude, GPT-4o, Gemini, and Llama-family models through Anthropic, Google, and Together APIs behind a common agent interface.
- **Real-time backend.** FastAPI + WebSocket server with async coordination across game phases, so several agents and humans can act in the same round without blocking each other.
- **Logging for research.** Structured JSONL logs of every hint, vote, chat message, and agent reasoning trace, so each game can be replayed and analyzed.

### Results

- In a 5-session pilot, **human players identified AI players 73% of the time**, compared with **40% for AI raters**, a clear human–AI detection asymmetry.
- The logging pipeline made it possible to trace why agents voted the way they did, not just the outcome.

### Takeaways

- Running several LLM providers in one real-time game is as much a systems problem as a modeling one, which is why the async backend came first.
- The pilot is small (5 sessions); the next step is more sessions before making general claims.
