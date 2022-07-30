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
| Language | Phoneme | X-SAMPA | Description                      |
| -------  | ------- | ------- | -------------------------------- |
| ES JP    | a       | a       | Central open unrounded vowel     |
| EN       | A       | A       | Add Later                        |
| EN       | aI      | aI      | Add Later                        |
| EN       | aU      | aU      | Add Later                        |
| EN       | ax      | @       | Add Later                        |
| EN       | V       | V       | Add Later                        |
| EN       | {       | {       | Add Later                        |
| ES JP    | e       | e       | Close-mid front unrounded vowel  |
| EN       | E       | E       | Add Later                        |
| EN       | 3       | 3       | Add Later                        |
| EN       | eI      | eI      | Add Later                        |
| EN       | ex      | e@      | Add Later                        |
| EN ES JP | i       | i       | Close front unrounded vowel      |
| EN       | I       | I       | Add Later                        |
| EN       | 1       | 1       | Add Later                        |
| ES JP    | o       | o       | Close-mid back rounded vowel     |
| EN       | O       | O       | Add Later                        |
| EN       | OI      | OI      | Add Later                        |
| EN       | oU      | oU      | Add Later                        |
| ES       | u       | u       | Close back rounded vowel         |
| EN       | uw      | u:      | Add Later                        |
| EN       | U       | U       | Add Later                        |
| JP       | M       | M       | Add Later                        |
| JP       | N       | N       | Add Later                        |
| JP       | a0      | a_0     | Add Later                        |
| JP       | e0      | e_0     | Add Later                        |
| JP       | i0      | i_0     | Add Later                        |
| JP       | o0      | o_0     | Add Later                        |
| JP       | M0      | M_0     | Add Later                        |


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
| Both       | Soft     | S       |
| Both       | Tense    | T       |
| Both       | Whisper  | W       |
| Both       | Power    | P       |
| Both       | Dark     | D       |
| Both       | Bright   | B       |
| Sin Nombre | Growl    | G       |
| Sin Nombre | Cursive  | C       |
| ES-F-01    | Falsetto | F       |
| ES-F-01    | Musical  | M       |

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
