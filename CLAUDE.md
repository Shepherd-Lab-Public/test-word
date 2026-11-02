# test-word Agent Instructions

This project turns a seed Microsoft Word file into LaTeX and then a PDF. The
GitHub repository Shepherd-Lab-Public/test-word (branch main) is the single
source of truth.

One house for now: the Lead, in staff/lead/. Facts, goals, ownership, and
decisions are in staff/lead/HOUSEHOLD.md.

## Start of every session
1. App chat: attach and clone Shepherd-Lab-Public/test-word. VS Code: git pull.
2. Read staff/lead/HOUSEHOLD.md and staff/lead/STATE.md.
3. Report in three lines.

## Checkpoint
1. Append the session to staff/lead/log/YYYY-MM-DD.md.
2. Update staff/lead/TODO.md and staff/lead/PRODUCTS.md.
3. Rewrite staff/lead/STATE.md.
4. Log decisions in staff/lead/HOUSEHOLD.md.
5. Commit, then git pull --rebase, then git push.

## Rules
- Keep the original files in legacy/ unchanged. Work happens in latex/.
- Never force-push or rewrite history on main.
- Only the owner opens a house. Never start another house, or a second copy of
  yourself, as a subagent or background session. Helpers that load no role file
  and write nothing are fine.
- Never send email or contact anyone. Draft it; the owner sends.
- No PHI, personal data, payment details, or secrets in git. Keep them where
  HOUSEHOLD.md's data rules say, and leave a pointer.
- De-identified data only in agent sessions, unless HOUSEHOLD.md's data rules
  say otherwise.
- Logs and notes summarize; never quote an email or copy an address.
- If something sensitive reaches git or an agent session, stop and tell the
  owner.
- Write working files and talk with the owner in English. Save files as UTF-8.
