# Notice of adaptation (CC BY-SA 4.0, section 3(a)(1)(B))

This is **Adapted Material**: a modified version of `ai-memory-vault` by Jared Rhodenizer (upstream: https://github.com/jaredrhod/ai-memory-vault), prepared by **Executive Stack** and dated **2026-09-22**.

- Based on upstream commit: `659bba9c8b351c937dd393b3042801d1ff1b502c` (upstream author `jaredrhod`, dated 2026-08-30).
- Executive Stack release: `es-2026.09.22-r1` (the name in `ES_RELEASE`), on branch `es-release`.
- Attribution: the original work is by Jared Rhodenizer (@jaredrhod), https://github.com/jaredrhod/ai-memory-vault, licensed under Creative Commons Attribution-ShareAlike 4.0 International (https://creativecommons.org/licenses/by-sa/4.0/). The `LICENSE` file is unchanged.
- ShareAlike: this adapted version is licensed under the same CC BY-SA 4.0 license. Note the reach: the `CLAUDE.md` and `VAULT-INDEX.md` that the wizard writes onto a client machine are derived from `templates/CLAUDE.md` and `templates/VAULT-INDEX.md` and are themselves Adapted Material under CC BY-SA 4.0.
- Each modified file carries a "Modified by Executive Stack, 2026-09-22" HTML comment at the top (after the YAML frontmatter where there is one).

## Why

Executive Stack ships this build script to its clients from a reviewed, pinned mirror. The changes below pin the third-party tools the script installs, make every install and update pointer land on the reviewed release tag, remove unreviewed repositories from the onboarding, replace the shipped default identity with a professional one suited to a business install, remove the health question, and replace the author's community and marketing material with the Executive Stack support pointer (author attribution and license credit are kept).

## Files changed, and why

| File | Change |
|---|---|
| `README.md` | Describes the Executive Stack default identity instead of the author's agent; the clone sentence points at the mirror at the release tag; the walkthrough playlist and the author's site links removed; update wording describes the pinned-tag update; the hands piece removed; YouTube, Discord and Ko-fi replaced with the Executive Stack support pointer; the license section keeps the author's copyright and adds the adaptation notice. |
| `ai-memory-vault.md` | Byline carries upstream and mirror; Obsidian install pinned to 1.13.7 on every lane (winget `--version`, the macOS DMG by direct release URL with its SHA-256 `05daa54f5e1a4458f75da29f8faaa17e8e37ae16998432537f674c626db99bce`, Linux AppImage hashes) instead of "latest"; `npx -y @modelcontextprotocol/server-filesystem` pinned to `@2026.8.31`; the identity doors (question 0) offer the Executive Stack default persona (warm, professional, no profanity, name chosen with the client) as door A, a tuned variant as door B, and build-your-own as door C; the Health question (7) removed and the Health section dropped from the VAULT-INDEX template and its Living Profile list; the embedded `CLAUDE.md` Identity section rewritten to the professional default; update wording describes the pinned-tag update; the closing section drops barehands, points the one-piece install and the fullstack-agent one-liners at the mirror at the tag (hash-checked Windows zip), replaces Discord and YouTube with the support pointer, and removes the marketing-files offer (`ai-marketing-skills`). |
| `templates/CLAUDE.md` | The Identity section replaced with the Executive Stack default persona (name and first-name markers to fill in; warm professional register; no profanity); the explanatory notes updated to match. Everything below the Identity section is unchanged and stays word-for-word identical to the embedded copy in `ai-memory-vault.md`. |
| `templates/VAULT-INDEX.md` | The Health section removed and "Health" dropped from the Living Profile update list, matching the embedded copy in `ai-memory-vault.md`. |
| `ES_RELEASE` | New: the release tag name this checkout belongs to. |
| `NOTICE-EXECUTIVE-STACK.md` | New: this notice. |

Files not listed (`templates/DAILY-NOTE.md`, `templates/MEMORY.md`, `TROUBLESHOOTING.md`, `LICENSE`, `.gitignore`) are byte-for-byte identical to the upstream commit.
