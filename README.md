# As-of Drug Labels: US corpus

US prescription drug labels as DailyMed (U.S. National Library of Medicine) showed them, as a git history: one commit per published label version, one folder `<inn>/<setid>/` per DailyMed setid with `label.json` and one Markdown file per LOINC section, one sentence per line. Commit dates are DailyMed's Published-Date, never FDA approval dates; the trailers `Source-Id`, `Source-Version`, `Published-Date`, `Source-URL` and `Source-SHA256` name each commit's source file and `Text-Fidelity` its conversion rule.

Wording is intended to be unchanged; automated conversion from SPL XML can introduce errors (tables, superscripts, column order, dropped lines). The source file pinned by URL and SHA-256 in each commit is authoritative; where this copy differs from the official DailyMed document, the official text prevails.

Courtesy of the U.S. National Library of Medicine (DailyMed); NLM does not endorse this project. Particula Tech does not license the label text and claims no copyright in it; copyright stays with its authors and holders. US label text is not public domain, CC0 or openly licensed.

Scope, record window, limits and the tools that build this repository are at https://github.com/Particula-Tech/asof-drug-labels; this repository carries no counts or dates of its own.

See `NOTICE.md` for licence terms, the rights-holder and corrections contact, trade marks and the warranty disclaimer. Not medical advice.
