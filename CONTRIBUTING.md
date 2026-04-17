# Contributing to PM in a Box

Thank you for considering a contribution. This project only works if the industry shows up to build it. There is a place for you whether you write code or not.

## Ways to contribute

### Fix a typo or improve the copy

The landing page at `index.html` is a single HTML file. No build step. Edit it, commit, open a PR.

If you're not a developer: open an issue using the **Copy fix** template and describe the change in plain language. We'll land it for you.

### Propose a skill or plugin

See [`skills/README.md`](./skills/README.md) for the registry. To propose a new one, copy [`skills/TEMPLATE.md`](./skills/TEMPLATE.md) to `skills/<your-skill-name>.md`, fill it in, and open a PR. You can also open an issue using the **Skill proposal** template if you'd rather start a discussion first.

### Report a bug

Open an issue using the **Bug report** template. Include:
- What you were doing
- What you expected to happen
- What actually happened
- Browser and OS if it's a UI/site bug

### Write code

For substantive changes (new sections, layout rework, build tooling), open an issue first to align on direction. Small fixes can go straight to a PR.

## Pull request checklist

- Branch from `main`.
- Keep the change focused. One PR per change.
- Test locally: `python3 -m http.server 8080` and load the page.
- For copy changes, read the full section aloud after editing — the voice is practitioner-forward, not marketing-slick.
- Accessibility: make sure links are keyboard-reachable and that contrast stays readable on both light and navy sections.

## Style guide (copy)

- Write like you're talking to a peer operator, not a prospect.
- Use short sentences. Name specifics over abstractions ("extraction fees," not "data friction").
- Italics (via `<em>`) carry the emphasis color — use sparingly, for the word that matters most in a headline.
- Avoid SaaS clichés ("unlock," "empower," "leverage"). Prefer verbs operators actually use.

## Governance

This is an industry-governed project. Maintainers are operators, partners, and engineers who've earned trust through contribution. Decisions happen in the open via PRs and issues. If you want to become a maintainer, contribute consistently, help triage, and ask.

## Code of Conduct

By participating, you agree to uphold the [Contributor Covenant v2.1](./CODE_OF_CONDUCT.md). Be kind, be direct, assume good faith.
