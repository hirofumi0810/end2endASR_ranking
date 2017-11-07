### CSJ (Corpus of Japanese)
#### Fullset (about 600h)
| WER/CER (eval1) | WER/CER (eval2) | WER/CER (eval3) | Model | output | Paper | Published | Notes |
| :---------- | :---------- | :---------- | :-----| :----- | :---- | :-------- | :---: |
| - / 7.9 | - / 5.8 | - / 6.7 | MTL <br> (CTC+Attention) | Char | [Hori et al.](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/1296.PDF) | Interspeech2017 <br> (2017/8) | + joint dec. (one-pass) <br> + RNNLM (seperate) |
| - / 8.4 | - / 6.2 | - / 6.9 | CTC-Attention | Char | [Hori et al.](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/1296.PDF) | Interspeech2017 <br> (2017/8) | + joint dec. (one-pass) <br> (BLSTM encoder 320*6 layers) |
| 11.90 / 9.4 | 9.24 / 7.3 | 9.65 / 7.5 | CTC | Char | [Kanda et al.](http://www.isca-speech.org/archive/Interspeech_2016/pdfs/0071.PDF) | Interspeech2016 <br> (2016/9) | MAP decoding |
| - / 9.5 | - / 7.0 | - / 7.8 | MTL <br> (CTC+Attention) | Char | Watanabe et al. | ASJ2017, spring <br> (2017/3) | (BLSTM encoder 320-5L) |
| - / 10.0 | - / 7.1 | - / 7.6 | MTL <br> (CTC+Attention) | Char | [Hori et al.](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/1296.PDF) | Interspeech2017 <br> (2017/8) | + joint dec. (one-pass) |
| - / 10.1 | - / 7.1 | - / 7.8 | MTL <br> (CTC+Attention) | Char | [Hori et al.](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/1296.PDF) | Interspeech2017 <br> (2017/8) | + joint dec. (rescoring) |
| - / 10.5 | - / 7.6 | - / 8.3 | MTL <br> (CTC+Attention) | Char | [Hori et al.](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/1296.PDF) | Interspeech2017 <br> (2017/8) | - |
| - / 10.9 | - / 7.8 | - / 8.3 | MTL <br> (CTC+Attention) | Char | Watanabe et al. | ASJ2017, spring <br> (2017/3) | (BLSTM encoder 320-4L) |
| - / 11.4 | - / 7.9 | - / 9.0 | Attention | Char | [Hori et al.](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/1296.PDF) | Interspeech2017 <br> (2017/8) | - |
| - / 11.5 | - / 7.9 | - / 9.0 | Attention | Char | Watanabe et al. | ASJ2017, spring <br> (2017/3) | - |
<!-- | * | * | * | model | output | Paper | Published | Notes | -->


#### Subset (about 240h)
| WER/CER (eval1) | WER/CER (eval2) | WER/CER (eval3) | Model | Output | Paper | Published | Notes |
| :---------- | :---------- | :---------- | :-----| :----- | :---- | :-------- | :---: |
| 12.94 / - | 10.33 / - | 13.11 / - | CTC | Char | [Kanda et al.](http://www.isca-speech.org/archive/Interspeech_2016/pdfs/0071.PDF) | Interspeech2016 <br> (2016/9) | MAP decoding |
| - / 13.9 | - / 10.2 | - / 22.2 | MTL <br> (CTC+Attention) | Char | Watanabe et al. | ASJ2017, spring <br> (2017/3) | - |
| - / 17.2 | - / 12.4 | - / 25.4 | Attention | Char | Watanabe et al. | ASJ2017, spring <br> (2017/3) | - |
<!-- | * | * | * | mdoel | output | Paper | Published | Notes | -->
