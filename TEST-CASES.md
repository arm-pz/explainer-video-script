# Test cases: explainer-video-script

## Executed (2026-11-13)

Claude Code 2.1.323, skill installed in a fresh project next to other skills (docx, pptx, xlsx, pdf, design, searchfit-seo, remotion), each prompt sent with `claude -p` in a new session; first Skill call recorded.

| Prompt | Expected | Loaded | Result |
| --- | --- | --- | --- |
| Write a script for our 1-minute product video. | should load | explainer-video-script | pass |
| Our video editor needs to know what to film and what the voiceover says for the launch clip. | should load | explainer-video-script | pass |
| Script and shot list for a 60-second ad for our invoicing app. | should load | explainer-video-script | pass |
| Animate a glowing search bar overlay for my CapCut edit. | should not load | anthropic-skills:remotion-capcut-motion-graphics | pass |

**4 pass, 0 fail.**

## Reviewed only (read from descriptions, not executed)

| # | Type | Message | Expected | Result |
|---|---|---|---|---|
| 1 | C | "Write a script for our product video" | explainer-video-script | pass |
| 2 | C | "I need a 1-minute explainer for the app" | explainer-video-script | pass |
| 3 | C | "Script and shot list for a 60-second ad" | explainer-video-script | pass |
| 4 | I | "Our video editor needs to know what to film for the launch clip" | explainer-video-script | pass |
| 5 | I | "What should the voiceover say in our promo?" | explainer-video-script | pass |
| 6 | N | "Animate this search bar for my CapCut edit" | remotion-capcut-motion-graphics | pass |
| 7 | N | "Write a 20-minute YouTube script" | none of these | pass |
| 8 | N | "Add a table to script.docx" | docx | pass |
