# Documentation project instructions

## About this project

- This is the customer-facing documentation site for Docent
- The main audience is customers and waitlist users
- These docs should explain what Docent is, how money is stored, which venues it supports, and how fees work
- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links
- Run `mint validate` to validate the site

## Terminology

- Use `non-custodial`, not `self-custodial`
- Use `prediction markets`, not `event markets`
- Use `perpetuals`, not `perps`, except when quoting UI or venue terminology
- Prefer `balance` over `portfolio value`, unless the UI label is specifically `Portfolio value`
- Refer to supported venues by name: `Hyperliquid` and `Polymarket`
- Mention `Privy` and `OneBalance` by name when explaining wallet infrastructure, security posture, or chain abstraction
- Treat `Lighter` as not live unless the user explicitly asks for planned work

## Style preferences

- Use active voice and second person (`you`)
- Keep sentences concise. One idea per sentence.
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- Match the tone of docs like Dreamcash and fomo: direct, plain, and low-hype
- Lead with the answer. Then explain the details.
- Be product-first. Explain the main thing the user can do before listing supporting details.
- Avoid laundry-list writing. Group details under a clear user outcome.
- Explain where the user is trading or where funds are held. Do not hide the venue.
- Separate `Docent fees` from `venue fees` and `network fees`
- Keep security language factual. Do not make claims that are not explicitly supported.
- Mention that Docent is on a waitlist when access or onboarding is relevant

## Content boundaries

- Write for customers, not internal operators or developers
- Prioritize these topics: what Docent is, how money is stored, app features, and how fees work
- Do not document internal admin tools, internal architecture, or operational runbooks unless the user asks
- Do not present `Lighter` integration as live
- Avoid minor or gamified features unless the user asks for them directly
- If a feature is planned, label it clearly as `coming soon`
