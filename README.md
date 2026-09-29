# TheMizeGuy

I build developer tools for AI coding agents, along with web and native apps. I use Claude Code and Codex, and build tools to test and review the work they produce.

## Code to explore

| Project | What it does | Implementation and tests |
| --- | --- | --- |
| [anti-slop](https://github.com/TheMizeGuy/anti-slop) | A JavaScript CLI that checks code and prose for security, accessibility, and quality problems. | [Scanner](https://github.com/TheMizeGuy/anti-slop/blob/master/anti-slop/scripts/lib/scan.mjs) · [Labeled evaluation](https://github.com/TheMizeGuy/anti-slop/blob/master/anti-slop/scripts/measure.mjs) |
| [ui-craft](https://github.com/TheMizeGuy/ui-craft-public) | Tools for inspecting and reviewing web interfaces, with checks for missed issues and false positives. | [Review scorer](https://github.com/TheMizeGuy/ui-craft-public/blob/main/tests/harness/score-review.mjs) · [Test fixtures](https://github.com/TheMizeGuy/ui-craft-public/tree/main/tests/corpus) |
| [apple-ui-craft](https://github.com/TheMizeGuy/apple-ui-craft-public) | SwiftUI review tools with a labeled regression corpus and precision/recall gates. | [Review scorer](https://github.com/TheMizeGuy/apple-ui-craft-public/blob/main/tests/harness/score-review.mjs) · [Tests](https://github.com/TheMizeGuy/apple-ui-craft-public/tree/main/tests) |

I also build [Twitch emotes for WoW Forever](https://github.com/TheMizeGuy/WowForeverTwitchEmotes): a Lua addon with animated emotes, a searchable browser, and chat completion, plus Python tools for building and packaging its assets.

For project questions, use the relevant repository's issues or discussions.
