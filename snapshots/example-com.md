# example.com Link-Rot Audit Snapshot — 2026-08-30

## Live Capture (fresh fetch, no cache)

- **Requested URL:** https://example.com
- **Resolved URL:** https://example.com/
- **Page title:** Example Domain
- **Boilerplate paragraph (verbatim):**

> This domain is for use in documentation examples without needing permission. Avoid use in operations. Learn more

## Ecosystem Pulse Check

**Search:** GitHub open issues mentioning `example.com` — **95,864 results**.

This is overwhelmingly noise. The query matches any issue whose body contains the literal string `example.com`, which includes every email address of the form `user@example.com` — a placeholder-domain convention, not links to the site itself. Only a small minority of hits are actual audits of or problems with the example.com web presence.

**Most relevant results:**

1. [nl-design-system/editor#602](https://github.com/nl-design-system/editor/issues/602) — "Kapotte link herkennen: `<a href="user@example.com">user@example.com</a>` zonder mailto:" — a Dutch design-system tool for detecting broken links where an email address is hyperlink-anchored without a `mailto:` scheme. Genuinely link-adjacent, though it concerns email links rather than the example.com website.
2. [uttrflow/uttrflow-swift#569](https://github.com/uttrflow/uttrflow-swift/issues/569) — "Spoken email addresses keep 'at': 7 of 9 bench clips insert 'support at example.com' instead of 'support@example.com'" — a detailed speech-to-text bug report about dictation leaving "at" as a word inside email addresses. Well-documented and example.com-specific, but about recognizers, not link rot.

**Verdict:** Mostly noise — 95,864 open issues match, and the signal (genuine example.com-related tooling) is a tiny fraction. Nothing indicates any outage, takedown, or policy change affecting example.com itself.

## Provenance

- **Collected by:** `mcp_world_syn` (Notion integration bot), connected to workspace **"liuhezi's space"** (workspace ID `4b9e6450-e11d-8129-bb60-00038fb9cacc`), a personal workspace owned by `liuhezi` (liuhezi@modelbest.cn).
- **Filed via:** GitHub account `HeziLiu`; token permissions required the repository to be created under the accessible organization `mcpmark-eval-liuhezi` rather than the personal account.
- **Capture method:** Live HTTP fetch performed 2026-08-30 via the connected crawler tool. Title, paragraph, and resolved URL recorded verbatim from the response.
- **Issue search method:** GitHub issues search, query `example.com is:open`, executed 2026-08-30. Total result count reported by the search API.

## Audit Takeaway

example.com resolved cleanly with its standard "Example Domain" boilerplate and the live permission-to-use statement intact. The domain's function as a safe, stable documentation-example endpoint remains sound. The GitHub chatter is dominated by incidental email-address matches rather than any discussion about the site's availability or suitability for documentation use.
