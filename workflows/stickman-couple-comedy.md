# Stickman Couple Comedy Shorts — VideoExpress Workflow

## Purpose

Create original, funny, comic-style husband-and-wife stories for Facebook Reels and YouTube Shorts using VideoExpress AI. Each episode is designed as **30 seconds total: five clips, six seconds each**. Default format is a shared **vertical 9:16 master at 1080×1920 MP4 when available**.

The stories should feel relatable, warm, visually expressive, and easy to understand without sound. Use playful domestic misunderstandings, clever reversals, exaggerated reactions, and a strong visual punchline. Keep the couple affectionate: the humor comes from the situation and their personalities, not cruelty, humiliation, or stereotypes.

This workflow is inspired by the general idea of a narrated stickman story agent. It is an original adaptation for this repo; it does not copy the reference project's full prompt.

## Defaults

- Platforms: Facebook Reels and YouTube Shorts. Prepare separate platform titles/captions from the same clean video master.

- Format: vertical 9:16.
- Runtime: 30 seconds.
- Structure: exactly five 6-second clips.
- Style: clean 2D stickman comic animation, bold readable outlines, expressive faces, clear poses, bright cel colors, simple backgrounds, motion lines and restrained comic effects.
- Cast: one recurring husband and one recurring wife, unless a story needs a small supporting role.
- Character consistency: create one character reference/master for each spouse, keep their design and outfits stable in the episode, and use the same references in every scene when supported.
- Audio: include short, natural husband-and-wife dialogue by default. Use stable, distinct voices and correct speaker assignment. Keep the visual joke understandable on mute with readable captions when supported. Narration is optional and must not replace the couple's exchange.
- Branding: place “AJ-AI” subtly in a background detail when it fits; never rely on tiny lettering.
- Rendering: VideoExpress supports up to five simultaneous renders for this workflow. Confirm the visible account limit; submit the five planned clips in order, never more than five at once.

## Comedy and story rules

1. Start with an instantly readable hook in the first seconds.
2. Build a simple cause-and-effect chain across all five clips.
3. Give each spouse a distinct, affectionate comic personality. Avoid reducing either character to a gender stereotype.
4. Use one clear visual joke or story beat per clip.
5. Escalate the problem in clips 2–4, then deliver a surprising but logical payoff in clip 5.
6. Prefer visual humor that works on a phone screen: expressive eyebrows, clear eyelines, exaggerated but readable poses, props, timing, reaction shots, and visual reversals.
7. Keep the joke original and specific. Avoid copying recognizable characters, existing skits, or viral videos.
8. Keep dialogue short enough to fit naturally in six seconds. No clip should require a long explanation.
9. Keep characters kind to each other. End on a shared laugh, affectionate reveal, or playful twist where possible.
10. No filler: if a beat does not advance the gag, sharpen or remove it while preserving the five-clip format.

## Relatable, enjoyable, shareable comedy — required

- Choose an everyday situation viewers recognize immediately: deciding dinner, lost phones, shared blankets, delivery fees, chores, alarms, or choosing a movie.
- Aim for “this is us” recognition and a reason to send the short to a partner or friend. Shareability is a creative goal, never a guaranteed performance claim.
- Write the spoken joke first. Use conversational English, contractions, short lines, and a clear setup followed by a surprising payoff. Avoid abstract lessons, slow explanations, or a story whose humor depends on a plant visibly changing health in seconds.
- Hook within the first two seconds. Each clip must add a new beat; clip 5 must deliver the strongest laugh. End with a warm reaction or visual callback, not an explanation of the joke.
- Allow roughly 8–12 spoken words per six-second clip and leave time for expressions and a reaction pause. Prefer one speaker per clip; when two speak, specify their order and prohibit overlapping speech.
- In VideoExpress's combined Video and Audio Prompt field, include exact quoted dialogue with the speaker named, plus voice and timing directions. Use separate audio controls when the app offers them. Keep dialogue out of the source-image prompt.
- Reuse the same reference image for the couple. A reference containing both spouses may be used when the app supports it. Keep mouths visible for speaking shots and avoid unnecessary camera movement.
- Review every rendered clip for audible dialogue, correct speaker, stable voice, natural pacing, and a readable joke. Retry confirmed unusable output within the existing attempt limit. Never export a dialogue episode with missing or cut-off lines.
- Use captions only when supported and proofread them. Do not claim captions, audio review, or audience appeal were verified unless actually checked.

## Five-clip beat map

| Clip | Story function | Typical beat |
|---|---|---|
| 1 — 0:00–0:06 | Hook | A surprising request, object, claim, or mishap |
| 2 — 0:06–0:12 | First reaction | Spouse reacts or misunderstands; a plan begins |
| 3 — 0:12–0:18 | Escalation | The plan makes things funnier or worse |
| 4 — 0:18–0:24 | Reversal setup | A clue or unexpected consequence changes the meaning |
| 5 — 0:24–0:30 | Payoff | Visual punchline, warm twist, and a clean ending pose |

Each clip is six seconds. The story plan must total 30 seconds. If VideoExpress returns a slightly different actual duration, record it and adjust the assembly where supported without cutting off speech.

## Preproduction

Before rendering, write a compact storyboard table with:
- clip number and exact target duration;
- spoken line or caption (if any);
- incoming character pose and screen position;
- one new action and emotional reaction;
- outgoing pose and prop state;
- image prompt;
- video/motion prompt;
- continuity handoff to the next clip.

## Permanent couple reference

Use the couple in the user's master image, “Vertical 916 frame, clean 2D stickman comic illustration.jpg,” for identity cues only. Redraw both as the same simple stick-figure style. Use the linked reel as a broad simplicity reference only if it can be viewed; do not copy its story, shot sequence, or characters: https://www.facebook.com/reel/1797942614850513

- **Both spouses:** simple white circular heads; only two small dot eyes and one short line mouth; very thin black line for neck, torso, arms, and legs. No detailed face, nose, eyelashes, fingers, muscles, or body volume.
- **Husband:** tiny blue rectangular shirt mark over the line torso; simple round black glasses that stay visible; at most one small black hair stroke.
- **Wife:** tiny yellow shirt/cardigan mark over the line torso; one short black ponytail stroke with a small yellow tie. Do not give her a different, more detailed, or more humanlike art style.
- Keep the heads, line thickness, proportions, and sparse flat coloring consistent between the two characters and every shot. The blue and yellow clothing marks and glasses/ponytail are identity cues; they must not create realistic bodies.
- Do not use chibi, anime, manga, 3D, realistic cartoon people, skin-colored limbs, detailed hair, facial features beyond dots and one line mouth, shaped hands, shoes, or dimensional clothing. Avoid hybrid bodies, thick thighs, missing or cropped limbs, and mismatched character styles.
- Reuse the approved couple reference when supported, but explicitly instruct the model to simplify both figures into this same minimal stickman design. If the reference conflicts with the simple line-figure rule, follow the simple line-figure rule.
- Every image and video prompt must state that both spouses are simple stick figures and repeat the glasses and ponytail cues. Check opening, middle, and ending frames for style drift and missing accessories before assembly.

### Character identity and prop continuity — required

- Treat the husband's round glasses and blue shirt mark, and the wife's ponytail and yellow shirt mark, as the only signature identity cues.
- Reuse the approved couple reference for all clips when available, simplified into the same minimal stick-figure style.
- Review opening, middle, and ending frames for matching circle heads, dot faces, line limbs, clothing marks, glasses, and ponytail. Regenerate clips that become humanlike, change style, or lose a signature cue.

### Stickman anatomy — non-negotiable

- Both spouses must read instantly as simple stick figures: unfilled white circular heads, two dot eyes, one short line mouth, a thin black line torso, and thin black line arms and legs.
- Clothing is limited to small flat color marks on the torso. Arms and legs stay as single thin lines. Do not add flesh, skin tones, realistic joints, muscles, hands, feet, or detailed anatomy.
- Both characters must use the same line thickness, head style, facial simplicity, and level of detail. The wife must not become a humanlike cartoon while the husband remains a stickman.
- Keep the whole figure visible where practical; if a pose hides limbs, simplify the pose or framing. Never crop a limb in a way that makes it look incomplete or malformed.
- Put these requirements in every source-image prompt and every motion prompt. Inspect the source image before animation; reject it if either spouse is not a clear, matching stick figure. Inspect motion output for style drift before assembly.

## Image prompts

For each clip, create a separate 9:16 source-image prompt showing the exact opening moment of that clip. Include:
- both characters' appearance, position, facing, eyeline, expression, and pose;
- the key prop's exact count, owner, location, and contact points;
- clear foreground, middle ground, and background;
- the room's stable layout and landmarks;
- camera framing and enough visible space for the action;
- bright, readable 2D comic lighting, clean outlines, cel colors, and a restrained comic visual effect where useful;
- the clip's incoming state, so it continues from the previous clip.

Use large expressive poses and silhouettes. Keep backgrounds simple enough that the joke reads instantly.
- Include the complete stickman anatomy checklist in every prompt: round heads; line-art necks and torsos; two thin continuous arms and two thin continuous legs per person; clearly connected knees and ankles; visible feet in full-body framing; consistent thin line weight; matching 2D stick-figure style for both spouses; no flesh-like limbs or realistic human anatomy.
- Stage both spouses in a full-body or three-quarter view with all four legs visible and unblocked. Avoid poses, furniture, props, or crops that conceal the knees, lower legs, ankles, or feet.
- Before animation, inspect each source image for two complete, correctly connected stick figures and matched style. Regenerate any source that has a hybrid body, a missing/cropped/hidden limb, a realistic spouse, malformed joints, or inconsistent limb thickness. Do not proceed until the source passes this check.

## Video prompts

Write one motion prompt for each source image. Describe a continuous six-second beat:
- opening pose;
- the main movement and reaction;
- camera movement, if useful;
- comic timing (pause, anticipation, quick reveal, reaction);
- motion lines, impact burst, squash-and-stretch, or other restrained effects;
- ending pose and prop state that leads into the next clip.

Keep text, narration, and dialogue out of the visual prompt if they belong in separate VideoExpress controls. Avoid asking for multiple unrelated actions in one clip. Preserve the same character designs, room geography, and screen direction across cuts.

## Rendering workflow

1. Prepare all five scenes and prompts before generation.
2. Confirm the project and generation-dialog ratio are both vertical 9:16.
3. Check the visible concurrent render limit; the planned batch is exactly five and must never exceed the account's displayed limit.
4. Submit clips 1–5 in story order, track each scene and job status, and do not resubmit an uncertain job.
5. Wait for all five jobs to reach a known result. If a render fails, inspect it before retrying; retry only confirmed failures or clearly unusable output, with at most three total attempts per clip.
6. Keep completed clips and note actual durations. Do not treat a full render queue as a failure.

## Timeline assembly and rendered-export QA — required

The planned five-clip beat map is the source of truth. Do not export until every usable rendered clip is accounted for, and do not deliver until the rendered output has been reviewed.

### Before export: verify the timeline

1. Match every finished clip to its numbered beat by visible content; do not trust creation order or filenames alone.
2. Confirm clips 1–5 appear in beat order exactly once, with no missing or duplicate clip.
3. Check total duration and every boundary. Run Auto Align or the equivalent when available, then inspect for gaps, overlaps, blank/black frames, frozen holds, repeated footage, abrupt cuts, and cut-off action/dialogue.
4. Play the timeline from start through finish when practical. At minimum inspect the hook, every clip join, reversal setup, final punchline, and audio handoffs.
5. Remove unwanted waiting or held time; keep pauses only when they are intentional comic timing. Confirm dialogue is complete, assigned to the right speaker, and not duplicated.
6. Save and confirm the project before exporting.

### After export: verify the rendered file

1. Wait until the new export is complete, open that rendered output, and confirm it plays. Check its displayed runtime and format/aspect ratio when available.
2. Review from start to end when practical. Otherwise seek to the opening, every clip boundary, the reversal, and final seconds; inspect playback position and frame.
3. Verify the output really plays clips 1–5 in order and ends on clip 5's intended punchline, not just as arranged in the editor.
4. Check for unwanted waiting, frozen/blank frames, accidental pauses, abrupt cuts, repeated or missing beats, and missing, overlapping, or cut-off dialogue/audio.
5. If any problem appears, correct the timeline, save, export again, and repeat the rendered-file review. Never call a known-wrong export final.
6. If a check is unavailable in the player, state that limitation and do not claim it passed.
## Example story seed

**“The husband says he has finally learned to listen. His wife tests him by asking him to bring one thing from the kitchen. He returns with an absurd pile of items. Just as she starts to explain, he reveals he brought everything so she could choose. She laughs, then hands him the one thing he forgot: the grocery list.”**

Expand any story seed into exactly five six-second clips, each with a concise visual gag, a detailed image prompt, a separate motion prompt, and short natural dialogue by default. The example is only a seed; create fresh stories rather than repeating it automatically.

## Cross-posting package

Keep the shared 30-second master in vertical 9:16, with faces, captions, and the joke's key prop away from top and bottom interface controls. Export without platform watermarks or baked-in follow prompts. Use music only if cleared for both destinations; otherwise add platform-cleared audio separately.

Prepare a concise YouTube title/description and a separate Facebook caption/description. This workflow prepares the video and copy but does not publish unless the user asks.

## Completion report

Report the title, 9:16 ratio, five-clip count, measured runtime, narration/audio choice, whether all clips were verified on the timeline, and save/export status. State any QA limitation honestly; never claim a timeline or export check was completed unless it was actually performed.
