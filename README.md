# Personal portfolio

An agent skill for building a personal website that is easy to read and explore. It covers page structure, consistent responsive layouts, plain descriptions, project demos, writing, media and useful preview evidence.

It is a workflow, not a template, theme, website generator or hosting service. It can improve an existing site without replacing its framework or visual identity.

## Install

Clone or copy this repository as `personal-portfolio` into the skill location chosen by your workspace. Start from the workspace's agent instructions and routing rules. Register exactly one root `SKILL.md` in the agent's discovery chain; the bundled references and examples are supporting material, not additional skills.

If the skill already exists in that chain, update its canonical source rather than installing another copy. To keep personal routes or preferences separate, point your workspace catalogue to a private overlay based on the [example](examples/private-overlay.example.md). The skill does not load an overlay automatically.

## Use

Ask your agent, for example:

> Use personal-portfolio to improve this site. Keep the approved visual direction, make page widths consistent, give each project an expandable demo, and show a responsive preview. Use only the feedback and content I have authorized you to read.

The agent reads [SKILL.md](SKILL.md), inspects your repository and content, and delivers source changes, a concise decision note and review evidence. Provide media when you have it; missing videos should remain clearly identified rather than invented.

## Review and limits

This package has no runtime dependencies or custom executable. Review it using the [acceptance checklist and scenarios](references/acceptance.md). Link and metadata inspection can verify packaging; they cannot establish how reliably a new model will follow the workflow.

Portfolio examples are fictional. No personal site, transcript, font, photo or video is bundled. Publishing, account changes and production deployment follow the receiving workspace's authority rules. Release licensing must be agreed before publication.

See [SOURCES.md](SOURCES.md) for provenance and [AGENTS.md](AGENTS.md) for maintenance guidance.
