# Minnesota: law history in git

The statute law of Minnesota as a git repository: one file per section, committed with the Office of the Revisor of Statutes as its publisher. It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law).

**What is in it now**

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `constitution/` | Constitution of the State of Minnesota (adopted 1857, generally revised 1974, as amended) | 1 | Oldest version available |
| `ch-609/` | Minnesota Statutes chapter 609, Criminal Code | 1 | Oldest version available |
| `ch-302a/` | Chapter 302A, Business Corporations | 1 | Oldest version available |
| `ch-507/` | Chapter 507, Conveyances of Real Property | 1 | Oldest version available |

That is all the law this repository holds today. Other chapters, session laws and the rules are not in it.

## Where the text comes from

The Revisor's chapter pages (`/statutes/cite/<chapter>/full`) and the Constitution page. Each section keeps its text and its History line (the session laws that made it). Repealed or renumbered sections keep the Revisor's one-line note as a Note line.

## Dates

The Revisor publishes yearly editions back to 1996 but states no in-force date for an edition. Each statute chapter is therefore one version dated by 29 October 2026, the day before it was retrieved (the 2026 edition; a commit cannot be dated later than the build), not the day the words took effect. The Constitution is dated 9 January 2025, the latest date in the Revisor's version list. Earlier editions and session-law commits (the History lines name them) are the next step.
