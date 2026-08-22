# Contributing

## Sourcing rules

This guide is only useful if its numbers are trustworthy. Two rules:

1. **Observe, don't copy.** Every stat, cost, timer, and drop rate must come
   from the live game, not from another guide site or a wiki mirror.
2. **Stamp the version.** Each page carries a `Verified against` line naming
   the game build the data was observed in. Unstamped numbers get removed.

If you cannot verify a figure, write the mechanic in prose and leave the
number out. A correct explanation with a missing number is more useful than
a confident wrong one.

## Adding a page

1. Copy [`docs/_template.md`](docs/_template.md) into the right section.
2. Fill in the front-matter block at the top.
3. Link it from the section `README.md` and from the table in the root
   [`README.md`](README.md).
4. Run `npx --yes markdownlint-cli2` before opening a pull request.

## Style

- One idea per heading; prefer short sections over long ones.
- Lead with the recommendation, then the reasoning.
- Use tables for anything comparative (heroes, buildings, costs).
- Avoid second-person hype ("you NEED this") — state the tradeoff instead.
