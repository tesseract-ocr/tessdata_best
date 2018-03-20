# tessdata_best
Best (most accurate) trained LSTM models.

These traineddata files are for people willing to trade a lot of speed for slightly better accuracy. It is also better for certain retraining scenarios for advanced users. 

If you want best to run faster, it is easy to integerize "best" at the cost of a small loss in accuracy.

When using the models in this repository, only the new LSTM-based OCR engine is supported. The legacy 'tesseract'engine is not supported with these files, so Tesseract's oem modes '0' and '2' won't work with them.


