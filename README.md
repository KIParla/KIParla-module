# MODULE_NAME

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

MODULE_NAME is part of the larger [KIParla collection](https://www.kiparla.it).

MODULE_DESCRIPTION

## Repository organization

This repository contains:

* metadata for both speakers and conversations, in the [`metadata`](./metadata/) subfolder
* descriptions of the transcription conventions used ([Transcription conventions](./jefferson-notation.md))

For each conversation you will find:

* `.eaf` file in [`eaf/`](./eaf/) folder: time-aligned Jefferson-style transcriptions (open with [ELAN](https://archive.mpi.nl/tla/elan)).
* `.txt` file in [`linear-jefferson/`](./linear-jefferson/) folder: linearized Jefferson-style transcription.
* `.txt` file in [`linear-orthographic/`](./linear-orthographic/) folder: linearized transcription retaining only orthographic words.
* `.tsv` file in [`tsv/`](./tsv/) folder: verticalized version of the transcription, with Jefferson-style information decoupled from the text as features.

## Metadata

Each participant and each conversation are associated to a series of metadata, found in
[`metadata/participants.tsv`](metadata/participants.tsv) and [`metadata/conversations.tsv`](metadata/conversations.tsv).

## Data access

Due to GDPR restrictions, pseudo-anonymized audio files (MP3) are available under a restricted-access license. To request access, please contact the corpus coordinators through the KIParla website.

## How to cite

To cite this module please include:

> CITATION

```bibtex
@BIBTEX_ENTRY
```

-----

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
