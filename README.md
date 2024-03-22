# Arabic syllables to word converter using MT5 model
This model will convert arabic syllables to full words.\
The models was intented to be used after Our [syllables based wav2vec model](https://huggingface.co/IbrahimSalah/Arabic_speech_Syllables_recognition_Using_Wav2vec2) \
The model was fine tunned using Mt5 base model on modern standard arabic dataset.\
[Hugging face model link](IbrahimSalah/Arabic_Syllables_to_text_Converter_Using_MT5](https://huggingface.co/IbrahimSalah/Arabic_Syllables_to_text_Converter_Using_MT5))

# Example :
-> input : بِاْ لِنْ نِسْ بَ تِ لِ لَسْ سُيْ يَ اِحْ مِمْ مِنْ طَ قَ تِشْ شَرْ قِلْ ءَوْ سَطْ\
-> output :بِالنِسْبَةِ لِلسُنْيَاح مِن مِنْطَقَةِ الشَرْق الأَوْسَط

# To use the model ,the input needs special preprocessing steps.
  Please refer to this notebook for further details : [Syllable to text example](https://colab.research.google.com/drive/1VdY16ADTUq6SKcBiORbMm7c-BJC3JxLS?usp=sharing)
