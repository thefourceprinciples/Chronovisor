# Chronovisor Production Machine v1

The production layer converts completed UCMS investigations into reproducible documentary episodes.

## Pipeline

`SWEEP -> VERIFY -> SCRIPT -> ASSET LEDGER -> VOICE -> EDIT -> QA -> PUBLISH -> ARCHIVE`

The archive remains the source of truth. An episode is a build artifact, not the archive itself.

## Core rule

Historical visuals must be independently real and provenance-controlled. AI generation may be used only for explicitly synthetic explanatory graphics, never as fabricated historical evidence.

## Episode states

- `candidate` — promising research unit
- `verified` — publication-grade evidence pass complete
- `scripted` — narration and visual plan locked
- `assets` — visual provenance ledger complete
- `voiced` — narration recorded/generated with commercial-use rights confirmed
- `edited` — first assembly exported
- `qa` — factual, provenance, audio, caption and rights checks
- `published` — live on YouTube
- `superseded` — replaced by a corrected version

## Reproducibility

Every episode should have a manifest containing its research source, claim ledger, narration version, visual assets, music/voice licenses, edit version, and publication metadata. Corrections should create a new version rather than overwrite history.

## Visual provenance classes

- `P` — primary historical artifact/document
- `D` — documentary photograph
- `S` — scientific evidence/figure
- `M` — derived map
- `G` — explanatory graphic

No unlabeled synthetic historical reconstruction.
