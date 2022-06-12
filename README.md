# AltIBMTTSDictionaries
An alternative set of dictionaries for IBMTTS.
Smaller than other dictionaries, but tries to be less agressive about modifying words.
## ViaVoice dictionary
This project contains dictionary files specifically optimized for ViaVoice TTS 6.7, the same version used in IBMTTS for Linux, but also available for Windows, which are located in the ViaVoice TTS 6.7 folder in this repository. The ViaVoice dictionaries fix a number of IBMTTS-specific pronunciation issues, and remove over 280 words that IBMTTS pronounces correctly. To use the dictionaries on Linux, rename enumain.dic and enuroot.dic to main.dct and root.dct, respectively, and place them in /var/opt/IBM/ibmtts/dict, or /var/opt/IBM/ibmtts/dict/en, or /var/opt/IBM/ibmtts/dict/en_US. Enuabbr.dic is compatible with IBMTTS as well, and can be renamed to abbreviation.dct.
# Contributing
If you'd like to contribute words to this dictionary, please open an issue with you word you want corrected, as well as your suggested pronunciation, and provide sources for it, whether that would be dictionaries, YouTube videos or similar. However, before you suggest a change, make sure that the word you want changed is actually pronounced incorrectly, and that the original pronunciation is not less common but otherwise acceptable, as your entry may get removed if this turns out to be the case.
