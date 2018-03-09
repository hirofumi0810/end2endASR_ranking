### Switchboard
#### 300h (LDC97S62)
| WER/CER <br> (SWB) | WER/CER <br> (CHE) | Model | Output <br> Unit | Paper | Published | Notes |
| :----------------- | :----------------- | :---- | :----- | :---- | :-------- | :---: |
| 13.9 / - | 24.7 / - | CTC | Phone | [Audhkhasi et al.](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/0546.PDF) | IS2017 (2017/8) | BigLM |
| 14.0 / - | 25.3 / - | CTC | Char | [Zweig et al.](https://arxiv.org/abs/1609.05935) | ICASSP2017 <br> (2017/4) | Lexicon <br> + word n-gram |
| 14.5 / - | - | CTC | Phone | [Miao et al.](https://www.cs.cmu.edu/~ymiao/pub/icassp2016_ctc.pdf) | ICASSP 2016 <br> (2016/4) | VTLN-filterbank |
| 15.1 / - | 26.3 / - | CTC | Char | [Zweig et al.](https://arxiv.org/abs/1609.05935) | ICASSP2017 <br> (2017/4) | Lexicon <br> + word RNNLM |
| 19.8 / - | 32.1 / - | CTC | Char | [Zweig et al.](https://arxiv.org/abs/1609.05935) | ICASSP2017 <br> (2017/4) | Char n-gram |
| 20.0 / - | 31.8 / - | CTC | Char | DeepSpeech | Published | - |
| 20.8 / - | 30.4 / - | CTC | Word | [Audhkhasi et al.](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/0546.PDF) | IS2017 <br> (2017/8) | GloVe Init. |
| 21.3 / - | 40.0 / - | CTC | Char | [Krishna et al.] | ICASSP2018 <br> (2018/) | 1-D CNN <br> + char 9-gram |
| 21.4 / - | 40.2 / - | CTC | Char | [Maas et al.](http://deeplearning.stanford.edu/lexfree/lexfree.pdf) | NAACL2015 <br> (2015/) | 3L RNNLM |
| 21.7 / - | 40.4 / - | CTC | Char | [Krishna et al.] | ICASSP2018 <br> (2018/) | 1-D CNN <br> + char 7-gram |
| 23.1 / - | 40.8 / - | Attention MTL | Char | [Toshiniwal et al.](https://arxiv.org/abs/1704.01631) | IS2017 <br> (2017/8) | Char <br> + Phone <br> + HHM States |
| 24.7 / - | 37.1 / - | Iterated CTC | Char | [Zweig et al.](https://arxiv.org/abs/1609.05935) | ICASSP2017 <br> (2017/4) | no LM |
| 25.8 / - | 46.0 / - | Attention | Word | [Lu et al.](http://homepages.inf.ed.ac.uk/llu/pdf/llu_icassp16.pdf) | ICASSP 2016 <br> (2016/4) | 3-gram |
| 25.9 / - | 38.8 / - | CTC | Char | [Zweig et al.](https://arxiv.org/abs/1609.05935) | ICASSP2017 <br> (2017/4) | no LM |
| 26.3 / - | 46.5 / - | Attention | Word | [Lu et al.](http://homepages.inf.ed.ac.uk/llu/pdf/llu_icassp16.pdf) | ICASSP 2016 <br> (2016/4) | no LM |
| 27.3 / - | 48.2 / - | Attention | Char | [Lu et al.](http://homepages.inf.ed.ac.uk/llu/pdf/llu_icassp16.pdf) | ICASSP 2016 <br> (2016/4) | no LM |
| 27.8 / - | 43.8 / - | CTC | Char | [Maas et al.](http://deeplearning.stanford.edu/lexfree/lexfree.pdf) | NAACL2015 <br> (2015/) | 7-gram |
| 27.9 / - | 48.6 / - | CTC | Char | [Krishna et al.] | ICASSP2018 <br> (2018/) | 1-D CNN <br> + no LM |
| 38.0 / - | 56.1 / - | CTC | Char | [Maas et al.](http://deeplearning.stanford.edu/lexfree/lexfree.pdf) | NAACL2015 <br> (2015/) | no LM |
| 38.8 / - | 59.9 / - | Attention | Word | [Lu et al.](http://www.isca-speech.org/archive/interspeech_2015/i15_3249.html) | IS2015 <br> (2015/9) | no LM |
<!-- | - | - | - | - | model | output | Paper | Published | Notes | -->


#### 2000h (+ Fisher)
| WER/CER <br> (SWB) | WER/CER <br> (CHE) | Model | Output | Paper | Published | Notes |
| :----------------- | :----------------- | :---- | :----- | :---- | :-------- | :---: |
| 9.6 / - | 16.0 / - | CTC | Phone | [Audhkhasi et al.](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/0546.PDF) | IS2017 (2017/8) | BigLM |
| 10.2 / - | 17.7 / - | CTC | Char | [Zweig et al.](https://arxiv.org/abs/1609.05935) | ICASSP2017 <br> (2017/4) | Word RNNLM |
| 11.3 / - | 18.7 / - | CTC | Char | [Zweig et al.](https://arxiv.org/abs/1609.05935) | ICASSP2017 <br> (2017/4) | Word n-gram |
| 12.5 / - | 18.0 / - | CTC | Word | [Audhkhasi et al.](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/0546.PDF) | IS2017 (2017/8) | GloVe Init. <br> + BigLM |
| 13.0 / - | 18.8 / - | CTC | Word | [Audhkhasi et al.](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/0546.PDF) | IS2017 (2017/8) | GloVe Init. |
| 13.8 / - | 21.8 / - | CTC | Char | [Zweig et al.](https://arxiv.org/abs/1609.05935) | ICASSP2017 <br> (2017/4) | Char n-gram |
| 17.2 / - | 26.4 / - | CTC | Char | [Zweig et al.](https://arxiv.org/abs/1609.05935) | ICASSP2017 <br> (2017/4) | no LM |
<!-- | - | - | - | - | model | output | Paper | Published | Notes | -->
