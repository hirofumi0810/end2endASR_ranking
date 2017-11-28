### WSJ-SI284, WSJ1 (clean, 81h)
| WER/CER | Model | Output | Paper | Published | Notes |
| :------ | :---- | :----- | :---- | :-------- | :---: |
| 7.25 / - | CTC | Phone | [Kanda et al.](http://www.isca-speech.org/archive/Interspeech_2016/pdfs/0071.PDF) | Interspeech2016 <br> (2016/9) | MAP decoding <br> (3-gram) |
| 7.34 / - | CTC | Char | [Miao et al.](https://arxiv.org/abs/1507.08240) | ASRU2015 <br> (2015/12) | extended 3-gram |
| 7.87 / - | CTC | Phone | [Miao et al.](https://arxiv.org/abs/1507.08240) | ASRU2015 <br> (2015/12) | 3-gram |
| 8.90 / 3.80 | CTC | Char | [Hwang et al.](https://arxiv.org/abs/1601.06581) | ICASSP2016 <br> (2016/4) | Tree-based online beam search |
| 9.07 / - | CTC | Char | [Miao et al.](https://arxiv.org/abs/1507.08240) | ASRU2015 <br> (2015/12) | 3-gram |
| 9.6 / - | LSD | Word pieces | [Chan et al.](https://arxiv.org/abs/1610.03035) | ICLR2017 <br> (2017/4) | + LSD4 <br> + CNN encoder <br> (no LM) |
| 11.8 / - | Attn | Char | [Zhang et al.](https://arxiv.org/abs/1610.03022) | ICASSP2017 <br> (2017/4) | + CNN |
| 12.9 / - | LSD | Word pieces | [Chan et al.](https://arxiv.org/abs/1610.03035) | ICLR2017 <br> (2017/4) | + LSD4 <br> (no LM) |
| 14.1 / 5.7 | CTC | Char | [Hannun et al.](https://arxiv.org/abs/1408.2873) | 2014/12 | 2-gram |
| 14.8 / - | Attn | Char | [Chan et al.](https://arxiv.org/abs/1610.03035) | ICLR2017 <br> (2017/4) | + weight noise <br> (no LM) |
| - / 7.24 | MTL <br> (CTC+Attn) | Char | [Kim et al.](https://arxiv.org/abs/1609.06773) | ICASSP2017 <br> (2017/4) | CTC:Attention=8:2 <br> (no LM) |
| - / 8.07 | Attn | Char | [Kim et al.](https://arxiv.org/abs/1609.06773) | ICASSP2017 <br> (2017/4) | location-based <br> (no LM) |
| - / 8.27 | Attn | Char | [Kim et al.](https://arxiv.org/abs/1609.06773) | ICASSP2017 <br> (2017/4) | content-based <br> (no LM) |
| 33.0 / - | Attn | Char | [Chan et al.](http://www.isca-speech.org/archive/Interspeech_2016/pdfs/0334.PDF) | Interspeech2016 (2016/9) | Online <br> (no LM) |
| - / 10.06 | CTC | Char | [Kim et al.](https://arxiv.org/abs/1609.06773) | ICASSP2017 <br> (2017/4) | no LM |
| 38.37 / 10.96 | CTC | Char | [Hwang et al.](https://arxiv.org/abs/1601.06581) | ICASSP2016 <br> (2016/4) | Tree-based online beam search <br> (no LM) |
| 35.8 / 10.0 | CTC | Char | [Hannun et al.](https://arxiv.org/abs/1408.2873) | 2014/12 | no LM |
<!-- | - / - | model | output | Paper | Published | Notes | -->


### WSJ-SI84, WSJ0 (noisy, 15h)
| WER/CER | Model | Output | Paper | Published | Notes |
| :------ | :---- | :----- | :---- | :-------- | :---: |
| - / 6.54 | Att Wav2Text | Char | [Attention-based Wav2text with Feature Transfer Learning](https://arxiv.org/abs/1709.07814) | ASRU2017 <br> (2017/12) | transfer from multi-target |
| - / 15.12 | MTL <br> (CTC+Attn) | Char | [Kim et al.](https://arxiv.org/abs/1609.06773) | ICASSP2017 <br> (2017/4) | CTC:Attention=5:5 <br> (no LM) |
| - / 16.32 | Attn | Char | [Kim et al.](https://arxiv.org/abs/1609.06773) | ICASSP2017 <br> (2017/4) | location-based <br> (no LM) |
| - / 22.10 | Attn | Char | [Kim et al.](https://arxiv.org/abs/1609.06773) | ICASSP2017 <br> (2017/4) | content-based <br> (no LM) |
| - / 24.69 | CTC | Char | [Kim et al.](https://arxiv.org/abs/1609.06773) | ICASSP2017 <br> (2017/4) | no LM |
<!-- | - / - | model | output | Paper | Published | Notes | -->
