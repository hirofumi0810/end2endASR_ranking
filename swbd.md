### Switchboard
#### 300h (LDC97S62)
| WER/CER <br> (SWB) | WER/CER <br> (CHE) | Model | Output | Paper | Published | Notes |
| :----------------- | :------------- | :------ | :---- | :-------- | :---: |
| 13.9 / - | 24.7 / - | CTC | Phone | [Audhkhasi et al.](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/0546.PDF) | Interspeech2017 (2017/8) | + BigLM |
| 14.0 / - | 25.3 / - | Iterated CTC | Char | [Zweig et al.](https://arxiv.org/abs/1609.05935) | ICASSP2017 <br> (2017/4) | + dictionary <br> + word ngram |
| 14.5 / - | - | CTC | Phone | [Miao et al.](https://www.cs.cmu.edu/~ymiao/pub/icassp2016_ctc.pdf) | ICASSP 2016 <br> (2016/4) | VTLN-filterbank |
| 19.8 / - | 32.1 / - | Iterated CTC | Char | [Zweig et al.](https://arxiv.org/abs/1609.05935) | ICASSP2017 <br> (2017/4) | + Char ngram |
| 20.8 / - | 30.4 / - | CTC | Word | [Audhkhasi et al.](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/0546.PDF) | Interspeech2017 (2017/8) | + GloVe Init. (24M + 560M) |
| 21.4 / - | 40.2 / - | CTC | Char | [Maas et al.](http://deeplearning.stanford.edu/lexfree/lexfree.pdf) | Published | + 3-layer RNNLM |
| 23.1 / - | 40.8 / - | Hierarchical <br> attn | Char | [Toshiniwal et al.](https://arxiv.org/abs/1704.01631) | Interspeech2017 <br> (2017/8) | Char <br> + Phone <br> + HHM States |
| 24.7 / - | 37.1 / - | Iterated CTC | Char | [Zweig et al.](https://arxiv.org/abs/1609.05935) | ICASSP2017 <br> (2017/4) | no LM |
| 25.8 / - | 46.0 / - | Attn | Word | [Lu et al.](http://homepages.inf.ed.ac.uk/llu/pdf/llu_icassp16.pdf) | ICASSP 2016 <br> (2016/4) | + 3-gram |
| 26.3 / - | 46.5 / - | Attn | Word | [Lu et al.](http://homepages.inf.ed.ac.uk/llu/pdf/llu_icassp16.pdf) | ICASSP 2016 <br> (2016/4) | no LM |
| 27.3 / - | 48.2 / - | Attn | Char | [Lu et al.](http://homepages.inf.ed.ac.uk/llu/pdf/llu_icassp16.pdf) | ICASSP 2016 <br> (2016/4) | no LM |
| 20.0 / - | 31.8 / - | CTC | Char | DeepSpeech | Published | a |
| 38.0 / - | 56.1 / - | CTC | Char | [Maas et al.](http://deeplearning.stanford.edu/lexfree/lexfree.pdf) | Published | no LM |
| 38.8 / - | 59.9 / - | Attn | Word | [Lu et al.](http://www.isca-speech.org/archive/interspeech_2015/i15_3249.html) | Interspeech2015 <br> (2015/9) | no LM |
<!-- | - | - | - | - | model | output | Paper | Published | Notes | -->

#### 2000h (+ Fisher)
| WER/CER <br> (SWB) | WER/CER <br> (CHE) | Model | Output | Paper | Published | Notes |
| :----------------- | :----------------- | :---- | :------ | :---- | :-------- | :---: |
| 9.6 / - | 16.0 / - | CTC | Phone | [Audhkhasi et al.](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/0546.PDF) | Interspeech2017 (2017/8) | + BigLM |
| 12.5 / - | 18.0 / - | CTC | Word | [Audhkhasi et al.](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/0546.PDF) | Interspeech2017 (2017/8) | + GloVe Init. (24M + 560M) <br> + BigLM |
| 13.0 / - | 18.8 / - | CTC | Word | [Audhkhasi et al.](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/0546.PDF) | Interspeech2017 (2017/8) | + GloVe Init. (24M + 560M) |
<!-- | - | - | - | - | model | output | Paper | Published | Notes | -->
