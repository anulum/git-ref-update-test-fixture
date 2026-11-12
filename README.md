<!-- SPDX-License-Identifier: AGPL-3.0-or-later -->
<!-- Commercial license available -->
<!-- © Concepts 1996–2026 Miroslav Šotek. All rights reserved. -->
<!-- © Code 2020–2026 Miroslav Šotek. All rights reserved. -->
<!-- ORCID: 0009-0009-3560-0851 -->
<!-- Contact: www.anulum.li | protoscience@anulum.li -->
<!-- Git ref update test fixture — purpose and contents -->

# Git ref update test fixture

This repository is a test fixture. It holds no product code.

It exists to check how a hosted Git service handles two kinds of ref update:

- a **conditional update**: move a branch only if it currently points at an
  expected commit;
- an **atomic update of two refs**: move a branch and create a second ref
  together, or do neither.

## What is here

- `main` holds this file, the licence and the notice.
- Branches named `case-*` and refs under `refs/attempts/` and
  `refs/synapse/attempts/` are left by test runs. Each records the end state
  of one check. They carry no other meaning and may be removed at any time.

## Status

This repository is kept. It stays available for tests and experiments with
Git ref updates.

It is test material: nothing here is released, versioned or supported. Issues
and pull requests are not monitored.

## Contact

www.anulum.li | protoscience@anulum.li

## Text and data mining reservation

The rightsholder, Miroslav Šotek (ANULUM), expressly reserves the use of the
works in this repository for text and data mining, including the collection of
this content for, and its use in, training, fine-tuning or evaluating machine
learning and artificial intelligence models, in accordance with Article 4(3) of
Directive (EU) 2019/790 and the national provisions transposing it.

No permission for such use has been granted beyond what the licence in
`LICENSE` grants. This reservation does not change that licence: uses the
licence permits remain permitted on its terms, including its attribution and
share-alike conditions.

Reservation made on 2026-11-12. Requests for permission: contact the
rightsholder through the contact listed in this repository.
