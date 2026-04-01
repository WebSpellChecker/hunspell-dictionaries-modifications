Hunspell dictionary for the Arabic (Saudi Arabia) (ar_SA) language.

Dictionary maintainers: Taha Zerrouki, Mohamed Kebdani
Dictionaries source: https://github.com/linuxscout/ayaspell 
License from source: GPL 2.0/LGPL 2.1/MPL 1.1 tri-license
Used under: MPL 1.1
License file: https://github.com/linuxscout/ayaspell?tab=License-1-ov-file
Current version: from Dec 16, 2016
Modified: Yes

CHANGELOG

2026-04-01 (WebSpellChecker)
  - The dictionary was incorrectly accepting أل (with hamza) as a valid form of the definite article. In standard Arabic the only correct form is ال (without hamza). All instances of this error have been removed from the .aff file, so the spellchecker will now flag words like ألكتاب or ألمدرسة as incorrect and suggest the proper forms الكتاب and المدرسة.
