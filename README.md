# TheMizeGuy

I build developer tools that review, test, or operate the work AI coding agents produce. I also ship web, iOS, and desktop products under [Meipath](https://meipath.com), an independent software studio.

Stack: TypeScript and React on the web, Swift and SwiftUI on iOS, Lua for World of Warcraft addons, Python and shell for tooling. Before this: real-time C++ systems and test engineering on embedded Linux and VxWorks.

## Tools for AI coding agents

Claude Code plugins unless noted. Each repository has install steps and a usage guide. anti-slop, ui-craft, and apple-ui-craft also ship labeled corpora of planted defects and clean controls, with a scorer that fails when recall or precision drops ([anti-slop](https://github.com/TheMizeGuy/anti-slop/blob/master/anti-slop/scripts/measure.mjs), [ui-craft](https://github.com/TheMizeGuy/ui-craft-public/blob/main/tests/harness/score-review.mjs), [apple-ui-craft](https://github.com/TheMizeGuy/apple-ui-craft-public/blob/main/tests/harness/score-review.mjs)).

### Review and quality

- [anti-slop](https://github.com/TheMizeGuy/anti-slop): catches what AI-generated output tends to get wrong, from security holes and accessibility gaps to regressions, weakened tests, and machine-sounding prose and design. Its zero-dependency scanner CLI also runs as a CI gate.
- [ui-craft](https://github.com/TheMizeGuy/ui-craft-public): ten agents that design and review interfaces for web, iOS, Android, and desktop, covering visual design, accessibility, responsive layout, motion, performance, and TypeScript.
- [apple-ui-craft](https://github.com/TheMizeGuy/apple-ui-craft-public): seven agents that design and review iOS 26 and 27 interfaces, covering Liquid Glass and the Human Interface Guidelines, spring animation, haptics, accessibility, and rendering performance.
- [ios-code-review](https://github.com/TheMizeGuy/ios-code-review): senior iOS review for Swift, SwiftUI, and UIKit. It returns two verdicts, App Review and engineering, with evidence-tagged findings, and checks runtime behavior on a simulator when one is available.

### Operations and workflow

- [railway-operator](https://github.com/TheMizeGuy/railway-operator-public): runs Railway infrastructure tasks end to end, CLI first, then the GraphQL API when the CLI lacks a mutation, then browser automation for dashboard-only actions, verifying every change and guarding destructive ones.
- [cicd-expert](https://github.com/TheMizeGuy/cicd-expert-public): designs, reviews, optimizes, debugs, and security-audits CI/CD pipelines on GitHub Actions, GitLab CI/CD, Jenkins, Buildkite, Tekton, and five more platforms.
- [project-onboard](https://github.com/TheMizeGuy/project-onboard-public): takes a new or stale project to a consistent standard with a scaffolder script, a runbook, and a verification gate.
- [scrum-master](https://github.com/TheMizeGuy/scrum-master-public): a Kanban board for Claude Code projects, with one markdown file per story, Obsidian board views, dependency graphs, and plans for which stories can run in parallel.
- [seo-optimization](https://github.com/TheMizeGuy/seo-optimization-public): site-agnostic SEO playbook skill, sourced from Google's own documentation and tested to keep models from over-optimizing pages.

### Other tools

- [clawdagotchi](https://github.com/TheMizeGuy/clawdagotchi): an unofficial pixel-art Claude on the Claude Code status line who acts out what the session is doing, plus the status line itself. Display only: it never reaches the model or changes a tool call.
- [wow-addon-dev](https://github.com/TheMizeGuy/wow-addon-dev): an Agent Skill for World of Warcraft addon development, with starter templates, API and TOC references, the patch 12.0 migration, debugging, and packaging. Verified in Claude Code and packaged in the Agent Skills format that Codex CLI, Gemini CLI, and Copilot CLI also read.

## Products

- [BootyBayBroker](https://bootybaybroker.com): auction-house price analytics for World of Warcraft Retail, the Classic editions, and WoW Forever, with a Windows desktop companion app in beta. 14,000+ active users in the 30 days to mid-September 2026.
- [Limerino](https://limerino.com): a native Twitch chat client for iPhone and iPad, on the [App Store](https://apps.apple.com/us/app/limerino-chat-for-twitch/id6772345850) since June 2026. 2,700 active users in September 2026.

## World of Warcraft addons

- [Twitch Emotes WoW Forever](https://github.com/TheMizeGuy/WowForeverTwitchEmotes), on [CurseForge](https://www.curseforge.com/wow/addons/twitch-emotes): animated Twitch, 7TV, BTTV, and FFZ emotes for the WoW Forever client, with a visual browser, autocomplete, and favorites. Lua, with Python tooling that builds the emote packs.
- [WoW Forever Issue Reporter Hide](https://github.com/TheMizeGuy/WowForeverIssueReportHide), on [CurseForge](https://www.curseforge.com/wow/addons/wow-forever-issue-report-hide): hides the beta Issue Reporter box in the WoW Forever client while keeping F6 reporting available.
- [Crown Cosmos Callout](https://github.com/TheMizeGuy/CrownCosmosCallout): a Retail raid addon for Crown of the Cosmos, the final boss of The Voidspire in Midnight Season 1. Silverstrike Arrow callouts with automatic coordination between raid members who run it.

## Contact

Project questions and bug reports go to the relevant repository's issues. For anything else, use the contact section at [meipath.com](https://meipath.com/#contact).
