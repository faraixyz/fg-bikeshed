# FG Bikeshed

Where I overthink how my Hugo websites work.

## Defaults

* Regarding the markdown configuration, the built-in render hooks are enabled, block attributes are enabled, standalone images aren't surrounded by a `<p>` tag so that block attributes work, HTML in markdown files isn't escaped and extra markdown elements are enabled.

## Page Notes (TODO)

To add notes to a post (for edits, explinations and updates), add a `notes` array to the frontmatter where each element has a date, explainatory note and the type of note (optional but of type note, update and hotfix—default: hotfix).

```yml
---
notes:
    - date: 2024-06-19T22:06:34+02:00
      type: hotfix
      notes: Didn't think this through, just needed something to write here.
---
```
