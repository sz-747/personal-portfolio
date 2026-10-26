# Review evidence

Inspect the items relevant to the task. Record viewport sizes, routes, actions and observed outcomes in the destination project's decision note. A checked box without the associated observation is not evidence.

## Site acceptance

- Compare main-column and gutter alignment on every affected page at the same viewport.
- Inspect a phone around 360px wide, a wide screen around 1440px, and the changed breakpoint. Check for overflow, clipped text, squashed demos and navigation collisions. These are sample sizes, not a promise to support only three devices.
- Use real long titles and descriptions. Confirm FAQ answers wrap naturally across available space and body text is readable at default zoom.
- Compare the before/after route inventory. Existing articles, photos and project entrances remain reachable or have an explicit approved migration.
- Follow a homepage project link. Its corresponding Builds section opens on initial load; unrelated projects remain collapsed. Check another hash and browser back.
- Open and close a project with keyboard and pointer. Confirm the expanded layout stacks and its video controls remain usable on a narrow screen.
- For an essay with video, inspect the sticky boundary after scrolling, the narrow layout, user-initiated playback and the loading policy. State separately whether playback itself was tested.
- Open a gallery image with keyboard or pointer. It enlarges the image, closes by its controls and Escape, and returns focus. An article link opens the article instead.
- Check collapsed event and article-list defaults, visible labels and absence of redundant expanded headings.
- Search the registry by exact title, repository name and a paraphrase. Combine search with categories. Clear the query while an asynchronous result is pending. Test an unrelated query and unavailable semantic backend. Exact keyword results must remain available.
- Copy an install prompt and a share link. Verify the actual clipboard or the honest fallback, and follow the shared anchor.
- Check reduced motion and a touch-friendly route to any action otherwise revealed on hover.
- Run the project's existing build and checks appropriate to the edited behavior. Inspect the deployed route too when publishing was authorized.
- Confirm that the owner can access the delivered preview. Identify authentication requirements and distinguish content verification from a blocked browser review.

## Author walkthrough scenarios

| Scenario | Expected outcome |
|---|---|
| An older global note says dark UI; the current approved portfolio is warm and light | Preserve the project's current design. Keep the older preference scoped to its original use. |
| A saved external design reference is unrelated to the current project | Record it as available, without blending its style into this site. |
| A registry has grown too large for the Builds page | Give it its own search page and one clear entrance from Builds. |
| A FAQ answer wraps early while much of its row is empty | Remove the accidental width cap and verify the shared pattern on other affected pages. |
| A visitor searches for a task whose words differ from the chosen title | Search descriptions and meaning; preserve exact matches and degrade clearly when the semantic component is unavailable. |
| Two essays exist on an older branch but are missing from the current tree | Inspect and recover the intended content; preserve unfinished status and do not replace it with an empty scaffold. |
| A project is private and has only screenshots | Show the authorized demo without an invented video or public source link. |
| A protected preview opens to login | Report the access boundary and arrange supported access; do not claim a rendered layout review. |

These scenarios define expected behavior. They are not claims that a new model or fresh agent session has executed the skill successfully. The skill's original source portfolio is a worked source of requirements, not a controlled behavioral evaluation of this new package.
