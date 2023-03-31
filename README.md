# Text-Summarizer

PyTorch and Transformer :- <br> <br>
Transformer Pipeline :-
We used the T5Tokenizer Transformer in PyTorch. For its training, we need input
sequences and its corresponding target sequences, which was already provided in the
given dataset (Supervised Learning). It then encodes the input sequence and feeds the
encoded hidden states via cross-attention layers to the decoder and auto-regressively
generates the decoder output. The decoded outputs are then stored in a .tsv file.

<br>

Transformer Pipeline :- <br>
We used the T5Tokenizer Transformer in PyTorch. For its training, we need input
sequences and its corresponding target sequences, which was already provided in the
given dataset (Supervised Learning). It then encodes the input sequence and feeds the
encoded hidden states via cross-attention layers to the decoder and auto-regressively
generates the decoder output. The decoded outputs are then stored in a .tsv file.
PRECESION SCORE: 0.961
RECALL SCORE: 0.125
The pipeline() is the most powerful object encapsulating all other pipelines. The
Pipeline is made of:- tokenizer to map text inputs to tokens and summarizer model.
PRECESION SCORE: 0.9696969696969697
RECALL SCORE: 0.125

<br>

NLTK

<br>
First step involves data clean-up in which special characters, stop words
and punctuation are removed.
Then word tokens and sentence tokens are created using Natural
Language Tool Kit library.
Word frequency for each word is evaluated, followed by weighted
frequency for each sentence.
Finally, the summary is created choosing 30% of top weighted
sentences.
PRECESION SCORE=0.6666666666666666
RECALL SCORE:=0.35555555555555557

<br>

CREDITS: 
<br>
Sainik Khaddar <br>
Saptarshi Pani <br>
Arindam Saha <br>

