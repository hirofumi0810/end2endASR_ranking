### Switchboard
#### 300h (LDC97S62)
| WER/CER <br> (SWB) | WER/CER <br> (CHE) | Model | Output | LM | Paper | Published | Notes |
| :----------------- | :----------------- | :---- | :----- | :- | :---- | :-------- | :---: |
| 13.9 / - | 24.7 / - | CTC | Phone | BigLM | [Audhkhasi et al.](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/0546.PDF) | Interspeech2017 | - |
| 14.0 / - | 25.3 / - | CTC | Char | Lexicon <br> + word n-gram | [Zweig et al.](https://arxiv.org/abs/1609.05935) | ICASSP2017 | - |
| 14.5 / - | - | CTC | Phone | - | [Miao et al.](https://www.cs.cmu.edu/~ymiao/pub/icassp2016_ctc.pdf) | ICASSP 2016 | VTLN-filterbank |
| 15.1 / - | 26.3 / - | CTC | Char | Lexicon <br> + word RNNLM | [Zweig et al.](https://arxiv.org/abs/1609.05935) | ICASSP2017 | - |
| 19.8 / - | 32.1 / - | CTC | Char | Char n-gram | [Zweig et al.](https://arxiv.org/abs/1609.05935) | ICASSP2017 | - |
| 20.0 / - | 31.8 / - | CTC | Char | - | DeepSpeech | Published | - |
| 20.8 / - | 30.4 / - | CTC | Word | - | [Audhkhasi et al.](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/0546.PDF) | Interspeech2017 | GloVe Init. |
| 21.3 / - | 40.0 / - | CTC | Char | char 9-gram | [Krishna et al.] | ICASSP2018 | 1-D CNN |
| 21.4 / - | 40.2 / - | CTC | Char | RNNLM-3L | [Maas et al.](http://deeplearning.stanford.edu/lexfree/lexfree.pdf) | NAACL2015 | - |
| 21.7 / - | 40.4 / - | CTC | Char | char 7-gram | [Krishna et al.] | ICASSP2018 | 1-D CNN |
| 23.1 / - | 40.8 / - | Att MTL | Char | - | [Toshiniwal et al.](https://arxiv.org/abs/1704.01631) | Interspeech2017 | Char <br> + Phone <br> + HHM States |
| 24.7 / - | 37.1 / - | Iterated CTC | Char | - | [Zweig et al.](https://arxiv.org/abs/1609.05935) | ICASSP2017 | - |
| 25.8 / - | 46.0 / - | Att | Word | 3-gram | [Lu et al.](http://homepages.inf.ed.ac.uk/llu/pdf/llu_icassp16.pdf) | ICASSP 2016 | - |
| 25.9 / - | 38.8 / - | CTC | Char | - | [Zweig et al.](https://arxiv.org/abs/1609.05935) | ICASSP2017 | - |
| 26.3 / - | 46.5 / - | Att | Word | - | [Lu et al.](http://homepages.inf.ed.ac.uk/llu/pdf/llu_icassp16.pdf) | ICASSP 2016 | - |
| 27.3 / - | 48.2 / - | Att | Char | - | [Lu et al.](http://homepages.inf.ed.ac.uk/llu/pdf/llu_icassp16.pdf) | ICASSP 2016 | - |
| 27.8 / - | 43.8 / - | CTC | Char | 7-gram | [Maas et al.](http://deeplearning.stanford.edu/lexfree/lexfree.pdf) | NAACL2015 | - |
| 27.9 / - | 48.6 / - | CTC | Char | - | [Krishna et al.] | ICASSP2018 | 1-D CNN |
| 38.0 / - | 56.1 / - | CTC | Char | - | [Maas et al.](http://deeplearning.stanford.edu/lexfree/lexfree.pdf) | NAACL2015 | - |
| 38.8 / - | 59.9 / - | Att | Word | - | [Lu et al.](http://www.isca-speech.org/archive/interspeech_2015/i15_3249.html) | Interspeech2015 | - |
<!-- | - | - | - | - | model | output | Paper | LM | Published | Notes | -->


#### 2000h (+ Fisher)
| WER/CER <br> (SWB) | WER/CER <br> (CHE) | Model | Output | LM | Paper | Published | Notes |
| :----------------- | :----------------- | :---- | :----- | :- | ---- | :-------- | :---: |
| 8.1 / - | 17.5 / - | RNN <br> transducer | Char | 4-gram | [Battenberg et al.](https://arxiv.org/abs/1707.07413) | ASRU2017 | - |
| 8.5 / - | 16.4 / - | RNN <br> transducer | Char | - | [Battenberg et al.](https://arxiv.org/abs/1707.07413) | ASRU2017 | - |
| 8.6 / - | 17.8 / - | Att | Char | 4-gram | [Battenberg et al.](https://arxiv.org/abs/1707.07413) | ASRU2017 | - |
| 8.6 / - | 17.8 / - | Att | Char | - | [Battenberg et al.](https://arxiv.org/abs/1707.07413) | ASRU2017 | - |
| 9.0 / - | 17.7 / - | CTC | Char | ?? | GramCTC | - | - |
| 9.6 / - | 16.0 / - | CTC | Phone | BigLM | [Audhkhasi et al.](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/0546.PDF) | Interspeech2017 | - |
| 10.2 / - | 17.7 / - | CTC | Char | Word RNNLM | [Zweig et al.](https://arxiv.org/abs/1609.05935) | ICASSP2017 | - |
| 11.3 / - | 18.7 / - | CTC | Char | Word n-gram | [Zweig et al.](https://arxiv.org/abs/1609.05935) | ICASSP2017 | - |
| 12.5 / - | 18.0 / - | CTC | Word | BigLM | [Audhkhasi et al.](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/0546.PDF) | Interspeech2017 | GloVe Init. |
| 13.0 / - | 18.8 / - | CTC | Word | - | [Audhkhasi et al.](http://www.isca-speech.org/archive/Interspeech_2017/pdfs/0546.PDF) | Interspeech2017 | GloVe Init. |
| 13.8 / - | 21.8 / - | CTC | Char | Char n-gram | [Zweig et al.](https://arxiv.org/abs/1609.05935) | ICASSP2017 | - |
| 17.2 / - | 26.4 / - | CTC | Char | - | [Zweig et al.](https://arxiv.org/abs/1609.05935) | ICASSP2017 | - |
<!-- | - | - | - | - | model | output | Paper | LM | Published | Notes | -->
