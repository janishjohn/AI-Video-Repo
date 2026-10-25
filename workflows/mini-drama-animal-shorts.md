# AJ-AI Mini-Drama Animal Shorts Workflow

A VideoExpress browser workflow for turning an animal-story idea into a fast, connected vertical Short. It combines the hook-first pacing of [Realistic Mini Dramas](https://github.com/ai-playbooks/realistic-mini-dramas) with this repo's established cinematic, whimsical animal stories and subtle AJ-AI branding.

## Personal defaults

- **Format:** YouTube Shorts, vertical 9:16.
- **Style:** cinematic, whimsical animal-led story.
- **Length:** 30–45 seconds; use 30 seconds for a quick gag and 45 seconds for a fuller emotional turn.
- **Pacing:** open during the most interesting moment; escalate quickly; land one reveal, emotional turn, or punchline near the end.
- **Brand:** include “AJ-AI” only as a subtle, legible environmental detail when it fits naturally. Never obscure the action.
- **Audio:** use narration only when requested or when it clearly improves the story; otherwise let action and suitable sound effects carry it.
- **Cast:** one animal protagonist and at most two supporting characters unless the user asks for more.

Honor explicit user choices over these defaults. Ask only for a missing creative choice that cannot reasonably be inferred. If the topic is open-ended, choose an original, family-friendly premise and proceed.

## Originality and account boundaries

Make original fictional stories. A reference can guide pace, shot energy, or visual mood; do not copy its plot, dialogue, characters, or identifiable likenesses. Preserve user-provided subject references and defining traits.

Use the visible VideoExpress browser session and the controls actually available in the account. Do not use scripts, terminals, downloads, or hidden account data. Never publish to a public gallery unless explicitly requested. Do not accept binding terms, spend money, or change unrelated account settings for the user. If sign-in, terms, payment, or an account-level blocker appears, ask the user to handle that screen.

## Story plan

Before generation, outline the whole short. Keep the plan concise and use the following structure:

1. **Hook (first scene):** start mid-action, with a surprising image, urgent choice, or unanswered question.
2. **Escalation:** each scene adds a new action or piece of information. Avoid repeated approaches or reaction shots that do not move the story.
3. **Turn (around the final third):** reveal why the situation looked different, or change the protagonist's goal.
4. **Payoff:** finish with a clear emotional beat, visual joke, or satisfying resolution. Avoid a slow fade.

For each scene, specify its number, approximate duration, narration/dialogue (if any), incoming pose, one principal action, outgoing pose, props and their exact positions, setting, framing, image prompt, motion prompt, and the handoff to the next scene.

**Shot count guide:** target roughly one scene per 2.5–3.5 seconds. A 30-second short usually needs 9–12 scenes; a 45-second short usually needs 13–18. Adapt to the editor and actual render lengths. Prefer fewer clear beats over filler.

## Character and continuity bible

Write a compact identity line for every recurring character and paste it consistently into prompts. Lock species, size, fur/feather/scale colors, distinctive markings, accessories, and personality. Keep character count manageable.

Track continuity across scenes:

- Starting and ending pose for the protagonist.
- Which paw/hand holds or touches each prop.
- Prop count, owner, and screen position.
- Screen direction, setting landmarks, time of day, and light direction.
- Emotional state and any costume/accessory changes.

Every scene should begin from the planned end state of the previous scene. Change one main story action per scene. Make the animal visibly act; camera motion alone is not an action beat.

## Image prompt recipe

Write a separate image prompt for every scene. Describe the exact story moment, not a poster:

- vertical 9:16 framing unless the user requested another ratio;
- character identity line, expression, pose, and position in frame;
- exact props, their count, contact points, and placement;
- foreground, middle ground, background, and stable landmarks;
- shot size, camera angle, and enough open space for the action;
- time, light direction, colors, shadows, and material texture;
- continuity from the prior scene and setup for the next;
- optional subtle AJ-AI environmental mark, only if it can render cleanly.

Keep prompts concrete and internally consistent. Inspect generated images when visible; correct severe identity, anatomy, count, or staging errors before animating.

## Motion prompt recipe

Give each image its own motion prompt. Describe one continuous beat in present tense:

- opening pose and framing;
- protagonist's principal action and direction;
- camera movement and final framing;
- restrained environmental motion;
- final pose and prop placement that hands off to the next scene.

Preserve the animal's identity, markings, proportions, accessories, and setting. Keep narration/dialogue in dedicated audio controls when available; don't ask the video prompt to create duplicate speech or lip sync.

## Production and render tracking

1. Open VideoExpress and select the project/workflow controls supported by the current account.
2. Generate scenes in story order. Name or label each scene clearly (for example, `S01 — The Missing Acorn`) when the UI supports it.
3. Use the concurrency limit displayed in the account. When the queue is full, wait and inspect existing jobs before retrying.
4. Track each planned scene as queued, rendering, complete, failed, or intentionally omitted.
5. Retry only confirmed failed or clearly unusable scenes, up to three total attempts per scene. Never resubmit a job whose status is uncertain.
6. Preserve completed clips; fix only the specific scene that needs it.
7. If a tool setting differs from these notes, use the closest available control and report meaningful limitations honestly.

## Timeline assembly and export

Do not export until submitted jobs have known outcomes and the timeline is accounted for.

1. Match each completed clip to its scene.
2. Add each usable clip exactly once and in story order. Verify its appearance before adding the next.
3. Compare timeline count with the plan. Account for every missing, duplicate, failed, or omitted scene.
4. Keep narration attached to its intended clip and check for duplicate audio.
5. Use Auto Align or equivalent when available. Check order, gaps, overlaps, durations, and key joins; play the start, important transitions, and ending when practical.
6. Save and confirm the visible save state.
7. Export the requested format and quality. Confirm the export exists and opens when the UI permits.

## Delivery

Report the title, format, scene count, actual runtime when visible, audio choice, save/export state, and whether timeline completeness was checked. Mention any failed scene or check that could not be completed. Never claim a render, timeline review, or export succeeded unless you saw evidence in VideoExpress.

## Copy-ready intake

**Let's make an AJ-AI animal Short.** Tell me the story idea or animal, and optionally the length, visual style, narration choice, or reference image/video. If you leave those open, I'll use the personal defaults above.
