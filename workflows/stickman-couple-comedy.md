# Stickman Couple Comedy Shorts — VideoExpress Workflow

## Purpose

Create original, funny, comic-style husband-and-wife stories for Facebook Reels and YouTube Shorts using VideoExpress AI. Default planning target: **about 30 seconds total, five roughly six-second clips**. Honor explicit duration/scene-count requests and report measured runtime. Default format is a shared **vertical 9:16 master at 1080×1920 MP4 when available**.

The stories should feel relatable, warm, visually expressive, and easy to understand without sound. Use playful domestic misunderstandings, clever reversals, exaggerated reactions, and a strong visual punchline. Keep the couple affectionate: the humor comes from the situation and their personalities, not cruelty, humiliation, or stereotypes.

This workflow is inspired by the general idea of a narrated stickman story agent. It is an original adaptation for this repo; it does not copy the reference project's full prompt.

## Starting a new video

If the user requests a new video without supplying a story or explicitly asking you to choose, ask once: **“Do you have a story idea, or would you like me to choose one?”** Wait for the answer before story planning or generation.

If the user supplies an idea, use it without asking this question again. If the user says “choose your own,” “you select,” or equivalent, choose an original affectionate couple-comedy premise and continue through the finished video without another story-approval pause. Keep all other defaults and the permanent couple reference. Do not ask this question again during routine production.

## Defaults

- Platforms: Facebook Reels and YouTube Shorts. Prepare separate platform titles/captions from the same clean video master.

- Format: vertical 9:16.
- Runtime: approximately 30 seconds by default; honor explicit requests.
- Structure: five roughly six-second clips by default; adjust for an explicit request.
- Style: clean 2D stickman comic animation, bold readable outlines, expressive faces, clear poses, bright cel colors, simple backgrounds, motion lines and restrained comic effects.
- Cast: one recurring husband and one recurring wife, unless a story needs a small supporting role.
- Character consistency: reuse the user's approved permanent couple across stories and revisions. Do not create replacement masters each episode. Inspect the actual reference and retain the established minimal stick-figure design below.
- Audio: include short, natural husband-and-wife dialogue by default. Use stable, distinct voices and correct speaker assignment. Keep the visual joke understandable on mute with readable captions when supported. Narration is optional and must not replace the couple's exchange.
- Branding: place “AJ-AI” subtly in a background detail when it fits; never rely on tiny lettering.
- Rendering: at most five concurrent video jobs, or the lower visible account limit. A full queue means wait for a slot, not resubmit.

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
10. No filler: if a beat does not advance the gag, sharpen or remove it while preserving the requested story length.

## Relatable, enjoyable, shareable comedy — required

- Choose an everyday situation viewers recognize immediately: deciding dinner, lost phones, shared blankets, delivery fees, chores, alarms, or choosing a movie.
- Aim for “this is us” recognition and a reason to send the short to a partner or friend. Shareability is a creative goal, never a guaranteed performance claim.
- Write the spoken joke first. Use conversational English, contractions, short lines, and a clear setup followed by a surprising payoff. Avoid abstract lessons, slow explanations, or a story whose humor depends on a plant visibly changing health in seconds.
- Hook within the first two seconds. Each clip must add a new beat; clip 5 must deliver the strongest laugh. End with a warm reaction or visual callback, not an explanation of the joke.
- Allow roughly 8–12 spoken words per six-second clip and leave time for expressions and a reaction pause. Prefer one speaker per clip; when two speak, specify their order and prohibit overlapping speech.
- Use dedicated dialogue/audio controls when available and keep speech out of visual-motion and source-image prompts. Only use a combined field for speech when the current UI explicitly supports that route; verify the result rather than assume spoken dialogue.
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

The table shows the default planning target, not measured output. Record actual audio/clip durations and cumulative runtime; honor explicit requests such as 36 seconds/six scenes. Shorten speech before generation when needed. Trim only surplus tails, never cut words or speed speech to force timing.

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

**Current character override: no glasses on either the husband or the wife.** Omit eyewear from all generated source images and clips, even though the older bundled reference shows glasses on the husband. Keep the remaining identity cues and minimal stick-figure style. This rule takes precedence over eyewear in any reference.

Use the approved bundled [permanent-couple.png](../characters/permanent-couple.png) as the default identity reference, unless the user supplies a newer one. See [the reference procedure](../characters/permanent-couple.md) for inspection and VideoExpress selection/upload. Preserve the established simplified line-figure style. Redraw both as the same simple stick-figure style. Use the linked reel as a broad simplicity reference only if it can be viewed; do not copy its story, shot sequence, or characters: https://www.facebook.com/reel/1797942614850513

- **Both spouses:** simple white circular heads; only two small dot eyes and one short line mouth; very thin black line for neck, torso, arms, and legs. No detailed face, nose, eyelashes, fingers, muscles, or body volume.
- **Husband:** simple line torso with a small flat outfit shape suited to the situation; blue is the casual default, not a permanent uniform. No glasses; at most one small black hair stroke.
- **Wife:** simple line torso with a small flat outfit shape suited to the situation; yellow is the casual default, not a permanent uniform. Keep her short black ponytail cue; adapt a hair tie naturally if needed. Do not give her a more detailed or humanlike style.
- Keep the heads, line thickness, proportions, and sparse flat coloring consistent between the two characters and every shot. Recognizable heads, facial simplicity, hair cues, proportions and line weight preserve identity. Clothing may change to suit the situation and must not create realistic bodies.
- Do not use chibi, anime, manga, 3D, realistic cartoon people, skin-colored limbs, detailed hair, facial features beyond dots and one line mouth, shaped hands, shoes, or dimensional clothing. Avoid hybrid bodies, thick thighs, missing or cropped limbs, and mismatched character styles.
- Reuse the approved couple reference when supported, but explicitly instruct the model to simplify both figures into this same minimal stickman design. If the reference conflicts with the simple line-figure rule, follow the simple line-figure rule.
- Every image and video prompt must state that both spouses are simple stick figures and repeat the selected scene outfit and ponytail cues; neither spouse wears glasses. Check opening, middle, and ending frames for style drift and missing accessories before assembly.

### Character identity and prop continuity — required

- Preserve each spouse's head, simple face, hair cues, proportions and matching line style. The wife's ponytail remains recognizable. Blue/yellow outfits are casual defaults, not mandatory identity locks.
- Reuse the approved couple reference for all clips when available, simplified into the same minimal stick-figure style.
- Review opening, middle, and ending frames for matching circle heads, dot faces, line limbs, clothing marks and ponytail, with no glasses on either spouse. Regenerate clips that become humanlike, change style, or lose a signature cue.

### Stickman anatomy — non-negotiable

- Both spouses must read instantly as simple stick figures: unfilled white circular heads, two dot eyes, one short line mouth, a thin black line torso, and thin black line arms and legs.
- Clothing uses simple flat shapes/color accents appropriate to the scene, such as a pajama top or robe. Keep the underlying stick silhouette readable and arms/legs as complete thin lines; avoid bulky, realistic garment volume. Do not add flesh, skin tones, realistic joints, muscles, hands, feet, or detailed anatomy.
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
- Include the complete stickman anatomy checklist in every prompt: round heads; line-art necks and torsos; two thin continuous arms and two thin continuous legs per person, complete to their simple line endpoints; consistent thin line weight; matching 2D stick-figure style for both spouses; no flesh-like limbs, modeled joints, shaped hands/feet or realistic anatomy.
- Favor full-body or readable three-quarter views with all four legs complete and unblocked. Simplify overlaps or move the camera if furniture/contact makes a limb appear missing; do not add realistic anatomy to solve visibility.
- Before animation, inspect each source image for two complete, correctly connected stick figures and matched style. Regenerate any source that has a hybrid body, a missing/cropped/hidden limb, a realistic spouse, malformed joints, or inconsistent limb thickness. Do not proceed until the source passes this check.

## Video prompts

Write one motion prompt for each source image. Describe one continuous beat near the planned clip duration:
- opening pose;
- the main movement and reaction;
- camera movement, if useful;
- comic timing (pause, anticipation, quick reveal, reaction);
- motion lines, impact burst, squash-and-stretch, or other restrained effects;
- ending pose and prop state that leads into the next clip.

Keep text, narration, and dialogue out of the visual prompt if they belong in separate VideoExpress controls. Avoid asking for multiple unrelated actions in one clip. Preserve the same character designs, room geography, and screen direction across cuts.

## Rendering workflow

Open **https://app.videoexpress.ai/** in the supported browser. This is the correct application URL; do not use app.videoexpressai or guess another domain.

1. Prepare all planned scenes and prompts before generation; five is the default.
2. Confirm the project and generation-dialog ratio are both vertical 9:16.
3. Check the visible concurrent render limit; never exceed five jobs or the lower displayed limit.
4. Submit scenes in story order. Record job ID/status immediately and prepare the next source while earlier jobs render. Keep the same panel and approved references. Never duplicate an uncertain job; use planned handoffs during submission and review actual joins in the final pass.
5. Wait for every planned job to reach a known result. If a render fails, inspect it before retrying; retry only confirmed failures or clearly unusable output, with at most three total attempts per clip.
6. Keep completed clips and note actual durations. Do not treat a full render queue as a failure.

## Timeline assembly and rendered-export QA — required

The requested storyboard and recorded scene count are the source of truth (five by default). Do not export until every usable rendered clip is accounted for, and do not deliver until the rendered output has been reviewed.

### Before export: verify the timeline

1. Match every finished clip to its numbered beat by visible content; do not trust creation order or filenames alone.
2. Confirm every planned clip, including the final punchline, appears in beat order exactly once, with no missing or duplicate clip.
3. Check total duration and every boundary. Run Auto Align or the equivalent when available, then inspect for gaps, overlaps, blank/black frames, frozen holds, repeated footage, abrupt cuts, and cut-off action/dialogue.
4. Play the timeline from start through finish when practical. At minimum inspect the hook, every clip join, reversal setup, final punchline, and audio handoffs.
5. Remove unwanted waiting or held time; keep pauses only when they are intentional comic timing. Confirm dialogue is complete, assigned to the right speaker, and not duplicated.
6. Save and confirm the project before exporting.

### After export: verify the rendered file

1. Wait until the new export is complete, open that rendered output, and confirm it plays. Check its displayed runtime and format/aspect ratio when available.
2. Review from start to end when practical. Otherwise seek to the opening, every clip boundary, the reversal, and final seconds; inspect playback position and frame.
3. Verify the output really plays all planned clips in order and ends on the intended final punchline, not just as arranged in the editor.
4. Check for unwanted waiting, frozen/blank frames, accidental pauses, abrupt cuts, repeated or missing beats, and missing, overlapping, or cut-off dialogue/audio.
5. If any problem appears, correct the timeline, save, export again, and repeat the rendered-file review. Never call a known-wrong export final.
6. If a check is unavailable in the player, state that limitation and do not claim it passed.
## Example story seed

**“The husband says he has finally learned to listen. His wife tests him by asking him to bring one thing from the kitchen. He returns with an absurd pile of items. Just as she starts to explain, he reveals he brought everything so she could choose. She laughs, then hands him the one thing he forgot: the grocery list.”**

Expand any story seed into five roughly six-second clips by default, or the requested scene count/runtime, each with a concise visual gag, a detailed image prompt, a separate motion prompt, and short natural dialogue by default. The example is only a seed; create fresh stories rather than repeating it automatically.

## Cross-posting package

Keep the shared 30-second master in vertical 9:16, with faces, captions, and the joke's key prop away from top and bottom interface controls. Export without platform watermarks or baked-in follow prompts. Use music only if cleared for both destinations; otherwise add platform-cleared audio separately.

Prepare a concise YouTube title/description and a separate Facebook caption/description. This workflow prepares the video and copy but does not publish unless the user asks.

## Completion report

Report the title, ratio, actual clip count, measured runtime, narration/audio choice, whether all clips were verified on the timeline, and save/export status. State any QA limitation honestly; never claim a timeline or export check was completed unless it was actually performed.

## Reference, set and prop safeguards

See [permanent couple reference](../characters/permanent-couple.md) and use the [private scene ledger](../templates/scene-ledger.md). Keep the existing simple line-figure style authoritative; the added procedures do not replace it with a detailed cartoon.

- Verify the approved paired reference in Consistent Character for every clip, including scene 1. Keep the selection while the panel is open; restore only on a visible reset. Never replace it with a scene image or drifting last frame.
- Use separate spouse/environment slots only as the UI supports. Prioritize the approved couple reference; if a room reference would displace it, repeat fixed room geometry in text instead. Report reference-capacity limitations honestly.
- Fix sofa, door, window, table and camera-side positions. Preserve facing, gaze, hand/arm contact, prop ownership/count/state and outgoing pose across clips.
- Props enter at the correct story event. During a discussion about ordering pizza, the table stays empty until pizza arrives. Noodles do not appear before they are prepared or delivered.
- Check the generation dialog's ratio independently from the project bar before every image submission. Keep image enhancement OFF; restore it if a rerender resets it. Keep Creative mode OFF and Advanced Mode OFF for the reference-based route when available.
- Review each source before animation. Use at most three informed source attempts for a material defect; if none is usable, report the blocker. Preserve successful assets.

## Speech, subtitles and music controls

Keep dialogue-led comedy as the default. Verify stable spouse voice assignments and actual audio; do not silently replace dialogue with narration. If separate dialogue/voices are unsupported, report the limitation and use an alternative only within the user's authorized scope.

For requested narration, prefer the integrated VideoExpress route when available: Narration Video → Create Video → CloneVoice → System Voice → verified available voice → create/import speech within that dialog → generate video. Use actual labels. Do not default to standalone CloneVoice downloads or another provider. Keep visual instructions separate from speech.

Add correctly spelled synchronized subtitles through available editor controls, not generated image text. Keep them inside vertical safe margins and match actual speech. Add suitable included music when available with rights for the intended destinations, quiet beneath dialogue; calm spa music suits the massage example. Do not purchase music or claim captions/music exist when unsupported.

## Exact timeline additions and final checks

Match each completed asset to its ledger entry, not newest-first library order. Where available, use My Media → My AI Videos → right-click the correct card → Add to Timeline. Verify one new clip each time and inspect an uncertain result before repeating. Record each clip's start/end and add count.

After final assembly and export, check opening, every join, final scene and complete runtime for blank/dark sections, unexplained bars, freezes, unwanted pauses, unwanted glasses on either spouse, lost ponytail/identity cues, unexplained outfit changes, humanlike or incomplete limbs, early food, subtitle spelling/sync and dialogue/music balance. Auto Align does not fix visual continuity.

Make final playback checks before claiming verified quality. If full playback or audio listening is unavailable, list the unverified checks. Correct material failures within three total render attempts per scene; preserve good clips. Save and export by default unless the user requests script-only, project-only or no export. Prefer included 1080p/high-quality MP4 settings without buying upgrades.

Video creation does not authorize GitHub edits, purchases, public posting, deletion of unrelated work or a new provider. Follow supported authentication/confirmation rules. Keep private asset/job IDs only in the run ledger, never public commits.

See [Massage Swap](../examples/massage-swap.md) for a five-scene example and [the quick-start request](../examples/stickman-request.md) for starting a new chat.

## Situation-appropriate wardrobe

Choose suitable outfits automatically from the story, time, location, activity and weather; no separate outfit-approval question is needed. Honor any explicit user choice. The reference supplies character identity rather than a compulsory blue-shirt/yellow-cardigan uniform. Neither spouse wears glasses in any outfit.

Examples:
- Nighttime bedroom or a 3 AM bathroom trip: simple pajamas, sleepwear or a light robe; keep the comedy non-explicit.
- At home during the day: relaxed casual clothes.
- Outdoors in cold/rainy weather: simple coat or rainwear.
- Work, exercise or a special occasion: a suitable simple outfit for that activity.

Plan each spouse's outfit/color before image generation and record it in the scene ledger. Repeat it in every image and motion prompt. Keep the same outfit across connected scenes at the same time/location; do not randomly switch clothes between clips. A change requires a story-motivated transition, such as getting dressed or a later-day cut. Preserve the approved identities, minimal 2D stick-figure design, full limbs and no-glasses rule. Choose distinct colors or simple flat patterns for readability, while allowing colors beyond the casual blue/yellow defaults.

If wardrobe-specific source references are needed, derive them from the approved couple without replacing the permanent identity reference or changing faces/style. Verify the actual available reference controls and inspect generated images; do not claim a setting guarantees wardrobe or identity consistency.

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
