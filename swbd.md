### Switchboard
#### 300h
| WER (SWBD) | CER (SWBD) | WER (CH) | CER (CH) | Model | Output | Paper | Published | Notes |
| :--------- | :--------- | :------- | :------- | :---- | :------ | :---- | :-------- | :---: |
| 13.9 | - | 24.7 | - | CTC | Phone | [Direct Acoustic-to-Word Models for English Conversational Speech Recognition](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/0546.PDF) | Interspeech2017 (2017/8) | + BigLM |
| 14.5 | - | - | - | CTC | Phone | [An Empirical Exploration of CTC Acoustic Models](https://www.cs.cmu.edu/~ymiao/pub/icassp2016_ctc.pdf) | ICASSP 2016 <br> (2016/4) | VTLN-filterbank |
| 20.8 | - | 30.4 | - | CTC | Word | [Direct Acoustic-to-Word Models for English Conversational Speech Recognition](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/0546.PDF) | Interspeech2017 (2017/8) | + GloVe Init. (24M + 560M) |
| 25.8 | - | 46.0 | - | Attention | Word | [On Training the Recurrent Neural Network Encoder-Decoder for Large Vocabulary End-to-End Speech Recognition](http://homepages.inf.ed.ac.uk/llu/pdf/llu_icassp16.pdf)] | ICASSP 2016 <br> (2016/4) | + 3-gram |
| 26.3 | - | 46.5 | - | Attention | Word | [On Training the Recurrent Neural Network Encoder-Decoder for Large Vocabulary End-to-End Speech Recognition](http://homepages.inf.ed.ac.uk/llu/pdf/llu_icassp16.pdf)] | ICASSP 2016 <br> (2016/4) | no LM |
| 27.3 | - | 48.2 | - | Attention | Char | [On Training the Recurrent Neural Network Encoder-Decoder for Large Vocabulary End-to-End Speech Recognition](http://homepages.inf.ed.ac.uk/llu/pdf/llu_icassp16.pdf)] | ICASSP 2016 <br> (2016/4) | no LM |
| 20.0 | - | 31.8 | - | CTC | Char | DeepSpeech | Published | Notes |
| 38.0 | - | 56.1 | - | CTC | Char | Lexicon-Free | Published | no LM |
| 38.8 | - | 59.9 | - | Attention | Word | [A Study of the Recurrent Neural Network Encoder-Decoder for Large Vocabulary Speech Recognition](http://www.isca-speech.org/archive/interspeech_2015/i15_3249.html) | Interspeech2015 <br> (2015/9) | Notes |
<!-- | - | - | - | - | model | output | Paper | Published | Notes | -->

#### 2000h (+ Fisher)
| WER (SWBD) | CER (SWBD) | WER (CH) | CER (CH) | Model | Output | Paper | Published | Notes |
| :--------- | :--------- | :------- | :------- | :---- | :------ | :---- | :-------- | :---: |
| 9.6 | - | 16.0 | - | CTC | Phone | [Direct Acoustic-to-Word Models for English Conversational Speech Recognition](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/0546.PDF) | Interspeech2017 (2017/8) | + BigLM |
| 12.5 | - | 18.0 | - | CTC | Word | [Direct Acoustic-to-Word Models for English Conversational Speech Recognition](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/0546.PDF) | Interspeech2017 (2017/8) | + GloVe Init. (24M + 560M) <br> + BigLM |
| 13.0 | - | 18.8 | - | CTC | Word | [Direct Acoustic-to-Word Models for English Conversational Speech Recognition](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/0546.PDF) | Interspeech2017 (2017/8) | + GloVe Init. (24M + 560M) |
| - | - | - | - | model | output | Paper | Published | Notes |
<!-- | - | - | - | - | model | output | Paper | Published | Notes | -->
