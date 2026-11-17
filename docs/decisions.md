# Decision Log

Short records of technical decisions: what was decided, why, and what was left out.

---

## 001 - Keep generated data out of Git

- **Date:** 2026-11-17
- **Status:** Accepted
- **Context:** The pipeline generates raw and processed files in `data/`.
  These files can be recreated at any time by running the pipeline.
- **Decision:** Add `data/` to `.gitignore`. Only code and docs are versioned.
- **Alternatives considered:** Commit sample data files. Rejected because
  the repository would grow with every run.
- **Consequences:** Anyone cloning the repo must run the pipeline to get data.
  The README must explain how.

---

## 002 - (next decision)

- **Date:**
- **Status:** Proposed | Accepted | Superseded by 00X
- **Context:**
- **Decision:**
- **Alternatives considered:**
- **Consequences:**