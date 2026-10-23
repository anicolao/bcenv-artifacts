# Public Battlecode engineering evidence archive

Destination: https://github.com/anicolao/bcenv-artifacts (repository ID1431035719, owner `anicolao`, public). Everything committed here is publicly readable. The user authorized this public destination on2026-10-23; publication follows an explicit file allowlist and independent review.

## Initial checkpoint

`checkpoints/public-ci-001` contains one existing public CI artifact, its complete61-member SHA256 inventory, an existing public engineering policy document, provenance, and a current retrieval report. The ZIP is the original269104-byte public artifact, not a newly run experiment. No missing trial data was reconstructed. The containing workflow head and embedded runtime revision are distinct and recorded without relabeling either.

This repository contains no held-out opponent corpus, private evaluator plans or raw benchmark outcomes, private aggregate results, credentials, signed download URLs, or private infrastructure payload. Public CI fixture logs/replays and instrumenter test fixtures are explicitly included; these are not autonomous candidate or held-out evaluation runs. No candidate work is in this initial checkpoint.

## Retention and publication contract

- Ordinary Git only; no Git LFS or Actions workflows in this repository.
- Every blob must be <=49MiB. Cumulative unique archived payload and manifest bytes across all history must remain <=512MiB; also monitor actual repository storage and stop before512MiB where observable. No silent omission, history rewrite, or splitting repositories to evade the cap. These are policy ceilings, not a measured future trial footprint or a provider retention guarantee.
- Exact remote commit retrieval into a new empty directory must verify every allowlisted file SHA256/size, archive SHA256, ZIP CRC and all61 member SHA256/sizes. Record the retrieved commit and verification result separately after publication; a push response alone is not readback proof.
- Future candidate/public-development checkpoints require a separate explicit public file allowlist and secret/private-material guard. Never copy a whole workspace or attach this archive repository to a candidate. Candidate-visible input rebinding remains separately reviewed.
- Held-out material and previously restricted private results remain excluded despite this public-repository authorization.
- Retention failures fence new admissions, preserving accepted work, charges, original deadlines and uncertainty. They do not imply retries, refunds, cancellation, helper death, or successful physical cleanup.
- No new trial or experimental continuation is authorized by this initialization. GitHub availability/deletion/account changes can still affect retention; successful readback proves current retrievability, not perpetual storage.

`MANIFEST.json` inventories all payload files except itself. `SHA256SUMS` binds those files and the manifest. No mutable remote URLs are used as content identities.
