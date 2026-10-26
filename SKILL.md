---
name: personal-portfolio
license: MIT
description: Build or refine a personal portfolio website from real work, approved references and design feedback. Use for portfolio structure, readable responsive layouts, project demos, writing, media galleries and a reviewable preview.
---

# Personal portfolio

Category: Workflow.

## Goal

Create a portfolio that lets a new visitor understand the person, explore their work and find evidence without having to decode labels or open every detail. Preserve the owner's voice and approved visual direction while making the whole site feel consistent.

## Scope and inputs

Use the existing repository and its instructions, owner-supplied content, authorized prior design feedback, selected reference sites and available media. Inspect the running site and actual source before choosing a framework or changing structure. Extend the existing implementation when it meets the need.

**Boundaries:** This skill owns portfolio content structure, presentation, interactions and review. It does not grant access to private history, rights to photographs, permission to publish private projects, or authority to change domains, accounts or production deployments. Use the receiving workspace's existing tools and authority rules for those operations.

The workspace may supply a private overlay through its agent instructions or catalogue. Read the named overlay explicitly. It can specify the repository, personal content, approved design references, preference evidence and deployment target. There is no automatic configuration loader. See the [overlay example](examples/private-overlay.example.md).

## Work from evidence

Read enough existing content and feedback to distinguish three things: explicit choices, repeated preferences, and suggestions the owner never accepted. The latest instruction and the current approved project design take precedence over older defaults. When authorized to use earlier sessions, search the workspace's designated archives; keep transcript text and source identifiers in a private evidence note. Do not infer broad taste from an assistant's generated brief.

Keep design references deliberately scoped. Record what each selected reference contributes, such as navigation or typography. Remembering a reference does not activate its whole style. Do not blend unrelated projects or copy code, assets or fonts without checking their terms.

Inspect the current route map, published articles, media, repository links and build inputs before editing. A page absent from one checkout may exist on another branch. Preserve or explicitly migrate existing content; never replace real work with a blank template because it was missed during discovery.

## Establish the page map

Make the homepage a concise introduction and set of entrances. Show a few individual projects and meaningful personal activities. Include interests when they help show a full person; a portfolio does not have to read only like a résumé.

Give a large collection its own page. A Builds page introduces projects and links once to a substantial skills registry; the registry owns its search, filters and FAQ. Writing can separate finished essays from short, unpolished memos. Media groups photos and coverage by event. Create other pages only when there is real content or an explicitly requested scaffold.

Choose primary navigation for substantial destinations. Smaller pages can be reached from relevant homepage items without getting a permanent nav entry. Avoid duplicating a homepage section as a redundant sidebar link. Preserve clear navigation back from a dedicated page or subdomain.

Write the intended page map and content moves down before restructuring. See the [fictional brief](examples/portfolio-brief.md) for a complete example.

## Make one coherent design

Use shared typography, gutters, spacing, borders and navigation across every page. Let the main content use the available width responsively. Avoid arbitrary paragraph widths that leave descriptions or FAQ rows visibly underfilled. A long essay may have a deliberate reading column; fit that column into the overall layout rather than narrowing the entire site.

Titles should identify the subject or capability in a few familiar words. Descriptions explain the useful result in plain language and may be longer when needed. Keep internal handles, repository owners, implementation labels and jargon out of the main heading unless the visitor needs them. A display title can differ from a product's canonical name.

Make cards and controls visibly identifiable. Use borders with enough contrast and weight to separate adjacent cards. A category pill explains what a card belongs to. Group search and category controls in one coherent row on wide screens; handle narrow screens with wrapping or a contained horizontal strip without overflowing the page.

Use motion to explain an interaction: a restrained expand cue, selected-card highlight or photo hover. Keep the click target large and understandable without the animation. Preserve keyboard, touch and reduced-motion behavior. See [design and interaction guidance](references/design-patterns.md) for the details that apply to the chosen pages.

## Show the work

For projects, begin with a compact summary: name, one sentence and a clear expansion control. Expand into a large demo and concise explanation, with only useful links. On wide screens, alternating demo and text placement can make a sequence easy to scan. Stack on small screens. Never expose a private repository just because its demo appears publicly.

For each public or open-source project, use one prominent, consistent "About the project" button. Link to the project page when one exists; until then, link directly to the public repository. Do not add separate source-code or installation-guide links to project cards. Keep those details on the project page or in the repository. Never link to a private repository.

A homepage project link should open the corresponding project on Builds, expand it and leave unrelated projects collapsed. Stable anchors must work on an initial load, a hash change and browser navigation. Avoid repeating the same heading after expansion when the summary already supplies it.

For an essay accompanied by video, consider a sticky video column beside the reading content when both remain usable. Stack the video above the essay when space is insufficient. Keep playback user initiated and avoid downloading the full video before it is wanted. If media or captions are missing, identify that gap; do not claim an unavailable demo works.

Photos enlarge as photos, with an obvious close control and keyboard dismissal. Article links remain distinct. Give an event a clear summary; collapse its photo collection or coverage list when requested, and do not repeat its title inside the expanded region.

For a skills registry, show a short capability title, useful description, category, repository link, share anchor and a clearly named install action. Copy the owner's supplied install instructions accurately. Search should cover capabilities and intent as well as display names. If semantic search is requested, use real embeddings or another evaluated meaning model, combine it with keyword matching, and keep a usable fallback. A synonym list alone is not verified semantic retrieval.

## Implement, review and deliver

Capture the relevant starting state before editing and work in the authorized development or preview environment. Keep the established stack unless a concrete requirement demands a change. Implement actual controls rather than visual props. Use semantic HTML and native interaction patterns where they meet the design.

Run the existing build and checks relevant to what changed. Inspect the rendered result at a wide viewport, a narrow phone and a size near each changed breakpoint. Use the [acceptance checklist](references/acceptance.md), including the actual click path that prompted the change. A successful build does not prove the responsive layout or an interaction works.

Use the owner's corrections as evidence: identify the underlying pattern, check the other pages it affects, and update shared styles or components when appropriate. Recheck adjacent layouts. Save a durable preference only when the owner's authorization covers that destination. Do not turn every one-off visual choice into a global rule.

**Deliverables:** Source changes in the chosen repository; a short private `portfolio-decisions.md` in its documentation area or existing equivalent; and a preview or other review artifact that the owner can actually access. The note records the page map, chosen visual direction, significant corrections, source locations, checks and unresolved content. Keep personal evidence out of any public package.

**Done when:** The intended content remains present, primary journeys work, the site is readable across tested sizes, and the report identifies what was inspected. Distinguish a local build, a rendered browser review, a ready deployment and an accessible preview. If authentication blocks viewing, help with the supported sign-in or share route rather than reporting the login page as a rendered website. Name missing access, media, checks or content plainly and finish the independent work that remains possible.
