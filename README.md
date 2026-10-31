# AJ-AI VideoExpress Story Workflows

A personal collection of reusable production prompts for creating vertical videos for Facebook Reels and YouTube Shorts with VideoExpress AI.

These are prompt and production guides. They do not control VideoExpress automatically; use them with a browser-capable agent that can operate VideoExpress.

## Workflows

- [Cinematic animal stories](SYSTEM_PROMPT.md) — whimsical animal-led stories, detailed scene image and motion prompts, 9:16 by default.
- [Stickman couple comedy](workflows/stickman-couple-comedy.md) — original husband-and-wife comic stories, about 30 seconds planned as five roughly six-second clips, with permanent-couple reuse, vertical 9:16.
- [Mini-drama animal Shorts](workflows/mini-drama-animal-shorts.md) — hook-first, fast-paced animal stories with a clear turn and payoff, personalized for the AJ-AI style.

## Playlists

- [AJ-AI Animal Mini-Dramas — Season 1](playlists/aj-ai-animal-mini-dramas-season-1.md) — an eight-episode connected Shorts season following Pip the squirrel through a park rebuilding after a storm.

## Shared cross-platform format

Prepare a shared vertical 9:16 master (1080×1920 MP4 when available), keep key content clear of interface overlays, and use separate platform titles/captions. The default 30–45 second runtime is suitable for cross-posting. See each workflow for upload notes.

## Shared checklist

Use [CHECKLIST.md](CHECKLIST.md) for production, render tracking, and the required timeline and rendered-export QA gate.

## Quick start

1. Open VideoExpress AI and sign in.
2. Choose a workflow above and copy it into your browser-capable agent.
3. Provide your story topic or ask for a fresh one. Include any requested runtime, aspect ratio, narration, and reference images.
4. Let the workflow plan all scenes before rendering.
5. Before export, verify that every intended clip appears exactly once on the timeline.

## Personal defaults

- Format: vertical 9:16 for Facebook Reels and YouTube Shorts; shared master at 1080×1920 MP4 when available.
- Animal workflow: cinematic, whimsical animal mini-stories with optional subtle AJ-AI branding.
- Stickman comedy workflow: affectionate, visually clear couple humor with a fast hook and satisfying punchline.
- Stickman comedy runtime: about 30 seconds planned as five roughly six-second clips; honor explicit requests and measure actual output.
- Rendering: respect the visible account limit. For the stickman workflow, plan five clips and never submit more simultaneous renders than the UI allows.
- Assembly: count, order, and verify every rendered clip on the timeline before export.

Never put passwords, session tokens, API keys, or private account data in this repository.

## Using this repository as your main hub

For a couple comedy, explicitly ask the agent to read [workflows/stickman-couple-comedy.md](workflows/stickman-couple-comedy.md), [characters/permanent-couple.md](characters/permanent-couple.md) and [CHECKLIST.md](CHECKLIST.md). The root SYSTEM_PROMPT.md is the animal workflow, not the couple workflow. Supply your story and the exact approved reference; do not rely on a bare repository link to choose the right workflow.

Start with [this copy-ready couple request](examples/stickman-request.md). A browser-capable agent executes production; these Markdown workflows do not create unattended automation. Login or product restrictions can still require intervention.

The [scene-ledger template](templates/scene-ledger.md) tracks private run state. The [Massage Swap example](examples/massage-swap.md) demonstrates the couple workflow. Keep private IDs and session information out of this public repository.

This repository remains the main collection for animal stories, couple comedy and playlists. The separate videoexpress-stickman-story-agent fork is an optional reference; it is not required to run these workflows. Its unmerged pull request is not automatically synchronized here.

## Permanent couple image

The approved reference is included at [characters/permanent-couple.png](characters/permanent-couple.png). Future couple-video requests can use this file without asking the user to attach it again, provided the agent can retrieve it. Read [the reference procedure](characters/permanent-couple.md), inspect the image and select/upload it into VideoExpress using supported controls. Keep the existing simplified stick-figure style; this reference supplies identity cues.
