# oss-license-picker

Pick the right open source license for your project. Four questions, plain-English summaries, full license text ready to paste. Single HTML file, browser-only.

**Live demo:** https://0xelitesystem.github.io/oss-license-picker/

## Why

Choosing a license is a 10-minute task that most developers turn into a 0-minute task by defaulting to MIT. MIT is fine for most projects, but not all. If you're building a library that touches patentable techniques, or a product you'd rather not have wrapped into a closed-source competitor, the right answer is different.

This tool walks you through the questions that actually matter and gives you the license text with your name and year filled in.

## Use it

Open `index.html` in any browser. Or visit `https://0xelitesystem.github.io/oss-license-picker/` once Pages is enabled.

1. Answer up to 4 questions about copyleft, patents, and attribution
2. Get a recommendation with plain-English summary
3. Type your name and year into the form
4. Click Copy, paste into a file named `LICENSE` in your repo root

## Licenses covered

The 8 most common OSI-approved options:

- **MIT**, most popular permissive license
- **Apache 2.0**, permissive with patent grant
- **BSD 2-Clause**, minimalist permissive
- **BSD 3-Clause**, permissive with no-endorsement clause
- **GPL-3.0**, strong copyleft
- **AGPL-3.0**, copyleft that closes the SaaS loophole
- **MPL-2.0**, file-level weak copyleft
- **The Unlicense**, public domain dedication

For each one, the result page shows: when to use it, the trade-offs, why-not-the-others comparison notes, and the full license text with your name and year filled in live.

## What it doesn't do

- Doesn't cover commercial / source-available licenses (BSL, Elastic License, Sustainable Use). Those aren't OSI-approved open source.
- Doesn't handle dual licensing decisions.
- Doesn't audit your dependencies for license compatibility. Use a tool like `licensee` or `pip-licenses` for that.
- Doesn't give legal advice. The author of this tool isn't a lawyer.

## Tech

- Single HTML file
- Vanilla JS, no frameworks, no build step
- All license text embedded; no external requests
- Light and dark themes with OS preference detection
- WCAG AA contrast on both themes
- Keyboard accessible

## License

This tool itself is MIT licensed. See [LICENSE](LICENSE).

## Related

- [legal-pages-starter](https://github.com/0xelitesystem/legal-pages-starter), Terms, Privacy, Disclaimers templates for your product
- [oss-readme-template](https://github.com/0xelitesystem/oss-readme-template), README structure for OSS projects
- [solo-saas-launch-checklist](https://github.com/0xelitesystem/solo-saas-launch-checklist), pre-launch checklist for indie products
