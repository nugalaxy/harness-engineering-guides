# Contributing

This is a book, so "contributing" means something a little different than it does on a codebase.
Here is what actually helps, in the order it helps.

## Tell me where it is wrong

Open an issue. Wrong facts, broken reasoning, a number that does not add up, a claim that falls
apart at scale, an example that would not survive contact with a real production system. This is
the most valuable thing you can send, and disagreement is more useful than a star.

If you have run this at scale and something here is naive, say so plainly. I would rather hear it
from you than find out from a reader who quietly closed the tab.

## Tell me where it lost you

Equally valuable and much less often reported. If a chapter stopped making sense, or a comparison
did not land, or you had to re-read a paragraph three times, that is a defect in the writing and I
want to know which paragraph. "I got lost in Part III" is a complete and useful bug report.

## Typos and small corrections

Open an issue or a pull request, whichever is less friction for you. For a PR, edit the markdown
in `001-.../`, not the PDF. The PDF is generated and any change to it will be overwritten.

## What I cannot merge

The manuscript is licensed CC BY-NC-ND 4.0, which means no derivative versions get distributed.
Practically, for this repo:

- Corrections, clarifications, and fixes: yes, gladly.
- Rewrites of a section in your own voice, new chapters, or a restructure: no, because the series
  depends on one continuous voice across every guide. Pitch the idea in an issue instead; if it is
  right, I will write it.
- Translations: yes, and I want them, but let us talk in an issue first so the license and
  attribution are handled properly rather than retroactively.

## Suggesting a topic for a future guide

Use the topic suggestion issue template. The series exists to answer questions people actually
have, and the honest way to find those is to be told. What would you want the next one to be
about?

## A note on the PDF

`001-.../*.pdf` is built from the markdown in the same folder. Never edit it by hand. If your
change is correct in the markdown, the PDF picks it up on the next release.
