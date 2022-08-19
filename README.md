# Multilingual NNSVS HED
HED and supporting files for the NNSVS tri-language system.
Based on X-SAMPA, this system includes the symbols for American English, South American Spanish, and Japanese.
None of the dictionaries are word based, only input allowed is phonetic.


## Others:
| Phoneme | X-SAMPA | Description               |
| ------- | ------- | ------------------------- |
| pau     |         | Silence                   |
| cl      | :       | Closure (Held Consonants) |
| gs      | ?       | Glottal Stop              |
| exh     |         | Exhale                    |
| vf      |         | Vocal Fry                 |
| trash   |         | Trash                     |

## Vowels:
| Language | Phoneme | X-SAMPA | Description                              |
| -------  | ------- | ------- | ---------------------------------------- |
| ES JP    | a       | a       | Central open unrounded vowel             |
| EN       | A       | A       | Open back unrounded vowel                |
| EN       | aI      | aI      | Add Later                                |
| EN       | aU      | aU      | Add Later                                |
| EN       | ax      | @       | Schwa                                    |
| EN       | V       | V       | Open-mid back unrounded vowel            |
| EN       | {       | {       | Near-open front unrounded vowel          |
| ES JP    | e       | e       | Close-mid front unrounded vowel          |
| EN       | E       | E       | Open-mid front unrounded vowel           |
| EN       | 3       | 3       | Open-mid central unrounded vowel         |
| EN       | eI      | eI      | Add Later                                |
| EN       | ex      | e@      | Add Later                                |
| EN ES JP | i       | i       | Close front unrounded vowel              |
| EN       | I       | I       | Near-close front unrounded vowel         |
| EN       | 1       | 1       | Close central unrounded vowel            |
| ES JP    | o       | o       | Close-mid back rounded vowel             |
| EN       | O       | O       | Open-mid back rounded vowel              |
| EN       | OI      | OI      | Add Later                                |
| EN       | oU      | oU      | Add Later                                | 
| ES       | u       | u       | Close back rounded vowel                 |
| EN       | uw      | u:      | Add Later                                |
| EN       | U       | U       | Near-close back rounded vowel            |
| JP       | M       | M       | Close back unrounded vowel               |
| JP       | N       | N       | Velar nasal                              |
| JP       | a0      | a_0     | Unvoiced central open unrounded vowel    |
| JP       | e0      | e_0     | Unvoiced close-mid front unrounded vowel |
| JP       | i0      | i_0     | Unvoiced close front unrounded vowel     |
| JP       | o0      | o_0     | Unvoiced close-mid back rounded vowel    |
| JP       | M0      | M_0     | Unvoiced close back unrounded vowel      |


## Consonants:
| Language | Phoneme | X-SAMPA | Description                      |
| -------- | ------- | ------- | -------------------------------- |
| EN ES JP | b       | b       | Add Later     |
| JP       | b'      | b'      | Add Later     |
| ES       | B       | B       | Add Later     |
| EN ES    | tS      | tS      | Add Later     |
| JP       | tss     | ts\     | Add Later     |
| EN ES JP | d       | d       | Add Later     |
| JP       | d'      | d'      | Add Later     |
| ES       | D       | D       | Add Later     |
| EN ES    | f       | f       | Add Later     |
| JP       | pp      | p\      | Add Later     |
| JP       | pp'     | p\'     | Add Later     |
| EN ES JP | g       | g       | Add Later     |
| JP       | g'      | g'      | Add Later     |
| ES       | G       | G       | Add Later     |
| EN JP    | h       | h       | Add Later     |
| JP       | C       | C       | Add Later     |
| ES       | x       | x       | Add Later     |
| EN       | dZ      | dZ      | Add Later     |
| EN ES JP | k       | k       | Add Later     |
| JP       | k'      | k'      | Add Later     |
| EN ES JP | l       | l       | Add Later     |
| EN ES JP | m       | m       | Add Later     |
| JP       | m'      | m'      | Add Later     |
| EN ES JP | n       | n       | Add Later     |
| EN ES JP | N       | N       | Add Later     |
| ES JP    | J       | J       | Add Later     |
| EN ES JP | p       | p       | Add Later     |
| JP       | p'      | p'      | Add Later     |
| EN ES JP | 4       | 4       | Add Later     |
| JP       | 4'      | 4'      | Add Later     |
| EN       | rr      | r\      | Add Later     |
| ES       | r       | r       | Add Later     |
| EN ES JP | s       | s       | Add Later     |
| JP       | ss      | s\      | Add Later     |
| EN ES    | S       | S       | Add Later     |
| EN ES JP | t       | t       | Add Later     |
| JP       | t'      | t'      | Add Later     |
| JP       | ts      | ts      | Add Later     |
| EN ES    | T       | T       | Add Later     |
| EN       | v       | v       | Add Later     |
| EN ES JP | w       | w       | Add Later     |
| EN ES JP | j       | j       | Add Later     |
| ES       | jj      | j\      | Add Later     |
| EN JP    | z       | z       | Add Later     |
| JP       | zz      | zz      | Add Later     |
| EN       | Z       | Z       | Add Later     |


## Flags:
| Bank       | Flag     | Symbol  |
| ---------- | -------- | ------- |
| Both       | Soft     | SFT     |
| Both       | Tense    | TNS     |
| Both       | Whisper  | WHI     |
| Both       | Power    | PWR     |
| Both       | Dark     | DRK     |
| Both       | Bright   | BRI     |
| Both       | Choir    | CHR     |
| Sin Nombre | Growl    | GRW     |
| Sin Nombre | Cursive  | CRS     |
| ES-F-01    | Falsetto | FST     |
| ES-F-01    | Musical  | MSC     |

## Included:
| File                   | Type       | Description                                                                                       | Implemented |
| ---------------------- | ---------- | ------------------------------------------------------------------------------------------------- | ----------- |
| trilang.hed            | HED        | Phoneme descriptor file                                                                           | Yes         |
| blank.table            | Dictionary | Base dictionary. Includes X-SAMPA and HED phonetic symbols.                                       | Yes         |
| dyvauxy.table          | Dictionary | ARPABET-like dictionary for all languages. Loosely follows the DYVAUX Romance phonetic symbols.   | Yes         |
| en-arpabet.table       | Dictionary | ARPABET dictionary with only English phonemes.                                                    | Yes         |
| en-x-sampa.table       | Dictionary | X-SAMPA dictionary with only English phonemes.                                                    | Yes         |
| en-s-sampa.table       | Dictionary | Simplified SAMPA dictionary with only English phonemes.                                           | Yes         |
| en-v-sampa.table       | Dictionary | VOCALOID SAMPA dictionary with only English phonemes.                                             | Yes         |
| en-czsampa.table       | Dictionary | CZSAMPA dictionary with only English phonemes.                                                    | Yes         |
| es-enye.table          | Dictionary | [e ny e] dictionary with only Spanish phonemes.                                                   | Yes         |
| es-classic.table       | Dictionary | SAMPA-like dictionary with only Spanish phonemes.                                                 | Yes         |
| es-x-sampa.table       | Dictionary | X-SAMPA dictionary with only Spanish phonemes.                                                    | Yes         |
| jp-romaji.table        | Dictionary | Romaji dictionary with only Japanese symbols. Follows Synthesizer V/CeVIO/Sinsy phonetic symbols. | Yes         |
| jp-x-sampa.table       | Dictionary | X-SAMPA dictionary with only Japanese symbols. Follows Synthesizer V/CeVIO/Sinsy phonetic symbols.| Yes         |
| jp-romaji-morae.table  | Dictionary | Romaji dictionary with Japanese syllables.                                                        | Yes         |
| jp-kana-morae.table    | Dictionary | Hiragana/Katakana dictionary with Japanese syllables.                                             | No          |

## Neat Stuff:
Due to the support of both English, Spanish and Japanese phonemes, this HED is indirectly compatible with Catalan, Tagalog, and other languages that incorporate phonology from exclusively those three languages, although, for a better, more supported experience (with way bigger phoneme coverage), I'd recommend checking out the DYVAUX Romance NNSVS Support.

## Note:
The L phoneme is cut due to it not being used by the voice providers this HED was made for.
