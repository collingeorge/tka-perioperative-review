# 2026.10-rc2 - educational review candidate

> **Educational work by a pre-medical student — not medical advice.** Not a clinical protocol, prescription, or patient handout, and not for patient care. See [DISCLAIMER](DISCLAIMER.md).

Revised 27 October 2026 after the rc1 PRs were merged.

This pass corrects newly identified source and software defects and deliberately narrows unsupported clinical/methodological content. Earlier versions remain recoverable in Git history. See PUBLICATION_REVIEW.md for the precise scope and limitations, PROVENANCE.md for author statements, and RELEASE_MANIFEST.json for current-file hashes.

The candidate is not a clinical protocol, validated controller, systematic/scoping review certification, or legal opinion. No repository visibility change is included.

## Applied example set — 28 October 2026
Added 6 topic-specific male/female case pairs, a local copy of the shared anesthesia-options set, two levels of source mapping and an explicit verification standard. The profiles are entirely synthetic; the source checks are scoped and do not certify clinical validity. Existing clinical/manuscript text and PDF exports are preserved.


## 29 October 2026 — Portfolio presentation and reading path

Added a concise reader’s guide, explicit AI-assistance/authorship scope and review-status notes. Linked the portfolio home and corrected navigation wording. This presentation pass preserves substantive manuscripts, casebooks, code and existing exports. Repository visibility is unchanged.

## November 2026 — accuracy and governance review

5 November 2026. Precision fixes from an independent source re-check (no Critical or Major findings):

- Main map and modality note: Johnson et al. 2016 is described as pooling randomized and prospective comparative studies; ICAROS 2019 additionally included retrospective/database observational studies. The ICAROS knee-arthroplasty neuraxial preference is now stated as a weak recommendation on low-level evidence (hip: strong).
- Adjunct note: PROSPECT 2022 does not recommend ketamine after TKA (conflicting procedure-specific evidence). The 2022 add-on trial is now cited by author, title and journal (Muñoz-Leyva et al., Anesthesiology 2022;137:459-470). The withdrawn PMID 23364596 is described only as not corresponding to a TKA lidocaine trial.
- Regional note and main map: the Cochrane adductor canal review (Schnabel 2019) is noted to cover adult knee surgery (18 TKA, 7 arthroscopic trials).
- Applied cases and EXAMPLE_SOURCE_AUDIT.json: TK-02 now cites Hussain et al. 2021 (iPACK) instead of the LAST checklist; the Beloeil (POFA) scope now states it was a major non-cardiac surgery trial, not TKA, replacing text copied from another repository; duplicate DOI links removed; the Smart NOA walkthrough reference is now an explicit link to the separate repository.
- Main map: title and README now say "selected-source narrative evidence map" (legacy "Scoping-Review" filenames kept for link continuity); reference list rewritten as full citations with printed DOIs/PMIDs; inline cross-document links rendered as plain filenames so the PDF export does not show raw Markdown; "Foo et al.." typo removed. The PDF export is stale until rebuilt.
