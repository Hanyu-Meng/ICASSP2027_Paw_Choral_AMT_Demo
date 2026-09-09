# PawCT project page

Public project page for **“Toward Part-Aware Choral Transcription with
Singing Voice Assignment.”**

**Live demo:**
[https://hanyu-meng.github.io/ICASSP2027_Paw_Choral_AMT_Demo/](https://hanyu-meng.github.io/ICASSP2027_Paw_Choral_AMT_Demo/)

PawCT transcribes one mixed choral recording into note-level soprano, alto,
tenor, and bass parts. This dependency-free academic project page presents the
method, manuscript-reported results, and the paper's qualitative comparison.

## Scientific status

The displayed metrics are manuscript-reported values, not results regenerated
from this demo repository. Read [the reproducibility audit](REPRODUCIBILITY.md)
before citing them. The accompanying implementation repository is currently
access-controlled while its experiment provenance is being frozen.

## Contents

- `index.html` and `styles.css`: the static project page;
- `assets/`: an author-generated piano-roll comparison and rights manifest;
- `CODE_WALKTHROUGH.md`: English method and code walkthrough;
- `CODE_WALKTHROUGH.zh-CN.md`: concise Chinese walkthrough;
- `REPRODUCIBILITY.md` and `PROVENANCE.md`: release caveats and source audit.

No YouChorale audio, source MIDI, annotations, model checkpoints, or
probability files are distributed here.

## Local preview

```bash
python -m http.server 8000
```

Then open <http://localhost:8000>. Local serving is only for development; the
GitHub Pages link above is the intended public entry point.

## Maintainer

[Hanyu Meng](https://github.com/Hanyu-Meng), Multimodal Music Research Lab.

## License

Site source is released under Apache License 2.0. The included visualization
is copyright 2026 Hanyu Meng, all rights reserved, and is not covered by the
source license. The license also does not grant rights to datasets, recordings,
annotations, checkpoints, or other generated media; see
`assets/manifest.json` for details.
