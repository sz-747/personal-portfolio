# Portfolio design and interactions

Apply these patterns when they serve the content and the owner's current direction. They are not requirements to put every feature on every site.

## Width and reading

Create one responsive page shell. The same viewport should give the homepage, Builds, writing index, registry and Media the same outer gutters and main-content alignment. A sidebar can remain narrow while the main column grows. On phones, navigation becomes a compact, wrapping bar or another accessible mobile pattern.

Avoid page-specific width overrides that make one destination feel squeezed. Introductory descriptions, FAQ answers and card descriptions should occupy their available row. Do not force text to stay on a single line; allow it to wrap naturally. A short answer should not wrap early merely because a leftover `max-width` caps it. Constrain sustained reading deliberately, such as an essay beside its video.

Typography should be comfortably readable at the default zoom. Scale headings, body text and spacing together rather than enlarging only the title. Check long titles, real descriptions, category labels and the smallest action text, including collapsed summaries.

## Hierarchy and wording

Use a short title such as "Skill Creation" or "Design Review", then explain the result in one or two clear sentences. Avoid labels that only make sense to the builder. Repository metadata can sit below the main title; omit redundant account prefixes from display copy.

Give important actions explicit labels. A visible expansion cue should be large enough to notice and work as part of the whole summary target. Prefer one clear entrance to a registry over two adjacent links to the same place. Do not duplicate an event or project title just below the summary the visitor opened.

Do not create newsletter signup, empty social destinations or subscription UI just to fill a layout. Keep incomplete or deferred features distinct from the current publication. An RSS subscription and an email newsletter are separate capabilities; any advertised subscription path must work.

## Project demos

Collapsed state: name, a useful one-sentence summary and an expansion affordance. Expanded state: a large video or image, the problem addressed, how it helps, relevant status and a few links. A private project's demo can be public without a source-code link. Avoid "open source" labels on private work.

Alternate large media and copy across a sequence on desktop if it helps scanning. Use one sensible reading order on phones. Video gets enough space to show the interface; do not shrink it to a decorative thumbnail. Use controls, inline playback on supported phones, a poster when available and captions when supplied. Keep missing captions visible as a content gap in the delivery note.

Initial project anchors must expand their intended section. When a visitor follows a homepage project link, avoid requiring another click on Builds. Hash changes, back navigation and direct external links should keep the active project understandable. A normal arrival without a project anchor leaves summaries collapsed unless directed otherwise.

For an essay, a side-by-side player can remain sticky within the article boundary. The breakpoint depends on both usable video size and readable text. Remove stickiness and stack when either becomes cramped. Never cover text or trap the player at phone sizes.

## Media and personal pages

Group coverage by event, with date and location when known. A photograph represents a photo action; clicking it opens an enlarged view. Coverage titles are distinct article links. A photo lightbox needs an accessible name, close button, Escape behavior, focus handling and a backdrop that does not accidentally close when the image itself is clicked.

A photo fan or other hover treatment needs keyboard and touch access, an inspectable focused image, and no overlap that hides every actionable image. Provide sensible image dimensions and meaningful alternative text. Do not crop out the subject merely to fit a card.

Keep interests, activities and informal memos in the owner's voice. They can show life outside work without becoming inflated professional claims. Navigation prominence should reflect the significance and amount of current content, rather than making every small activity a primary section.

## Registry search and installation

Give each item a stable slug, category label and distinct repository and share actions. A copied link should clear conflicting filters, reveal and highlight the intended card. Clipboard failure needs a usable manual-copy path. A success message must correspond to an actual completed copy.

Filter by category and search together. Search capabilities, descriptions and useful metadata as well as titles. When adding meaning search, pin the embedding model and its vector dimension, use the same model for query and corpus, normalize and rank consistently, and evaluate paraphrases plus unrelated queries. Weight exact matches clearly; do not hide a literal match because a model ranks it poorly.

Keep keyword matching available during loading or failure. Avoid showing stale results after someone clears or changes the query. Label real fallback behavior honestly. For a tiny public catalogue, use a small search component; do not index personal archives or introduce an account-heavy service without a concrete need.

The install action should name its outcome, such as "Add to your agent". The prompt should identify the public repository, follow the receiving workspace's routing, expose one root skill and keep personal setup in a private overlay. Do not silently install on the visitor's machine.
