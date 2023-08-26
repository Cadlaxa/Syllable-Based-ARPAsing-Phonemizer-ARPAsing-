# Syllavle-Based ARPAsing Phonemizer
Custom English Arpabet Phonemizer based on Syllable-Based API Phonemizer
 
This Phonemizer was optimizer for `Arpasing 0.1.0` and `Arpasing 0.2.0` **banks the original list Kanru Hua** made for [Openutau](https://www.openutau.com/).

#### 📍 if there's any issue on the Phonemizer, you can contact me through my [Twitter](https://twitter.com/cadlaxa). Let me know if there's a problem tehee.
 - - - -
### Table of contents
- **[How to download and install the custom Phonemizer](https://github.com/Cadlaxa/Syllable-Based-ARPAsing-Phonemizer/blob/main/README.md#how-to-download-and-install-the-custom-phonemizer)**
- **[Mechanics of the Phonemizer](https://github.com/Cadlaxa/Syllable-Based-ARPAsing-Phonemizer/blob/main/README.md#mechanics-of-the-phonemizer)**
    - **[How syllables work](https://github.com/Cadlaxa/Syllable-Based-ARPAsing-Phonemizer/blob/main/README.md#how-syllables-work)**
    - **[Vowel and Consonant Fallbacks](https://github.com/Cadlaxa/Syllable-Based-ARPAsing-Phonemizer/blob/main/README.md#vowel-and-consonant-fallbacks)**
    - **[Phonemizer Demo](https://github.com/Cadlaxa/Syllable-Based-ARPAsing-Phonemizer/blob/main/README.md#phonemizer-demo)**
 - - - -
## How to download and install the custom Phonemizer

- To download and install the Phonemizer, click on Tags then download the zip file. When downloaded, move ArpaPlusPhonemizer.dll into the path\to\OpenUtau\Plugins folder or just simply drag the dll file and drop onto the OpenUtau program.
 - - - -
 ## Mechanics of the Phonemizer

### How syllables work
**Syllables are built like:**

- Starting C: `[- c]`
- Starting V: `[- v]`
- VV: `(with V and CV fallbacks if there's so VV available on the bank)`
- Connecting CV: `[c v]`
- Connecting VC: `[v c]`
- Connecting CC: `[c c]` (with consonant fallbacks)
- Ending C: `[c -]`
- Ending V: `[v -]`

  **Phoneme length are specified directly to the phonemizer:**
- Default transition in ms: '0.50'
- Vowels: 'default'
- Consonants: '1.3'
- Affricates: '1.5'
- Long Consonants: '2.3'
- Semi-long Consonants: '1.3'
- Tap Consonant: '0.5'
 - - - -
### Vowel and Consonant Fallbacks
**This custom Phonemizer supports vowel and consonant fallbacks:**
- CV Fallback: `[c v]`
- VV Fallback: `(with V and CV fallbacks if there's so VV available on the bank)`
- Connecting VC Fallback: `[v c]`
### Phonemizer Demo
- **English**
  - Vocal: KYE by @Winter_drivE
  - `EN ARPA`
  - `EN ARPA+`
- **Chinese (with dictionary)**
  - Vocal: LIEE ENGLISH by @utauraptor
  - `EN ARPA`
  - `EN ARPA+`
- **Japanese (with dictionary)**
  - Vocal: Ryujin Soru by @Sora/Rippa
  - `EN ARPA`
  - `EN ARPA+`
