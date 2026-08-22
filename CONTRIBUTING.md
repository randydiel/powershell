# Contributing

This is an alliance reference. Its only value is that members can trust it
without double-checking in chat.

## Policy pages are not open edits

Pages under [`docs/rules/`](docs/rules/README.md),
[`docs/governance/`](docs/governance/README.md), and
[`docs/partnerships/`](docs/partnerships/README.md) record **decisions**,
not opinions.

1. **Get the decision first.** Raise it per the decision table in
   [governance](docs/governance/README.md). A pull request is how a decision
   gets written down — not how it gets made.
2. **Restamp the approval.** Update the `Approved by` line with the
   approving leader and the date.
3. **Announce diplomacy changes.** Members do not re-read pages on their
   own; a standing change that is only in git has not reached anyone.

## Reference pages are open

[Glossary](docs/reference/glossary.md),
[gift codes](docs/reference/gift-codes.md), and
[gameplay basics](docs/reference/gameplay-basics.md) take edits from any
member. Two rules:

- **Observe, don't copy.** Gameplay numbers come from the live game, not
  from another guide site. Stamp the build they were seen in.
- **Verify codes before listing them.** A dead code wastes a reader's time
  and costs trust in every other page.

## Adding a page

1. Copy [`docs/_template.md`](docs/_template.md) into the right section.
2. Link it from the section README and the lookup table in the root
   [README](README.md).
3. Run `npx --yes markdownlint-cli2` before opening a pull request.

## Style

Optimise for lookup, not for reading start to finish.

- Lead with the answer, then the reasoning.
- Tables for anything comparative — most lookups end in a table.
- Short sections with specific headings; people scan headings.
- Write criteria as observable facts, not judgement calls.
