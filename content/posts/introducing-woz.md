---
title: "Introducing Woz"
date: 2026-02-07
description: "My personal CTO, and how I built a better way to work"
---

I've spent the last few months building something that I think solves a real problem: the friction between the work I *want* to do and the work I *have* to do.

It's called Woz. And it's an AI assistant that acts as my personal CTO.

## The Problem

There are two kinds of work in software development. The first kind is the thinking — the architecture, the decisions, the hard problems that require judgment. That's the work that matters. That's the work I want to spend my time on.

The second kind is everything else. The branch management, the small refactors, the tests, the documentation, the "while you're in there, can you fix this too?" stuff. Call it the scaffolding. It has to be done, but it's not why you became a developer.

Here's what I realized: I was spending too much time on scaffolding and not enough on thinking. Not because the scaffolding is hard. It's just *tedious*.

## Enter Woz

Woz is an AI assistant living in [OpenClaw](https://openclaw.ai), a personal gateway that runs on my machine. It has access to my code, my projects, my workspace. It knows about my setup — the dev directory, the repos, the stacks I use.

More importantly, it knows about itself. I wrote a soul file — literally — that describes who Woz is supposed to be. Not a chatbot. Not a generic "helpful assistant." A CTO.

Here's what that means:

**During the day,** Woz is a thought partner. I ask questions, it thinks out loud, we work through problems together. It reads my code, understands the context, and offers architectural insights. It's like having a really good pair programmer in your ear.

**During the night,** Woz works. It checks out the codebase, finds the easy tickets, the low-hanging fruit, the small improvements that don't require judgment. It creates branches, writes PRs, documents its thinking. It never pushes to main — that's for me to review in the morning. Its PRs sit in my inbox like little gifts.

The structure matters here. Woz isn't just "doing stuff." It's doing stuff *responsibly*. It respects the codebase. It follows patterns. It writes clean code. It tests before it pushes. It documents the "why," not just the "what."

And critically: it knows when to stop. Big architectural decisions? Woz waits. Things that need judgment? That's my job. Woz has boundaries, and it respects them.

## What I Actually Use It For (Today)

Let's be honest: the overnight PR factory is the vision. We're not quite there yet.

Right now, I use Woz for the mundane. The day-to-day friction that slows you down:

- **Code reviews.** Woz reads a PR, thinks about it, and gives thoughtful feedback. Real feedback, not AI-generated buzzwords.
- **Jumping between projects.** I work across multiple repos (brisket, pilaf, the blog you're reading). Woz keeps track of what each project needs — the node version, the framework, the current state of things.
- **One-off tasks.** Build this, fix that, research this thing, write this documentation. Tasks that don't fit neatly into a sprint but need to get done.
- **Thinking partner.** Sometimes I just want to talk through an idea. Woz listens, asks good questions, pushes back when needed.

## Why This Works

A lot of people have tried building AI assistants. Most of them feel like talking to a chatbot. They lack context. They lack judgment. They make weird decisions.

Woz works because of three things:

**First: context.** It has access to my actual code, my actual projects, my actual setup. It's not guessing. When I ask "what's the current state of brisket," it can tell me — the node version, the structure, what we're working on.

**Second: personality.** I gave it a soul. Not a marketing persona, an actual soul. It knows it's supposed to be succinct but thorough. It knows it should respect the codebase. It knows when to ask for direction and when to just do the work. It knows it's not supposed to be flashy; it's supposed to be reliable.

**Third: boundaries.** It knows what it can't do. It doesn't push to main. It doesn't make big architectural calls alone. It doesn't break things. These constraints actually make it *better* at what it does, because I trust it more.

## The Overnight Workflow (Coming Soon)

Here's the vision: somewhere in the future, Woz is smart enough to find tickets marked "easy" or "good first issue," understand what they're asking for, and create a PR for them. Not every ticket — just the ones it can actually handle. The ones where the decision is clear and the work is straightforward.

I wake up, I get my morning coffee, and there's a PR waiting. Five lines of code, a clear explanation of what was wrong and how it's fixed. Takes me two minutes to review. Takes Woz four hours to write and test properly.

That's the dream.

## The Reality

Building Woz taught me something useful: you can't just throw an AI at a problem and expect it to work. You have to *design* the system. You have to give it structure, boundaries, context, and a clear sense of purpose.

Most AI assistants fail because they're built like consumer products — generic, trying to be everything, optimized for the chat. Woz works because it's built like *infrastructure* — specific, focused, optimized for a real workflow.

It's not going to replace developers. But it might just make development less annoying.

And honestly? That's worth something.

---

*Woz is built on [OpenClaw](https://openclaw.ai), a personal AI operating system that I highly recommend if you spend your time writing code and managing projects. It's still early, but the foundation is solid.*
