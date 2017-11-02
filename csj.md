### CSJ (Corpus of Japanese)
#### Fullset (about 600h)
| CER (eval1) | CER (eval2) | CER (eval3) | Model | output | Paper | Published | Notes |
| :---------- | :---------- | :---------- | :-----| :----- | :---- | :-------- | :---: |
| 7.9 | 5.8 | 6.7 | CTC+Attention | Char | [Advances in Joint CTC-Attention Based End-to-End Speech Recognition with a Deep CNN Encoder and RNN-LM](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/1296.PDF) | Interspeech2017 <br> (2017/8) | + joint dec. (one-pass) <br> + RNNLM (seperate) |
| 8.4 | 6.2 | 6.9 | CTC-Attention | Char | [Advances in Joint CTC-Attention Based End-to-End Speech Recognition with a Deep CNN Encoder and RNN-LM](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/1296.PDF) | Interspeech2017 <br> (2017/8) | + joint dec. (one-pass) <br> (BLSTM encoder 320*6 layers) |
| 9.4 | 7.3 | 7.5 | CTC | Phone | Paper | Published | CTC-syllable |
| 9.5 | 7.0 | 7.8 | CTC+Attention | Char | End-to-end Japanese ASR without using morphological analyzer, pronuncication dictionary and language model | ASJ2017, spring <br> (2017/3) | (BLSTM encoder 320-5L) |
| 10.0 | 7.1 | 7.6 | CTC+Attention | Char | [Advances in Joint CTC-Attention Based End-to-End Speech Recognition with a Deep CNN Encoder and RNN-LM](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/1296.PDF) | Interspeech2017 <br> (2017/8) | + joint dec. (one-pass) |
| 10.1 | 7.1 | 7.8 | CTC+Attention | Char | [Advances in Joint CTC-Attention Based End-to-End Speech Recognition with a Deep CNN Encoder and RNN-LM](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/1296.PDF) | Interspeech2017 <br> (2017/8) | + joint dec. (rescoring) |
| 10.5 | 7.6 | 8.3 | CTC+Attention | Char | [Advances in Joint CTC-Attention Based End-to-End Speech Recognition with a Deep CNN Encoder and RNN-LM](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/1296.PDF) | Interspeech2017 <br> (2017/8) | - |
| 10.9 | 7.8 | 8.3 | CTC+Attention | Char | End-to-end Japanese ASR without using morphological analyzer, pronuncication dictionary and language model | ASJ2017, spring <br> (2017/3) | (BLSTM encoder 320-4L) |
| 11.4 | 7.9 | 9.0 | Attention | Char | [Advances in Joint CTC-Attention Based End-to-End Speech Recognition with a Deep CNN Encoder and RNN-LM](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/1296.PDF) | Interspeech2017 <br> (2017/8) | - |
| 11.5 | 7.9 | 9.0 | Attention | Char | End-to-end Japanese ASR without using morphological analyzer, pronuncication dictionary and language model | ASJ2017, spring <br> (2017/3) | - |
<!-- | * | * | * | model | output | Paper | Published | Notes | -->

#### Subset (about 240h)
| CER (eval1) | CER (eval2) | CER (eval3) | Model | Output | Paper | Published | Notes |
| :---------- | :---------- | :---------- | :-----| :----- | :---- | :-------- | :---: |
| 13.9 | 10.2 | 22.2 | CTC+Attention | Char | End-to-end Japanese ASR without using morphological analyzer, pronuncication dictionary and language model | ASJ2017, spring <br> (2017/3) | - |
| 17.2 | 12.4 | 25.4 | Attention | Char | End-to-end Japanese ASR without using morphological analyzer, pronuncication dictionary and language model | ASJ2017, spring <br> (2017/3) | - |
<!-- | * | * | * | mdoel | output | Paper | Published | Notes | -->
