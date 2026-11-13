# explainer-video-script

Writes a 60-second explainer video script (about 150 spoken words) and a shot list table in one Word file, so a video editor can start without a call: problem in the first 5 seconds, the product's fix in 3 steps, one call to action, timings that add up to 60 seconds.

It asks the questions your material leaves open (each with a default) before it builds anything, then runs a "Done means" check and reports the result.

## Install

- Upload `explainer-video-script.zip` in your Claude skills settings, or
- Copy this folder into `~/.claude/skills/explainer-video-script/` (Claude Code), or
- `npx skills add arm-pz/explainer-video-script`

Check: start a new session and confirm `explainer-video-script` appears in the skill list.

## Try it

- "Write a script for our 1-minute product video."
- "Script and shot list for a 60-second ad for our invoicing app."

## Boundaries

See the description in `SKILL.md`: the "Not for" clause names which skill takes each excluded request.

## Test results

Version 0.1.0: 4 pass, 0 fail executed live. Details in `TEST-CASES.md`.

## Credits

Prompt adapted from the freelancer workflows thread by @claudeskills101 on X.

## Version

See CHANGELOG.md.
