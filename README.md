# ai-agency-guard

One file: `MANIFEST.sha256` — SHA-256 hashes of the AI Agency's protected security files
(agent definitions, hooks, security scripts, settings). Names and hashes only. Nothing sensitive.

**Who writes it:** a human, in the GitHub web editor, logged in with 2FA.
**Who reads it:** the agency, on every session start, every sync, and every Monday sweep.
A local file that does not match this list is drift, and the agency refuses to sync.

To approve a change: run `verify_protected.ps1 -Print` locally, paste the output here, commit.
