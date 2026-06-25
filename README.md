# Yite Labs Skills

A library of Claude Skills built by Yite Labs. Each one runs a focused working session that asks sharp questions and hands back a concrete next move, rather than a wall of generic advice.

## What's a skill

A skill is a folder with a `SKILL.md` inside. The Markdown is the source of truth: it's what gets reviewed, edited, and versioned here. A skill becomes installable by packaging that folder into a `.skill` file (a zip), which is attached to a release rather than committed to the tree.

## Skills in this repo

| Skill | What it does |
| --- | --- |
| [`yite-labs-help-me-on-ai-journey`](./yite-labs-help-me-on-ai-journey) | A collaborative working session that helps anyone work out where AI actually helps their business and team, and what to do first. Diagnoses where they sit on a three-phase journey (get on the field, go after the painful work, change how the company runs) and ends with a concrete output shaped to that. |

## Installing a skill

Grab the packaged `.skill` file from the [Releases](../../releases) page and add it through the skills interface in Claude. Don't install the `.skill` files from the source tree if they aren't there, the tree holds source, releases hold the installable build.

## Editing a skill

Edit the `SKILL.md` in the relevant folder. To produce an installable build afterwards, package the folder into a `.skill` and attach it to a new release.

## Conventions

- One folder per skill. The folder name matches the skill's `name` in its frontmatter.
- Source lives in the tree as `SKILL.md`. Packaged `.skill` files live on releases.
- Australian English. Plain language. No consultant-speak.
