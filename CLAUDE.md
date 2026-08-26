# Orkas Docs Publishing Rules

This repository is Orkas's official GitHub content hub. Its public Issues are search-facing guides for agents, use cases, comparisons, and articles; the README files are the catalog.

## Repository Ownership

- Use the `Orkas-AI` GitHub account for every GitHub operation in this repository, including `gh` API/CLI writes, Issue and label management, settings changes, commits, and pushes. Before any remote write, verify that `Orkas-AI` is the active authenticated account and that the target repository is `Orkas-AI/Orkas-Docs`; never use a personal account or personal fork.

## Language And Pairing

- Publish every topic as exactly two separate Issues: one English Issue and one Simplified Chinese Issue. Never combine both languages in one Issue.
- Create, review, publish, archive, and materially update both language versions together.
- Apply one shared `topic:<slug>` label to both versions, plus exactly one language label: `lang:en` or `lang:zh-CN`.
- Localize the Chinese version for natural Chinese search intent; do not produce a literal line-by-line translation.

## Issue Types And State

- Apply exactly one content-type label: `type:agent`, `type:use-case`, `type:comparison`, or `type:blog`.
- Apply `status:published` only after the content and its paired language version are ready.
- A live page is an Open, Locked Issue. A replaced or obsolete page is Closed and remains Locked.
- Keep GitHub Discussions disabled and the repository Issue creation policy set to `COLLABORATORS_ONLY`.
- Lock every Issue immediately after creation. Do not use Issue comments for updates or corrections; edit the Issue body instead.

## Search-Facing Content

- Write a natural search-facing title without internal prefixes such as `[Agent]` or `[SEO]`; labels own classification.
- Start the body with a standalone summary suitable for GitHub's meta description: roughly 140-160 characters in English or 60-90 Chinese characters. Put no image, badge, heading, or link before it.
- Each Issue must independently help the reader: explain the goal, good-fit and poor-fit cases, required inputs, workflow, deliverables, limitations, and an actionable example as applicable.
- Do not create thin keyword variants, doorway copy, or a duplicate of the corresponding orkas.ai landing page.
- Do not link Issues to other Issues. The README catalog owns discovery; each Issue sends the reader directly to the matching orkas.ai page.
- Add `source=gh-orkas-docs` to every orkas.ai content or download link. Chinese targets also use `lang=zh`.
- End with `Official Orkas guide · Last verified: YYYY-MM-DD` or the localized Chinese equivalent.

## Product Accuracy

- Verify agent behavior, model access, platform support, pricing, privacy, security, and data-flow claims against the current orkas.ai page and the current Orkas product before publishing.
- State the model boundary precisely: own-provider credentials stay local and calls go directly to that provider; optional Orkas-managed models use the managed model service.
- Do not fabricate or reuse stale ratings, reviews, install counts, source counts, awards, or performance claims.

## Publish Verification

- Render the body with GitHub-flavored Markdown before publishing.
- Confirm the official target URL returns successfully and contains `source=gh-orkas-docs`.
- After creation, verify the Issue is Open, Locked, has zero comments, and has the required type, status, language, and shared topic labels.
- Before making the repository public, verify every published topic has both language Issues and that `issueCreationPolicy` is still `COLLABORATORS_ONLY`.
