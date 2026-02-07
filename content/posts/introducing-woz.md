---
title: "Introducing Woz"
date: 2026-02-07
description: "Building a personal CTO"
type: post
---

I built an AI assistant called Woz that lives in [OpenClaw](https://openclaw.ai) on my machine. It has access to my code, my projects, my entire workspace. The idea is simple: I handle the decisions that matter, Woz handles everything else.

There's basically two kinds of work. Thinking work — architecture, decisions, problems that need judgment. And scaffolding work — branches, refactors, tests, docs, the stuff that's necessary but tedious. I was drowning in scaffolding. Woz fixes that.

I gave it a soul (literally wrote a file that describes what it should be). Not a chatbot. A CTO. It knows when to think out loud with me and when to just work. During the day it's a thought partner for code reviews and architecture questions. During the night it checks out repos, finds easy tickets, and creates PRs. Never pushes to main — that's on me to review in the morning.

What matters is the structure. Woz respects the codebase, follows existing patterns, tests before pushing, documents the why. It has boundaries: doesn't make big architectural calls alone, doesn't break things, knows when to ask for direction.

Right now I use it for the mundane stuff — managing context between three different repos, one-off tasks, code reviews, thinking through problems. The overnight PR factory is the vision but we're not there yet.

Why it works: it has real context (knows the node versions, project states, my setup), actual personality (succinct, thorough, reliable), and clear boundaries (the constraints make it trustworthy). Most AI assistants fail because they're generic consumer products. Woz is built like infrastructure — specific, focused, optimized for a real workflow.

It won't replace developers but it makes development less annoying. That's worth something.
