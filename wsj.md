### WSJ-SI284, WSJ1 (81h)
| WER/CER (eval92) | Model | Output | LM | Paper | Published | Notes |
| :------ | :---- | :----- | :- | :---- | :-------- | :---: |
| 5.6 / - | Att<be>+CTC | char | wordLM <br>+charLM | [Hori et at.](http://www.merl.com/publications/docs/TR2017-181.pdf) | ASRU2017 | joint decoding <br> (Att+CTC+<br>charLM+wordLM) |
| 6.7 / - | Att | Char | extended <br> 3-gram | [Chorowski et al.](http://www.isca-speech.org/archive/Interspeech_2016/pdfs/0071.PDF) | Interspeech2017 | Label smoothing |
| 6.9 / - | Att | Char | RNNLM | [Kannan et al.](https://arxiv.org/abs/1712.01996) | ICASSP2018 | - |
| 7.25 / - | CTC | Phone | 3-gram | [Kanda et al.](https://www.isca-speech.org/archive/Interspeech_2017/pdfs/0343.PDF) | Interspeech2016 | MAP decoding |
| 7.34 / - | CTC | Char | extended <br> 3-gram | [Miao et al.](https://arxiv.org/abs/1507.08240) | ASRU2015 | - |
| 7.6 / - | Att | Char | 3-gram | [Kannan et al.](https://arxiv.org/abs/1712.01996) | ICASSP2018 | - |
| 7.87 / - | CTC | Phone | 3-gram | [Miao et al.](https://arxiv.org/abs/1507.08240) | ASRU2015 | - |
| 8.2 / - | Att | WP | RNNLM | [Kannan et al.](https://arxiv.org/abs/1712.01996) | ICASSP2018 | - |
| 8.90 / 3.80 | CTC | Char | - | [Hwang et al.](https://arxiv.org/abs/1601.06581) | ICASSP2016 | Tree-based online beam search |
| 9.07 / - | CTC | Char | 3-gram | [Miao et al.](https://arxiv.org/abs/1507.08240) | ASRU2015 | - |
| 9.3 / 3.9 | Att | Char | extended <br> 3-gram | [Bahdanau et al.](https://arxiv.org/abs/1508.04395) | ICASSP2016 | WFST decoding <br> GRU enc-dec |
| 9.3 / - | Att | WP | 3-gram | [Kannan et al.](https://arxiv.org/abs/1712.01996) | ICASSP2018 | - |
| 9.6 / - | LSD | Word pieces | - | [Chan et al.](https://arxiv.org/abs/1610.03035) | ICLR2017 | LSD4 <br>+VGG-BLSTM |
| 10.3 / - | Att | Char | - | [Kannan et al.](https://arxiv.org/abs/1712.01996) | ICASSP2018 | - |
| 10.53 / - | Att | Char | - | [Zhang et al.](https://arxiv.org/abs/1610.03022) | ICASSP2017 | VGG <br>+ResConvLSTM |
| 10.6 / - | Att | Char | - | [Chorowski et al.](http://www.isca-speech.org/archive/Interspeech_2016/pdfs/0071.PDF) | Interspeech2017 | Unigram <br> label smoothing |
| 10.8 / 4.8 | Att | Char | 3-gram | [Bahdanau et al.](https://arxiv.org/abs/1508.04395) | ICASSP2016 | WFST decoding |
| 10.8 / - | CTC | Char | external LM | [Battenberg et al.](https://arxiv.org/abs/1707.07413) | ASRU2017 | - |
| 12.3 / - | Att | WP | - | [Kannan et al.](https://arxiv.org/abs/1712.01996) | ICASSP2018 | - |
| 12.9 / - | LSD | Word pieces | - | [Chan et al.](https://arxiv.org/abs/1610.03035) | ICLR2017 | LSD4 |
| 13.9 / - | MoChA | Char | - | [Chiu et al.](https://arxiv.org/abs/1712.05382) | ICLR2018 | online |
| 14.05 / - | RNN <br> transducer | Char | external LM | [Battenberg et al.](https://arxiv.org/abs/1707.07413) | ASRU2017 | - |
| 14.07 / - | Attn | Char | external LM | [Battenberg et al.](https://arxiv.org/abs/1707.07413) | ASRU2017 | - |
| 14.1 / 5.7 | CTC | Char | 2-gram | [Hannun et al.](https://arxiv.org/abs/1408.2873) | 2014/12 | - |
| 14.2 / - | Att | Char | - | [Chorowski et al.](http://www.isca-speech.org/archive/Interspeech_2016/pdfs/0071.PDF) | Interspeech2017 | - |
| 14.8 / - | Att | Char | - | [Chan et al.](https://arxiv.org/abs/1610.03035) | ICLR2017 | - |
| 14.99 / - | Att | Char | - | [Battenberg et al.](https://arxiv.org/abs/1707.07413) | ASRU2017 | - |
| 15.29 / - | RNN <br> transducer | Char | - | [Battenberg et al.](https://arxiv.org/abs/1707.07413) | ASRU2017 | - |
| 15.73 / - | CTC | Char | - | [Battenberg et al.](https://arxiv.org/abs/1707.07413) | ASRU2017 | - |
| 17.04 / 6.54 | Att | Char | - | [Tjandra et al.](https://arxiv.org/abs/1709.07814) | ASRU2017 |　Wav2text <br>  + transfer from multi-target |
| 18.6 / 6.4 | Att | Char | - | [Bahdanau et al.](https://arxiv.org/abs/1508.04395) | ICASSP2016 | GRU enc-dec |
| - / 7.24 | Att+CTC | Char | - | [Kim et al.](https://arxiv.org/abs/1609.06773) | ICASSP2017 | Att:CTC=2:8 |
| - / 8.07 | Att | Char | - | [Kim et al.](https://arxiv.org/abs/1609.06773) | ICASSP2017 | location-based |
| - / 8.27 | Att | Char | - | [Kim et al.](https://arxiv.org/abs/1609.06773) | ICASSP2017 | content-based |
| 33.0 / - | Att | Char | - | [Chan et al.](http://www.isca-speech.org/archive/Interspeech_2016/pdfs/0334.PDF) | Interspeech2016 | Online |
| - / 10.06 | CTC | Char | - | [Kim et al.](https://arxiv.org/abs/1609.06773) | ICASSP2017 | - |
| 38.37 / 10.96 | CTC | Char | - | [Hwang et al.](https://arxiv.org/abs/1601.06581) | ICASSP2016 | Tree-based online beam search |
| 35.8 / 10.0 | CTC | Char | - | [Hannun et al.](https://arxiv.org/abs/1408.2873) | 2014/12 | - |
<!-- | - / - | model | output | LM | Paper | Published | Notes | -->


### WSJ-SI84, WSJ0 (15h)
| WER/CER (eval92) | Model | Output | LM | Paper | Published | Notes |
| :------ | :---- | :----- | :- | :---- | :-------- | :---: |
| - / 15.12 | Att+CTC | Char | - | [Kim et al.](https://arxiv.org/abs/1609.06773) | ICASSP2017 | Att:CTC=5:5 |
| - / 16.32 | Att | Char | - | [Kim et al.](https://arxiv.org/abs/1609.06773) | ICASSP2017 | location-based |
| - / 22.10 | Att | Char | - | [Kim et al.](https://arxiv.org/abs/1609.06773) | ICASSP2017 | content-based |
| - / 24.69 | CTC | Char | - | [Kim et al.](https://arxiv.org/abs/1609.06773) | ICASSP2017 | - LM |
<!-- | - / - | model | output | LM | Paper | Published | Notes | -->
