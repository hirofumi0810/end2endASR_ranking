### CSJ (Corpus of Japanese)
#### APS+SPS (about 600h)
| WER/CER (eval1) | WER/CER (eval2) | WER/CER (eval3) | Model | Output | LM | Paper | Published | Notes |
| :-------------- | :-------------- | :-------------- | :---- | :----- | :- | :---- | :-------- | :---: |
| - / 7.9 | - / 5.8 | - / 6.7 | Attn+CTC | Char | RNNLM | [Hori et al.](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/1296.PDF) | Interspeech2017 | joint dec. (one-pass, seperate) |
| - / 8.4 | - / 6.2 | - / 6.9 | Att+CTC | Char | no | [Hori et al.](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/1296.PDF) | Interspeech2017 | joint dec. (one-pass) <br> (BLSTM 6L-320H) |
| 11.90 / 9.4 | 9.24 / 7.3 | 9.65 / 7.5 | CTC | Char | 2-gram | [Kanda et al.](http://www.isca-speech.org/archive/Interspeech_2016/pdfs/0071.PDF) | Interspeech2016 | MAP decoding |
| - / 9.5 | - / 7.0 | - / 7.8 | Attn+CTC | Char | no | Watanabe et al. | ASJ2017, spring | BLSTM 5L-320H |
| - / 10.0 | - / 7.1 | - / 7.6 | Attn+CTC | Char | no | [Hori et al.](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/1296.PDF) | Interspeech2017 | joint dec. (one-pass) |
| - / 10.1 | - / 7.1 | - / 7.8 | Attn+CTC | Char | no | [Hori et al.](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/1296.PDF) | Interspeech2017 | joint dec. (rescoring) |
| - / 10.4 | - / 7.7 | - / 8.9 | Att | Char | no | [Hayashi et al.](https://arxiv.org/abs/1804.08050) | Interspeech2018? |  Multi-head <br> (loc*2 + cov*2) |
| - / 10.5 | - / 7.6 | - / 8.3 | Attn+CTC | Char | no | [Hori et al.](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/1296.PDF) | Interspeech2017 | - |
| - / 10.9 | - / 7.8 | - / 8.3 | Attn+CTC | Char | no | Watanabe et al. | ASJ2017, spring | BLSTM 4L-320H |
| - / 11.4 | - / 7.9 | - / 9.0 | Att | Char | no | [Hori et al.](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/1296.PDF) | Interspeech2017 | - |
| - / 11.5 | - / 7.9 | - / 9.0 | Att | Char | no | Watanabe et al. | ASJ2017, spring | - |
<!-- | * | * | * | model | Output | LM | Paper | Published | Notes | -->


#### APS (about 240h)
| WER/CER (eval1) | WER/CER (eval2) | WER/CER (eval3) | Model | Output | LM | Paper | Published | Notes |
| :-------------- | :-------------- | :-------------- | :---- | :----- | :- | :---- | :-------- | :---: |
| 12.94 / - | 10.33 / - | 13.11 / - | CTC | Char | 2-gram | [Kanda et al.](http://www.isca-speech.org/archive/Interspeech_2016/pdfs/0071.PDF) | Interspeech2016 | MAP decoding |
| 13.65 | - | - | Att | Word | - | [Ueno et al.] | ICASSP2018 | WordAtt+CharCTC <br> + resolbing UNK |
| - / 13.9 | - / 10.2 | - / 22.2 | Attn+CTC | Char | no | Watanabe et al. | ASJ2017, spring | - |
| - / 17.2 | - / 12.4 | - / 25.4 | Att | Char | no | Watanabe et al. | ASJ2017, spring | - |
<!-- | * | * | * | mdoel | Output | LM | Paper | Published | Notes | -->
