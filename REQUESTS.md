# Request Log — Sehgal Autoriders / Maruti Suzuki Division

Every request gets a **two-word label** so you can tell at a glance what a
request number is about, instead of only seeing "Request No. 0095".

## Labelling rule

- Exactly **two words**, Title Case.
- Name the **thing being changed**, not the action.
  Good: `OCR Cascade`, `Android Launch`, `KM Allowance`.
  Bad: `Fixed Bug`, `Some Changes`, `Update App`.
- The label never changes once assigned — the request number and label stay
  paired for good.

## Log

| Request | Label | What it was | Date | Commit |
|---|---|---|---|---|
| — | `Division Setup` | Maruti Suzuki Division: driver km allowance + gate-out register (demo) | 13-Aug | `02fcdc8` |
| — | `OCR Cascade` | Gate-out OCR fallback chain: Gemini → Cloud Vision → on-device scanner → manual; no-JC exits shown in red | 13-Aug | `c44afb7` |
| 0095 | `Android Launch` | Marketing the app and publishing it to the Android store | 16-Aug | — |

Request numbers for the 13-Aug entries are unknown — those commits predate this
log, and the request number is not recorded anywhere in the repository. Fill
them in if you still have them in the router history.

Requests 0001–0094 are not listed: none of them changed this repository, so
there is nothing here to reconstruct them from.
