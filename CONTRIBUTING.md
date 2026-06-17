# Contributing

Thank you for helping improve this list. The goal is to keep it useful, scoped, and easy to maintain as an awesome-style resource.

## What Belongs Here

Good additions usually include at least one of the following:

- A peer-reviewed paper, arXiv preprint, technical report, or benchmark paper about LLMs, multimodal LLMs, or LLM-based agents for quantitative trading or investment research.
- A dataset, benchmark, arena, framework, or open-source tool that supports LLM-based financial forecasting, portfolio construction, factor mining, strategy generation, or trading-agent evaluation.
- A survey or practitioner guide that is directly relevant to LLM-based quantitative investment research.

## Out of Scope

Please avoid adding:

- General trading, economics, or finance resources that do not have a meaningful LLM component.
- Generic LLM resources that do not target quantitative trading, investment research, financial forecasting, or financial decision-making.
- Marketing pages, paid products, affiliate links, or claims without a paper, codebase, dataset, benchmark, or other verifiable artifact.
- Duplicate entries or near-duplicates of resources already listed.

## Entry Format

Use one bullet per resource:

```markdown
- CryptoTrade: A Reflective LLM-based Agent to Guide Zero-shot Cryptocurrency Trading (NUS, EMNLP 2024). [![Paper](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.09546)
```

Guidelines:

- Prefer canonical links, such as arXiv abstracts, DOI pages, official project pages, OpenReview pages, or maintained GitHub repositories.
- Use shields.io badge links for source labels, such as arXiv paper badges, GitHub star badges, Project Page badges, OpenReview badges, Paper badges, or Dataset badges.
- Include the institution, venue, year, or month when known.
- Keep descriptions concise and factual. Avoid promotional language.
- Add a resource to the most specific existing section. If no section fits, propose a new section in the pull request description.

## Pull Request Checklist

Before opening a pull request:

- Confirm the resource fits the curation policy.
- Check that the link is reachable.
- Check that the entry is not already listed.
- Keep formatting consistent with nearby entries.
- Run the local checks when possible:

```bash
npx awesome-lint README.md
lychee --config .lychee.toml README.md CONTRIBUTING.md
```

If a link checker reports a temporary failure for a normally stable academic site, mention it in the pull request.
