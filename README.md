# PM in a Box — pm-in-a-box.org

**An open-source AI agentic harness for property management operations. Built and maintained by the PM industry, for the PM industry.**

This repo is the landing page at [pm-in-a-box.org](https://pm-in-a-box.org). It exists to recruit operators, partners, and engineers into the project and to serve as the public front door for the community.

## What is PM in a Box?

PM in a Box is an official fork of [biz-in-a-box.org](https://biz-in-a-box.org), focused on property management. "PM" stands for Property Management. The project's goal is to give every PM operator a self-hostable AI harness that runs on **their** data, with skills and plugins contributed by the industry.

The underlying thesis: property management data has been held hostage by vendor lock-in for decades. AI has raised the stakes on that lock-in. The industry's answer is to build and govern its own agentic harness, in the open.

## Principles

1. **Full control over your data** — your PMS data never leaves your infrastructure without your say.
2. **Fully open source** — AGPL-3.0 licensed, every line readable. Modifications must be shared back.
3. **FREE to self-host** — no seat fees, no per-unit fees.
4. **Built by the PM industry** — governed and maintained by operators and partners in the field.

## How to contribute

There are three lanes:

- **Operators** — install it, run it, open issues when it breaks, star the repo so other operators find it.
- **Partners** — contribute a skill or plugin (bookkeeping, comms, DNS, websites, data backup, …). See [`skills/README.md`](./skills/README.md).
- **Engineers** — PRs welcome, typo fixes to architecture. See [`CONTRIBUTING.md`](./CONTRIBUTING.md).

## Local preview

This site has no build step. To preview locally:

```sh
python3 -m http.server 8080
# or
npx serve .
```

Then open <http://localhost:8080>.

## Deploy

GitHub Pages serves from `main` at the repo root. The `CNAME` file pins the custom domain to `pm-in-a-box.org`. DNS at the registrar should point:

- Apex `pm-in-a-box.org` → GitHub Pages A records: `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
- `www.pm-in-a-box.org` CNAME → `<org>.github.io`

## License

AGPL-3.0. See [`LICENSE`](./LICENSE). If you modify and distribute this software — or run it as a network service — you must release your source under the same license.

## Code of Conduct

This project follows the [Contributor Covenant v2.1](./CODE_OF_CONDUCT.md).
