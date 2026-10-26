# Fictional portfolio brief and result

## Input

A designer and engineer has an existing static site with an approved warm-paper theme, large body type and a right navigation rail. They want to show three projects, a reusable-skills collection, essays, quick notes, press photos, and hiking. One project is private; two have demo videos. They dislike dense pages, unexplained technical labels and narrow FAQ answers. The current site's typography wins over an older dark-dashboard preference.

## Chosen page map

| Route | Content and entrance |
|---|---|
| `/` | Introduction, three individual project summaries and a short activities list |
| `/builds/` | One link to the skills collection, followed by expandable project demos |
| `/skills/` | Search, category pills, install prompts and FAQ |
| `/writing/` | Essays and a separate entrance to informal notes |
| `/writing/notes/` | Dated, unpolished observations |
| `/media/` | Event summaries that expand into photos and coverage |
| `/hiking/` | A small personal page reached from the homepage |

Primary navigation: About, Builds, Writing, Media. Hiking is reachable without a permanent primary item. The private project has authorized screenshots and no repository link. Its summary is a concrete description of what it helps someone do.

## Behavior

A homepage link to `/builds/#trail-map` opens Trail Map's details, scrolls to the project and leaves the other projects collapsed. Demos alternate sides on wide screens and stack on phones. A shared skill anchor clears filters and highlights that card. The photo action enlarges a photograph; the article title opens the coverage link. An essay's video stays beside the text only when both columns have useful space.

## Decision note excerpt

Preserved the existing theme and shared navigation. Used one responsive outer shell for all routes. Kept FAQ answers at their available width; gave sustained essay reading a deliberate column. Renamed an internal capability label to "Research Notes" and explained its outcome in the description. Preserved two existing essays, including one unfinished draft. Source references and personal asset paths remain in this project's private inventory.

Acceptance requires observations from the project's build and rendered routes at the chosen sizes. This fictional brief supplies expected behavior only; no fabricated check output, screenshots or deployment URL is attached.
