### WSJ-SI284, WSJ1 (clean, 81h)
| WER/CER | Model | Output | LM | Paper | Published | Notes |
| :------ | :---- | :----- | :- | :---- | :-------- | :---: |
| 6.7 / - | Attn | Char | 3-gram | [Chorowski et al.](http://www.isca-speech.org/archive/Interspeech_2016/pdfs/0071.PDF) | Interspeech2017 | Label smoothing |
| 7.25 / - | CTC | Phone | 3-gram | [Kanda et al.](https://www.isca-speech.org/archive/Interspeech_2017/pdfs/0343.PDF) | Interspeech2016 | MAP decoding |
| 7.34 / - | CTC | Char | extended <br> 3-gram | [Miao et al.](https://arxiv.org/abs/1507.08240) | ASRU2015 | - |
| 7.87 / - | CTC | Phone | 3-gram | [Miao et al.](https://arxiv.org/abs/1507.08240) | ASRU2015 | - |
| 8.90 / 3.80 | CTC | Char | - | [Hwang et al.](https://arxiv.org/abs/1601.06581) | ICASSP2016 | Tree-based online beam search |
| 9.07 / - | CTC | Char | 3-gram | [Miao et al.](https://arxiv.org/abs/1507.08240) | ASRU2015 | - |
| 9.6 / - | LSD | Word pieces | no | [Chan et al.](https://arxiv.org/abs/1610.03035) | ICLR2017 | LSD4 <br> + VGG-BLSTM |
| 10.53 / - | Attn | Char | - | [Zhang et al.](https://arxiv.org/abs/1610.03022) | ICASSP2017 | VGG <br> + ResConvLSTM |
| 10.6 / - | Attn | Char | - | [Chorowski et al.](http://www.isca-speech.org/archive/Interspeech_2016/pdfs/0071.PDF) | Interspeech2017 | Label smoothing <br> |
| 12.9 / - | LSD | Word pieces | no | [Chan et al.](https://arxiv.org/abs/1610.03035) | ICLR2017 | LSD4 |
| 13.9 / - | MoChA | Char | no | [Chiu et al.](https://arxiv.org/abs/1712.05382) | ICLR2018 | online |
| 14.1 / 5.7 | CTC | Char | 2-gram | [Hannun et al.](https://arxiv.org/abs/1408.2873) | 2014/12 | - |
| 14.8 / - | Attn | Char | no | [Chan et al.](https://arxiv.org/abs/1610.03035) | ICLR2017 | - |
| - / 7.24 | MTL <br> (CTC+Attn) | Char | no | [Kim et al.](https://arxiv.org/abs/1609.06773) | ICASSP2017 | CTC:Attn=8:2 |
| - / 8.07 | Attn | Char | no | [Kim et al.](https://arxiv.org/abs/1609.06773) | ICASSP2017 | location-based |
| - / 8.27 | Attn | Char | no | [Kim et al.](https://arxiv.org/abs/1609.06773) | ICASSP2017 | content-based |
| 33.0 / - | Attn | Char | no | [Chan et al.](http://www.isca-speech.org/archive/Interspeech_2016/pdfs/0334.PDF) | Interspeech2016 | Online |
| - / 10.06 | CTC | Char | no | [Kim et al.](https://arxiv.org/abs/1609.06773) | ICASSP2017 | - |
| 38.37 / 10.96 | CTC | Char | no | [Hwang et al.](https://arxiv.org/abs/1601.06581) | ICASSP2016 | Tree-based online beam search |
| 35.8 / 10.0 | CTC | Char | no | [Hannun et al.](https://arxiv.org/abs/1408.2873) | 2014/12 | - |
<!-- | - / - | model | output | LM | Paper | Published | Notes | -->


### WSJ-SI84, WSJ0 (noisy, 15h)
| WER/CER | Model | Output | LM | Paper | Published | Notes |
| :------ | :---- | :----- | :- | :---- | :-------- | :---: |
| - / 6.54 | Att Wav2Text | Char | - | [Tjandra et al.](https://arxiv.org/abs/1709.07814) | ASRU2017 | transfer from multi-target |
| - / 15.12 | MTL <br> (CTC+Attn) | Char | no | [Kim et al.](https://arxiv.org/abs/1609.06773) | ICASSP2017 | CTC:Attn=5:5 |
| - / 16.32 | Attn | Char | no | [Kim et al.](https://arxiv.org/abs/1609.06773) | ICASSP2017 | location-based |
| - / 22.10 | Attn | Char | no | [Kim et al.](https://arxiv.org/abs/1609.06773) | ICASSP2017 | content-based |
| - / 24.69 | CTC | Char | no | [Kim et al.](https://arxiv.org/abs/1609.06773) | ICASSP2017 | no LM |
<!-- | - / - | model | output | LM | Paper | Published | Notes | -->
