# ACTCD19: Andrew's C/C++ Token Count Dataset 2019

See paper [http://www.tomazos.com/actcd16.pdf] for background.  Difference between ACTCD19 and ACTCD16 are that in ACTCD19 Debian Sid (Unstable) was used as the base distribution, which should be about 4 years fresher than ACTCD16.

Released Artifacts:

- [ACTCD19-2TOK.txt.gz](https://github.com/tomazos/actcd19/raw/master/ACTCD19-2TOK.txt.gz) (23MB)

A text file containing lines of the form:

    OCCURENCES TOKEN1 TOKEN2

The unique token spellings in the corpus were identified, counted and ranked.  We define a *common token* as a token that has a rank of 65536 or greater.

We then identified, counted and ranked unique consecutive pairs of common tokens.  (This is known as a 2-gram language model.)

OCCURENCES is the number of occurences of each unique token pair.
TOKEN1 is the first token of the pair
TOKEN2 is the second token of the pair.


