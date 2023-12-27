## v0.1:
LTVA:
- Macros are now dynamically allocated, adds unexpected bugs but improves RAM usage. Instrument and each FM op can have up to 32 macros each, although yet no system exists that uses that many. The same dynamic allocation, although simplified, is done for hardware sequences and note table which is used in sample map
- Fixed annoying one-frame glitch in macros menu (when you open instrument the first time; pay the attention to the area where macro names are displayed)
- Added options to made tabs borders round or sharp
- remove "guru mode" (always expose full color settings)
- throw a warning and refuse to load instrument/song file if encountered instrument is of unknown type
- remove the ability to **save** instrument in old format (useless and afaik never even used in the program)

freq-mod:
- 86-PCM streo DAC fix
- Remove basic mode, tutorial and intro
