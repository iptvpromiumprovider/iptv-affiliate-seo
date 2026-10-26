# iptv-affiliate-seo

A Claude skill for writing IPTV affiliate content that ranks on Google and gets cited by AI answer engines — without tripping Google's 2024 Site Reputation Abuse policy or getting banned from Reddit, Medium, or Quora.

## Why this exists

Most "IPTV SEO" advice is a decade out of date. It assumes you can keyword-stuff a blog post and point 50 backlinks at it. That stopped working in 2024. Google now actively filters thin affiliate IPTV content, and every major platform has spam heuristics tuned specifically to this vertical.

The posts that still rank share four traits: a named testing method, a real limitation on the recommended service, a comparison structure, and a specific device + region frame. This skill encodes those four traits into every output.

## What it covers

- Platform ranking for IPTV (Reddit > Medium > Quora > YouTube > GitHub > forums)
- Keyword clusters mapped to buyer intent, not search volume
- E-E-A-T shapes that survive 2025–2026 Google updates
- GEO structure so ChatGPT / Perplexity / Google AIO quote the post
- Link placement rules per platform (where the affiliate link goes, where it doesn't)
- The specific patterns that get posts removed or accounts banned

## What it doesn't cover

- Piracy tooling, credential sharing, DRM circumvention
- General SEO for non-IPTV verticals — see `parasite-seo`
- Paid ads

## Install

Drop `SKILL.md` into your Claude skills directory (`~/.claude/skills/iptv-affiliate-seo/` on Unix, `%USERPROFILE%\.claude\skills\iptv-affiliate-seo\` on Windows).

Or install from skillsdirectory: `<link once published>`

## Usage

Once installed, invoke by asking Claude to write or optimize IPTV content:

> "Write a Reddit post comparing three IPTV providers for UK Firestick users in 2026"

> "This Medium article about IPTV isn't ranking — what's wrong with it?"

> "Structure an IPTV Quora answer for the query 'best iptv for premier league uk'"

The skill reads the platform, the intent, and the offer, then returns a post shaped to rank without getting flagged.

## License

MIT
