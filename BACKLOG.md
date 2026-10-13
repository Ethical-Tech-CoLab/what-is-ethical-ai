# Backlog

Known gaps, in the order they would mislead a reader.

---

## Credibility review — 2026-07-27

A hostile-but-fair peer-review sweep of the report copy (canonical in
[REPORT.md](REPORT.md), mirrored on the site in
`website/src/content/publications/what-is-ethical-ai.ts`). Fix in both places.

### 1. The Bletchley Declaration count contradicts itself — FIXED 2026-07-27

Fixed in both `REPORT.md` and the site copy: §12 now reads "twenty six other
states." Original write-up below.

Verified 2026-10-12: the fix was in `REPORT.md` and the CoLab site copy, but
the committed Pages build (`docs/index.html`) had not been regenerated and
still said "twenty five." Rebuilt and committed. The designed PDF in
`docs/pdf/` still carries the old wording (see item 4).


§09 says the declaration was "signed by twenty eight countries and the European
Union," but §12 describes the same acknowledgment as "the United States, China,
the European Union, and twenty five other states" (i.e. 27 + EU). The correct
figure is 28 states + EU, so §12 is the wrong one. Fix: change §12's "twenty
five other states" to "twenty six."

### 2. Misattribution: "Bietti named ethics washing" — FIXED 2026-07-27

Fixed in both `REPORT.md` and the site copy: now reads "analyzed ethics
washing." Original write-up below.

Verified 2026-10-12: same story as item 1. `docs/index.html` still said
"named ethics washing" until the rebuild on this date. The designed PDF still
says "Bietti named the political economy of the moment, ethics washing" (see
item 4).


§09 says "Elettra Bietti named ethics washing," but her cited FAccT 2020 paper
("From Ethics Washing to Ethics Bashing") is known for coining *ethics bashing*;
"ethics washing" is generally credited to others (e.g. Wagner). Fix: reword to
"analyzed ethics washing," or credit her with "ethics bashing."

### 3. (Done 2026-07-27, confirm keep) Hero stat band replaced

The "4,000 years of ethics" and Gender Shades "34.7% / 0.8%" hero stats were
removed as not insight-bearing and replaced with the Signpost "15% could not be
rated safe" and ILO "$236B" figures, both drawn from the paper's own body.
Revert if the editor prefers the original four.

### 4. The designed PDF still carries both errors — OPEN

`docs/pdf/What-Is-Ethical-AI-ETC-Report.pdf` was exported before the two fixes
above. Its text still reads "twenty five other states" (§12) and "Elettra
Bietti named the political economy of the moment, ethics washing" (§09). The
PDF is a designed export, not generated from `REPORT.md`, so it has to be
re-exported by hand from the design source and dropped back into `docs/pdf/`
under the same filename. The Pages site and the CoLab site both link to it.

### 5. Quality pass — 2026-10-12

Checked: README's three external links and the PDF URL all return 200;
the "ten resources" list in §09 has ten items; the sixteen numbered sections
match the Contents list; no em dashes in `REPORT.md`; repo description and
topics are set. The References section carries no URLs or DOIs, so the
citations were not link-checked, only read for internal consistency. Nothing
else open.
