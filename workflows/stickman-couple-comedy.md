# Stickman Couple Comedy Shorts — VideoExpress Workflow

## Purpose

Create original, funny, comic-style husband-and-wife stories for YouTube Shorts using VideoExpress AI. Each episode is designed as **30 seconds total: five clips, six seconds each**. Default format is **vertical 9:16**.

The stories should feel relatable, warm, visually expressive, and easy to understand without sound. Use playful domestic misunderstandings, clever reversals, exaggerated reactions, and a strong visual punchline. Keep the couple affectionate: the humor comes from the situation and their personalities, not cruelty, humiliation, or stereotypes.

This workflow is inspired by the general idea of a narrated stickman story agent. It is an original adaptation for this repo; it does not copy the reference project's full prompt.

## Defaults

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

Give the couple stable visual identities with a continuity card approved before rendering: husband with a blue shirt and round glasses; wife with a yellow cardigan and high ponytail. Treat these features as mandatory in every image and motion prompt, and verify them at the start, middle, and end of each rendered clip before assembly. Do not silently change faces, clothing, proportions, or accessories from clip to clip. Keep both characters clearly 2D stickmen; avoid photorealistic humans or mixed art styles.

### Character identity and prop continuity — required
- Before rendering, define a continuity card for each recurring character with exact head/face, hair, outfit colors, body proportions, and signature accessories. For this couple: husband has round glasses and a blue shirt; wife has a ponytail and a yellow cardigan.
- Treat signature accessories as fixed character features, not optional props. State them explicitly in every source-image prompt and every video/motion prompt, including the final clip. The husband must wear the same round glasses in every frame; the wife must retain her same ponytail. Do not omit, replace, recolor, or transfer them.
- Reuse the same approved character reference image for all clips when supported. Do not switch to a newly generated character design mid-episode. If a clip begins from a different source image, compare it against the continuity card and approved reference before animating.
- Review each generated clip at its opening, middle, and ending frames, including the final laugh/reaction. Check glasses, hair, clothing, face, proportions, line style, and limb count. Reject and regenerate any clip that loses or changes a signature feature or visibly drifts from the approved design. Do not assemble or export until every clip passes this continuity check.

### Stickman anatomy — non-negotiable
- Both spouses must be full-body, unmistakable stick-figure characters in every reference and generated shot. Use a simple round head, expressive face, and thin continuous line-art neck, torso, arms, hands, legs, and feet. Clothing may appear as simple colored shapes over the line-art body, but must not turn the torso or limbs into realistic human anatomy.
- Show two complete legs per character from hips to feet, with both knees and ankles visibly connected in the correct order. Legs must have consistent thin stick-line thickness from upper leg through knee to ankle; do not mix human thighs with stick lower legs, omit a leg, end a leg at the knee, merge legs, or crop limbs at frame edges. Keep feet visible when a full-body shot is requested.
- Make both characters match the same stickman art style and level of detail. No realistic human girl, realistic skin/flesh limbs, partial-body hybrid, mannequin, amputated appearance, malformed joints, extra/missing limbs, or inconsistent limb thickness.
- Use full-body or three-quarter framing with enough room around each figure to inspect all limbs. If a pose, prop, sofa, or frame hides the legs, change the staging or camera framing so both complete leg silhouettes remain readable.
- Put these anatomy constraints directly into every source-image prompt and every video/motion prompt; image/video models may not reliably carry instructions across stages. Re-state the matching design for husband and wife rather than relying on “same characters” alone.
- Inspect each generated source image at readable size before animating. Reject and regenerate any image where either spouse is not clearly a complete stick figure, where any limb is cropped/hidden/malformed, or where the two spouses use different art styles. Do not send a failed anatomy reference into video generation. After motion generation, inspect for limb deformation or style drift and retry confirmed unusable output within the attempt limit.

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

## Timeline assembly — required before export

Do not export until every usable rendered clip is on the timeline.

1. Match each finished video to clips 1–5 using scene names or job identity.
2. Add each clip to the timeline in order, exactly once.
3. After every addition, verify one new clip appears before adding the next.
4. Check that the timeline contains all five clips in order and no duplicates.
5. Confirm total duration is about 30 seconds; note actual timing and adjust where available.
6. Keep narration/dialogue attached and avoid duplicated audio.
7. Run Auto Align or the equivalent timing tool when available.
8. Inspect the beginning, transitions, and final punchline for obvious gaps, overlaps, or cut-off audio.
9. Save and confirm the project.
10. Export only after confirming all five clips are present. Verify the exported video exists and opens when possible.

## Example story seed

**“The husband says he has finally learned to listen. His wife tests him by asking him to bring one thing from the kitchen. He returns with an absurd pile of items. Just as she starts to explain, he reveals he brought everything so she could choose. She laughs, then hands him the one thing he forgot: the grocery list.”**

Expand any story seed into exactly five six-second clips, each with a concise visual gag, a detailed image prompt, a separate motion prompt, and short natural dialogue by default. The example is only a seed; create fresh stories rather than repeating it automatically.

## Completion report

Report the title, 9:16 ratio, five-clip count, measured runtime, narration/audio choice, whether all clips were verified on the timeline, and save/export status. State any QA limitation honestly; never claim a timeline or export check was completed unless it was actually performed.
