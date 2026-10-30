# How this repository was made (United States (Minnesota))

This file is written by the build on 2026-10-30, the day the source data was retrieved.

## Sources

| Source | Address | Retrieved | Licence |
| --- | --- | --- | --- |
| Minnesota Revisor of Statutes: Minnesota Statutes (current edition) | <https://www.revisor.mn.gov/statutes/> | 2026-10-30 | No reuse terms are stated on the statute pages. Statutory text is not copyrightable (Georgia v. Public.Resource.Org, 2020); the Revisor claims copyright only in the arrangement and editorial apparatus of its compilations, which are not taken. |
| Minnesota Revisor of Statutes: Constitution of the State of Minnesota | <https://www.revisor.mn.gov/constitution/> | 2026-10-30 | Official text published under Minnesota Statutes chapter 3E; no reuse terms stated. |

Every word of law in this repository comes from these sources. Lexifina reads them and records each act's dated versions, and the laws that made each change, in one corpus file. This repository is built from that file.

## What is in it

| Act | Title | Versions | Span |
| --- | --- | ---: | --- |
| `constitution` | Constitution of the State of Minnesota | 1 | 2025-01-09 to 2025-01-09 |
| `ch-609` | Minnesota Statutes chapter 609 (Criminal Code) | 1 | 2026-10-29 to 2026-10-29 |
| `ch-302a` | Minnesota Statutes chapter 302A (Business Corporations) | 1 | 2026-10-29 to 2026-10-29 |
| `ch-507` | Minnesota Statutes chapter 507 (Conveyances of Real Property) | 1 | 2026-10-29 to 2026-10-29 |

The build made 4 commits:

| Commits | Kind |
| ---: | --- |
| 4 | first version of an act |
| 0 | one law on its in-force day |
| 0 | changes no amendment note explains, credited to the publisher |

Other counts:
- 0 commits on the branch `future`: laws not yet in force on 2026-10-30.
- 0 commits dated 1 January 1970: in force before 1970, with the real day in their `In-force` trailer.
- 0 laws in the record.
- 4 tags.

## Dates

Each commit is dated at noon (America/Chicago) on the day the change took effect. The other dates, enacted and published, are trailers.

When a law gives no date of its own, the default rule applies: Oldest version available: the current Minnesota Statutes (2026 edition) as served by the Revisor on the retrieval date; the Constitution is dated by the Revisor electronic publication date. https://www.revisor.mn.gov/statutes/

## How the history is built

`tools/build.py` turns the corpus into this history in one pass: one commit per law, on the day it took effect. The same corpus always gives the same commit hashes. `tools/check_repo.py` reads every version back from git and compares it with the corpus. `tools/on.py` shows the law as it stood on any date. The corpus format is described in `tools/SCHEMA.md`.

- Corpus: sha256 `7c2039fae0e624608668b059d26b8f24d4655b8472cac6188debb84199e7a320` (1727051 bytes).
- Builder blob hashes (`git hash-object`): `build.py` `a4faa25af85facb64b956b372f6b528aafdd7ec1`, `check.py` `3e59cb6f05eccb94a9ec14431a7f6781221e83ef`, `on.py` `644a6c0857fbcc72562032b58d57aa113fee0641`.
- Python 3.12.10; git version 2.46.0.windows.1.

## Checks

Not yet run for this build.

No second build of this corpus has been compared yet.

## Decisions made by hand

- The Revisor publishes yearly editions but states no in-force date for them, so each Statutes chapter is one oldest-version-available version dated 2026-10-29, the day before retrieval (2026-10-30), because commits are stamped at noon UTC and cannot be future-dated on the retrieval day. Earlier editions (2017 on) were not taken.
- The Constitution version is dated 2025-01-09, the latest date in the Revisor version list.
- Chapters taken: 609 (Criminal Code), 302A (Business Corporations), 507 (Conveyances of Real Property). Headings are kept in the Revisor capitals.
- Editorial see-notes and the Revisor tables are left out; repealed and renumbered sections keep their one-line note.

## What AI did and did not do

The scripts that read the sources and build this repository were written by Claude Code running Claude Opus 5.5 (`claude-opus-5-5`) under Lexifina's direction.

No model wrote, translated or corrected legal text. No model runs at build time. Every word of law in this repository comes from the official sources above.

The commit messages are written by `build.py` from the source data.

Model use at data-build time:
- none
