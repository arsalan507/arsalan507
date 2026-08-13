# Arsalan Ahmed

**Founder, [KineticXHub](https://kineticxhub.com)** · **Co-founder, [Black Arrow Technologies](https://blackarrowtechnologies.com)** — I build AI automation and digital-marketing infrastructure for businesses, then run agencies on it.

📍 Bengaluru, India &nbsp;·&nbsp; [LinkedIn](https://linkedin.com/in/arsalan507) &nbsp;·&nbsp; [Email](mailto:arsalanahmed507@gmail.com) &nbsp;·&nbsp; [WhatsApp](https://wa.me/919916516507)

---

## What I run

| | Business | What | |
|---|---|---|---|
| 🟠 | **KineticXHub** | AI automation + digital marketing for Bengaluru businesses | [kineticxhub.com](https://kineticxhub.com) |
| ⚫ | **Black Arrow Technologies** | Website design + digital services, co-founded | [blackarrowtechnologies.com](https://blackarrowtechnologies.com) |

## What I'm building

**[Nirman](https://github.com/arsalan507/nirman)** — voice-powered construction-expense tracker. Speak in Hindi, Kannada, or English and it auto-fills amount, category, and vendor. Open source, live.

**KXH AI Marketing Engine** — an autonomous content pipeline: Claude drafts, self-reviews against a quality gate, and publishes daily to LinkedIn and Reddit with no human in the loop.

**[second-brain](https://github.com/arsalan507/second-brain)** — a personal AI OS with persistent memory, a consistent personality, and a voice interface.

**[AZALEA](https://github.com/arsalan507/azalea-template)** — an original-code recreation of a luxury real-estate site's full motion system: curtain page transitions, character-stagger reveals, digit-roll counters. Zero dependencies, no build step.

## Open source

Bug fixes in other people's codebases, each backed by a regression test verified to fail before the fix and pass after.

**[bitrix24/b24ui](https://github.com/bitrix24/b24ui)** — search results were truncated one UTF-16 code unit at a time, so a boundary landing between an emoji's surrogates split it in half and rendered `�`. Fixed by iterating code points and measuring the caller's budget in the same units — [merged into `main`](https://github.com/bitrix24/b24ui/commit/01252a62), closing [#339](https://github.com/bitrix24/b24ui/issues/339), with authorship preserved by the maintainer. Follow-up [#379](https://github.com/bitrix24/b24ui/pull/379) fixes the same class of bug where the `<mark>` tag is *inserted* rather than where the string is cut.

**[nuxt/ui](https://github.com/nuxt/ui)** — [#6830](https://github.com/nuxt/ui/pull/6830) merged: the alternating-timeline recipe positioned items with physical `translate-x` and `text-right` utilities, which don't mirror under `dir="rtl"`. [#6817](https://github.com/nuxt/ui/pull/6817) open: the upstream twin of the b24ui truncation fix, so the two projects stay in sync.

**[bitrix24/b24rabbitmq](https://github.com/bitrix24/b24rabbitmq)** — three fixes open: [#54](https://github.com/bitrix24/b24rabbitmq/pull/54) a config-merge bug silently dropping a default value, [#55](https://github.com/bitrix24/b24rabbitmq/pull/55) a reconnect loop that re-armed itself after a graceful shutdown, [#56](https://github.com/bitrix24/b24rabbitmq/pull/56) missing error listeners that could crash the host process on a broker bounce.

## Stack

`Next.js` `React` `TypeScript` `Tailwind` &nbsp;—&nbsp; `Node.js` `Python` `Playwright` &nbsp;—&nbsp; `Supabase` `PostgreSQL` &nbsp;—&nbsp; `Claude` `OpenAI` &nbsp;—&nbsp; `Docker` `Coolify`

---

📫 Reach out on [WhatsApp](https://wa.me/919916516507) or [LinkedIn](https://linkedin.com/in/arsalan507) — always open to talking automation, AI infra, or a new build.
