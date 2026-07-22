# Contribution Guidelines

Thank you for your interest in contributing to Awesome Chess. Please read the following guidelines before you submit a pull request or open an issue.

This is a curated list, not a collection. Every submission must clear **two bars**: the [eligibility signals](#1-eligibility-signals) (objective minimums) and the [editorial fit](#2-editorial-fit) (curation). Meeting the numbers does not guarantee inclusion, and these criteria apply to everyone — including entries added by the maintainer.

## Before You Submit

- Make an individual pull request for each suggestion.
- Use [title case](https://titlecase.com) for new headings.
- Use the following format: `- [Name](link) - Description.`
- Start the description with a capital letter and end it with a period.
- Keep descriptions short, objective and ideally under 100 characters. No marketing taglines.
- Check your spelling and grammar.
- Remove any trailing whitespace.
- Add new entries to the bottom of the relevant category (not alphabetized inside a category).
- New categories or improvements to the existing categorization are welcome, but please explain the rationale in the PR description.
- Provide a meaningful commit message. For example: `Add Fairy-Stockfish to Engines`.
- **If you built the resource or are affiliated with it, say so in the PR.** Self-submissions are welcome and judged on the same criteria as everything else — but undisclosed self-promotion will be closed without review.

## 1. Eligibility Signals

The resource must show at least one objective, publicly verifiable signal of a real audience. Paste the proof (a link) in your PR — the reviewer should not have to go looking for it.

| Resource type | Minimum signal |
|---|---|
| GitHub/GitLab repository | 3+ months old **and** ~50 stars (25+ considered with strong evidence elsewhere) |
| npm / PyPI package | ~250+ weekly downloads, or documented use by a known project |
| Browser extension | ~1,000+ users on the extension store |
| Mobile app | 1,000+ installs on Google Play, or 100+ ratings on the App Store |
| Website or service | Any **two** of: online for 12+ months, organic community discussion (Reddit, Hacker News, Lichess forums), an active community of its own (verifiably active, not just a member count), coverage by an identifiable chess publication |

Whatever the numbers, projects **less than 30 days old are deferred by default** — see [Deferrals](#deferrals).

### Hidden Gem Exception

A resource below the thresholds may still be considered, but only if the PR satisfies **all** of the following:

- Any affiliation is clearly disclosed.
- The resource solves a distinct problem not already covered by existing entries. "Yet another X" is not eligible.
- The PR names the closest existing entries and explains the practical difference.
- The resource is usable today, documented, and not a placeholder or closed beta.
- There is some quality evidence: open source code with tests, a public methodology, real user discussion, an independent mention, or a demonstrably non-trivial implementation.

## 2. Editorial Fit

- **Active**: commits, releases, posts, or episodes within the last 12 months.
- **Distinct value**: adds something the existing entries do not (a capability, a language, a format, a niche).
- **Category saturation**: when a category already contains three or more similar tools, a new one must demonstrate a substantial practical difference — not a variation in presentation.
- **Accessible**: at least a significant portion of the resource is available in English.
- **Reputable**: no referral-only sites, paywalled black boxes, self-promotional fluff, or AI-generated low-effort content.

### Channels, Streamers and Podcasts

The **YouTube Channels**, **Twitch Streamers** and **Podcasts** sections are the most subjective, so entries must clear a higher, objective bar:

- **Substantial audience**: at least 50k subscribers/followers on the linked platform. Smaller channels can still qualify if the creator is a titled player or otherwise notable, but say so in the PR.
- **Recently active**: has published a video, stream, or episode within the last 6 months.
- **Chess-focused**: chess is the primary subject of the channel, not an occasional topic.
- **Distinct value**: adds something the existing entries do not (a language, a format, a niche). Duplicates of what is already covered will not be accepted.

Entries that no longer meet these criteria (inactive, renamed, or gone dark) may be removed.

## Deferrals

A closed PR is usually a "not yet", not a "no". If your project was declined for maturity or audience, come back after ~3 months with evidence (usage, organic discussion, growth) and open a new PR referencing the old one. Maturity is the one criterion that fixes itself.

## Pull Request Process

1. Fork the repository and create your branch from `main`.
2. Add your entry following the formatting rules above.
3. Make sure the README renders correctly and `npx awesome-lint` passes locally.
4. Open a pull request and fill in the template — including the eligibility evidence and affiliation sections.
5. Respond to review feedback promptly.

## What Not to Submit

- Links to the same resource you have already submitted.
- Blog posts, tweets, or videos that duplicate content already covered by a larger resource on the list.
- Content that is explicitly commercial with no free value tier.
- AI-generated entries without human review.
- Projects launched in the last 30 days (see [Deferrals](#deferrals)).

## Updating Your Pull Request

If your pull request needs changes, keep the same branch and push new commits. Do not close and reopen.

Thanks for helping make Awesome Chess useful to the chess community.
