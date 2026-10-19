# Titi Game Media · MS TRANG TRIEU EDUCATION

Shared static media for the Titi learning games. The original classroom recordings and generated full-resolution PNGs retain their original bytes. No runtime AI or paid media API is required.

- `assets/dictation-audio/`: FF1–2 Lesson 6 and Discover 1–4 Listening, 102 recordings.
- `assets/hunt-worlds/`: 20 scene plates, 32 transparent Unit object atlases and phoneme audio.
- `assets/hunt-audio/`: native English Titi instructions and praise.
- `manifest.json`: deployed asset URLs, byte sizes and SHA-256 digests.
- `art-sources.json`: all image prompts and atlas cell specifications; **Built-in image generation**.

The Phonics sound models are credited to [University of Hamburg · English Explorations](https://englishexplorations.check.uni-hamburg.de/basic-concepts-of-english-phonetics-and-pronunciation/); see `assets/hunt-worlds/phonemes/sources.json`. Runtime clips contain only the first isolated sound, ending before the example words. Extraction retains the original sample rate and pitch in lossless PCM WAV files. The /ks/ cluster combines the isolated /k/ and /s/ after boundary silence removal. Titi's spoken instructions use native en-US-AnaNeural audio.

[Open Titi Games](https://mstrangtrieueducation-droid.github.io/titi-games/)
