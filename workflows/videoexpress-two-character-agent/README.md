# VideoExpress Two-Character Video Agent

A browser-automation agent for VideoExpress.ai. The user uploads **two consistent-character images** and a story idea. The agent makes either a **10-second clip** or a **30-second video** (three 10-second scenes merged in the VideoExpress timeline), with planned scene transitions and consistent framing, then saves and exports it.

## Files
- `SYSTEM_PROMPT.md`: the full system prompt (~21k characters). Use it as-is in Claude, or as a ChatGPT Knowledge file.
- `SYSTEM_PROMPT_COMPACT.md`: under 8,000 characters, for the ChatGPT Custom GPT **Instructions** field (that field has an 8,000-character limit). It defers to the full file.

## Setup
**Claude (Claude in Chrome / computer use, or a Project):** paste `SYSTEM_PROMPT.md` into the Project instructions (or the first message). Sign into app.videoexpress.ai in the browser the agent controls. Start a chat by attaching the two character images and the story idea.

**ChatGPT (agent mode / Custom GPT):** put `SYSTEM_PROMPT_COMPACT.md` in Instructions and upload `SYSTEM_PROMPT.md` under Knowledge. Enable the agent/browser capability. Sign into VideoExpress in the agent browser when asked.

## Example request
```text
Here are my two characters (image 1 = Maya, image 2 = Leo). Make a 30-second vertical video: Maya surprises Leo with the old key to the treehouse they built as kids, they race to the backyard, and find it still standing. Use my signed-in VideoExpress account; generate, assemble, Auto Align, save and export. Don't buy or publish anything.
```

## What the prompt enforces
- Two references stay fixed: Reference Photo 1 = Character A and 2 = Character B, plus word-for-word identity tags in every prompt.
- A continuity table where each scene's last frame is the next scene's first frame, plus fixed set layouts, one camera side and one lighting logic.
- A planned transition for each join: match on action, camera-move bridge, exit/entry, or a dissolve only for time/place jumps.
- Cropping safety: same ratio in project, dialog and images; a safe area for 9:16 social UI; uniform fill in the timeline; join trims of at most 0.5 s.
- Video prompts in one flowing present-tense paragraph: shot → scene → action beats → characters (physical cues) → one camera move with its end framing → end state → audio last, with dialogue in quotes at about 20 words per 10 s.
