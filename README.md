# tessdata_best
Best (most accurate) trained LSTM models.

These traineddata files are for people willing to trade a lot of speed for slightly better accuracy. It is also better for certain retraining scenarios for advanced users. 

When using the models in this repository, only the new LSTM-based OCR engine is supported. The legacy 'tesseract'engine is not supported with these files, so Tesseract's oem modes '0' and '2' won't work with them.

Initial capitals indicate the one model for all languages in that script. Most of the script models include English training data as well  as the script, but not for Cyrillic, as that would have a major ambiguity    problem.

Latin is all latin-based languages 
except vie, which has its own    Vietnamese. 

Devanagari is  hin+san+mar+nep+eng

Fraktur is basically a    combination of all the latin-based languages that have an 'old' variant.
