# Harness Engineering Series

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21453137.svg)](https://doi.org/10.5281/zenodo.21453137)
[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-blue.svg)](https://creativecommons.org/licenses/by-nc-nd/4.0/)

Free short books about the engineering problems that show up after the demo works.

Every guide follows one person through one real mess. No lectures, no jargon wall, no
prerequisites beyond knowing what a test is. If a comparison explains something better than a
definition, you get the comparison.

---

## Guide 001: How Do You Know Your AI Agent Actually Works?

> Friday, 5:47 PM. James presses deploy and goes home. He has spent three weeks building a
> support agent. He wrote 340 tests for it. Every one passed.
>
> Monday, 8:58 AM. His phone buzzes. Then again. Then it does not stop.

James's tests all passed because he wrote the test inputs himself. Real customers write the way
they text a friend. This guide is the three months he spent learning how to know his agent works
before production tells him it does not.

**[Download the PDF](001-how-do-you-know-your-ai-agent-actually-works/how-do-you-know-your-ai-agent-actually-works.pdf)**
or read it [chapter by chapter](001-how-do-you-know-your-ai-agent-actually-works/).

**What you get:**

- Why traditional testing breaks on systems that do not think in straight lines
- How to judge behavior instead of output, and why that distinction is the whole game
- Building your first evaluation dataset and rubric from scratch
- When to use code judges, human judges, and AI judges, and what each one is bad at
- Taking all of it to production without pretending the problem is solved

Read it if you have shipped an agent and quietly wondered whether you would notice it going
wrong. Or if you have not shipped one yet and would like to skip James's Monday.

**Next in the series:** Building Your First Evaluation Dataset

---

## Reading online vs the PDF

The markdown files are the same text as the PDF. The PDF has the layout, the comics in place,
and the cover, so it is the better read. The markdown is here so the guide is searchable,
linkable, quotable, and open to corrections.

## Found a mistake? Disagree with something?

[Open an issue](https://github.com/nugalaxy/harness-engineering-guides/issues). Corrections make
the next version better, and disagreement is more useful than a star. If a chapter did not land,
saying so is a real contribution and there is an issue template for exactly that.

There is also a template for suggesting what the next guide should be about. The series answers
questions people actually have, and the only honest way to find those is to be told.

See [CONTRIBUTING.md](CONTRIBUTING.md) for what helps most.

## Citing this

The guide is archived on Zenodo and has a DOI, so it can be cited in a paper, a thesis, or a
reading list like any other book.

**DOI: [10.5281/zenodo.21453137](https://doi.org/10.5281/zenodo.21453137)**

That is the concept DOI: it always resolves to the newest version, so a citation written today
still points somewhere sensible after guide 001 gets a second edition. If you need to pin the
exact 1.0 release instead, use [10.5281/zenodo.21453138](https://doi.org/10.5281/zenodo.21453138).

> Mohseni, S. (2026). *How Do You Know Your AI Agent Actually Works?* (Version 1.0).
> Zenodo. https://doi.org/10.5281/zenodo.21453137

GitHub's "Cite this repository" button in the sidebar will format it in other styles, and
`CITATION.cff` has the machine-readable version.

## License

The text and comics are released under
[CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/). Share it, print it,
send it to your team, use it to teach. Do not sell it or publish an altered version under your
own name. Want to translate it or excerpt it somewhere? Open an issue, the answer is usually yes.

## The tool behind the guides

The same people who write these guides build developer tools that run on your machine. No GPU,
no cloud account, no vendor lock-in.

**[dugalaxy](https://github.com/nugalaxy/dugalaxy)** fills an empty database with realistic,
reproducible test data. You describe your data in a sentence and get back a template you can run
again, share with your team, and commit next to your code. Same template, same data, every time.

```bash
pip install dugalaxy
```

## Who made this

Written by Sara Mohseni, who has been a developer, a product designer, and a product manager,
and is self taught all the way. That is why these guides teach the way she learned best: a real
problem, a real mess, and someone in the middle figuring it out. Poor James.

Built by [nugalaxy](https://github.com/nugalaxy), where the tools are: try
[dugalaxy](https://github.com/nugalaxy/dugalaxy). More writing at
[nugalaxy.ai/blog](https://nugalaxy.ai/blog).
