# test-word Household

## 1. Goals and key dates

Goal: convert a seed Microsoft Word file into LaTeX, and build a PDF from that LaTeX.

Key dates: none set.

## 2. Style rules for all agents

Working language: English.

The owner has not set other style rules yet.

### Data rules

The owner has not yet described the seed Word file. Until they do:

- Ask the owner whether the file holds anything sensitive before committing it.
- PHI, personal data, payment details, secrets, and unpublished or embargoed material stay out of git.
- De-identified data only in agent sessions.

## 3. Ownership

| House | Folder | Also owns |
|---|---|---|
| Lead (Head House) | staff/lead/ | legacy/, latex/, CLAUDE.md, README.md, .gitignore |

## 4. Status by role

Lead: set up 2026-11-02. Waiting for the seed Word file.

## 5. Decision log

- 2026-11-02: Started as a one-house seed in one standalone repository.
- 2026-11-02: Repository is private, because it holds the household's working files. Read the full history before ever making it public.
- 2026-11-02: legacy/ is committed to git, so cloud chats can see the seed file.

## 6. Pointers

- Work list: TODO.md
- Products: PRODUCTS.md

## Tripwire

If this product is ever released, release a clean copy without `staff/`, or move `staff/` into its own private control repository first.
