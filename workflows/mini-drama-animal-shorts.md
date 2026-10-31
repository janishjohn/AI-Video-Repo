# AJ-AI Mini-Drama Animal Shorts Workflow

A VideoExpress browser workflow for turning an animal-story idea into a fast, connected vertical video prepared for Facebook Reels and YouTube Shorts. It combines the hook-first pacing of [Realistic Mini Dramas](https://github.com/ai-playbooks/realistic-mini-dramas) with this repo's established cinematic, whimsical animal stories and subtle AJ-AI branding.

## Personal defaults

- **Platforms:** Facebook Reels and YouTube Shorts.
- **Shared master:** vertical 9:16, 1080×1920 MP4 when available.
- **Style:** cinematic, whimsical animal-led story.
- **Length:** 30–45 seconds for easy cross-posting; check current platform limits for longer requests.
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

## Pre-export timeline and rendered-video QA — required gate

Do not treat the editor preview or a successful export click as proof that the final video is correct. Complete and record both checks below before delivery.

### Before exporting: verify the timeline

1. Use the numbered storyboard as the source of truth. Match every timeline clip to its planned scene by visible thumbnail/content and, where available, scene label or job identity; do not rely on creation order, filenames, or memory alone.
2. Read the timeline from first to last and confirm the hook, escalation, turn, and payoff appear in the intended order. Confirm every planned usable scene appears exactly once, with missing, failed, omitted, or duplicate scenes accounted for.
3. Check clip boundaries and durations. Use Auto Align or the closest available timing control, then inspect again: look for unintended gaps, overlaps, blank/black frames, frozen holds, repeated footage, abrupt jumps, and cut-off action/audio. Remove unwanted waiting time between clips; keep a pause only when it is an intentional story beat.
4. Play from the beginning through the full timeline when practical. At minimum, inspect the opening, each important join/transition, the turn, and the ending; compare what appears on screen with the storyboard and adjacent scene handoffs.
5. Confirm audio is attached to the intended scene, has no accidental duplicate, and is not cut off. Save and verify the visible saved state.

### After exporting: verify the rendered file

1. Wait for the export to finish. Open the newly created output itself, not just the editor preview; confirm it opens and check its displayed runtime and format/aspect ratio when available.
2. Review the rendered video from start to finish when playback permits. If full playback is impractical, seek to the opening, every scene boundary/major transition, the turn, and the final seconds, and inspect the visible frame and playback position at each point.
3. Compare the rendered sequence with the storyboard and timeline. Specifically confirm the opening is the hook, the scenes play in story order, the reveal/turn precedes the payoff, and the final shot is the intended resolution.
4. Check for dead air or unwanted waiting between clips, including frozen/held frames, blank frames, accidental pauses, abrupt cuts, repeated or missing scenes, and missing/cut-off audio. A pause is acceptable only when it is deliberate and advances the intended timing or emotion.
5. If any order, timing, continuity, or playback issue is found, return to the timeline, correct it, save, export again, and repeat this rendered-file check on the new output. Do not present a known-wrong render as final.
6. If the player cannot seek, a transition cannot be inspected, or another check is unavailable, state that specific limitation and do not claim that check passed. Only report checks supported by visible evidence.

## Platform packaging and delivery

Use a shared 9:16 master for both platforms. Keep important faces, action, text, and AJ-AI branding in the central safe area with top and bottom space for interface controls. Prefer a clean export without platform watermarks or baked-in follow prompts. Use audio cleared for both services, or export without music and add audio separately in each platform's own editor.

Prepare separate upload copy:
- **YouTube Shorts:** concise title, short description, and a few relevant hashtags.
- **Facebook Reels:** conversational caption/description and a few relevant hashtags.

The default 30–45 second edit stays comfortably within the currently described Facebook Reels limit and YouTube Shorts limit. If the user requests longer content, check the current destination upload requirements before finalizing. The workflow creates an export and copy; it does not publish unless the user asks.

## Delivery

Report the title, format, scene count, actual runtime when visible, audio choice, save/export state, and whether timeline completeness was checked. Mention any failed scene or check that could not be completed. Never claim a render, timeline review, or export succeeded unless you saw evidence in VideoExpress.

## Copy-ready intake

**Let's make an AJ-AI video for Facebook Reels and YouTube Shorts.** Tell me the story idea or animal, and optionally the length, visual style, narration choice, or reference image/video. If you leave those open, I'll use the personal defaults above.

## Rendering and export: wait and recheck

VideoExpress can run up to five video clips concurrently for this user, subject to any lower visible account limit. Jobs finish independently: submitting five together does not mean all five complete together.

### While clips render
- Record each scene's existing job ID/title, current status, completed asset if any, and most recent check. Keep queued/rendering/completed/failed states separate for every scene.
- When a job still says queued, rendering, processing or another in-progress status, wait a short interval and recheck that same job. Use supported waits around 15–30 seconds when available, adapting to visible progress and tool limits. Avoid rapid repeated refreshes.
- Update only jobs whose status actually changed. Preserve completed clips and continue useful independent work while the others render. If more scenes are planned, use a free slot only after an earlier job is confirmed finished/failed; never exceed five or the lower visible limit.
- Continue waiting and checking unfinished jobs until every planned scene reaches a known result. One completed clip, an old thumbnail or a mixed-status batch does not establish completion of the whole batch.
- Do not resubmit a queued/rendering job, count slow progress as a generation attempt, or restart successful clips. Before retrying an unknown result, inspect existing jobs and assets. Retry only a confirmed failure or material unusability within the workflow's retry limit.
- Keep the user informed roughly once per minute during a long wait, for example “4 of 5 clips are complete; scene 3 is still rendering.” Do not end the task or ask whether to continue merely because generation is ongoing.
- If status appears stalled, make a supported low-risk status check/recovery and inspect existing assets before any resubmission. Elapsed time alone is not proof of failure. Respect site/tool recovery limits; if a session limit or concrete unresolved error prevents further monitoring, preserve job identities, report the last observed state and give the exact blocker rather than claiming completion.

### While the export runs
- Submit export once and record the existing export's identity/title and status.
- If it still says queued, exporting, rendering or processing, wait and recheck that same export, typically after 15–30 seconds. Continue until a visible completed or failed result; do not click Export again because the first job is slow.
- Before any recovery/retry, inspect the existing export results to avoid duplicate exports. A status check or wait is not an export attempt.
- A completed badge is followed by opening the actual exported item/file and verifying playback, duration, ending and required quality checks. A submitted export, spinner or finished editor timeline is not a delivered MP4.
- For a confirmed failed export, use bounded supported recovery and preserve the saved project. If monitoring or playback is unavailable, report the exact remaining state/check honestly.

Use supported visible product controls for status checks; do not bypass site safeguards or use hidden service APIs. No repeated user approval is needed simply to wait and recheck routine authorized renders or exports.

## Mandatory continuity in every scene

Keep all recurring people, animals and story-relevant objects consistent across every source image, generated clip and scene join. Changes are allowed only when required by the story or explicitly requested by the user. A new camera angle, render or scene number is not a reason to redesign a subject, replace a prop or reset its state.

Before rendering, create a continuity inventory in the private scene ledger:
- Give every recurring person/animal a stable ID. Record face/head, hair/fur/markings, proportions, illustrated style, relative size, distinguishing cues and selected reference. Retain established constraints such as no glasses for the stickman couple.
- Record each character's situation-appropriate outfit, colors, accessories and occupied hands/paws. Keep the selected outfit through connected scenes; change it only for an explicit wardrobe/time/location transition.
- Give every important object a stable ID and exact count, shape, size, color, design, owner and location. Preserve its current state: open/closed, full/empty, switched on/off, intact/broken, dry/wet, held/placed, and similar story-relevant properties.
- Fix recurring set landmarks, furniture, relative distances, light/time progression and camera side. Keep screen direction, facing, gaze, pose and physical contact coherent through the handoff.

For every scene, repeat the relevant identity/outfit/object/set details in image and motion prompts rather than relying on memory or the words “same as before.” Use available Consistent Character/reference features for identity and environments as supported; never displace a required character reference with an object/room reference. If reference slots are limited, repeat concrete details and inspect the output; do not claim perfect locking.

Scene N's outgoing state becomes scene N+1's incoming state. Do not introduce duplicates, missing/replaced characters or props, unexplained ownership changes, mirrored rooms, early food, spontaneous outfit changes or repeated/reset actions. A legitimately hidden/off-screen object remains in its established location/state; it does not need to appear in every shot or be moved into view. A tighter crop must not be mistaken for disappearance.

Plan and record every permitted change: what changes, why, in which scene, and the resulting new state. Show or clearly motivate entrances, exits, deliveries, transfers, wardrobe changes, breakage, growth, consumption and location/time transitions. After the change, carry the new state forward consistently. Honor deliberate user-requested redesigns while preserving everything else.

Review each source before animation and check rendered continuity during the final clip/join/export pass. Concurrent production may use planned handoffs while earlier clips render; do not require all jobs to finish serially. Correct material identity, object or spatial errors within the existing bounded retry rules, preserving successful assets. Minor harmless variations do not justify unlimited regeneration. If a check cannot be performed, mark it unverified rather than claiming consistency.
