# is-longer-always-the-best
A python codebase to test the Alternate hypothesis "The longest protein sequence may not necessarily contain maximum information"

##details

**Null Hypothesis** - If presented with homologs of the same protein, in terms of information content it is best to choose the longest one

(MY logic for this Null hypo, The longest one would have all the features of the protein)

In response to the above logic of mine, The challenge as written by Prof. V. Nanjundiah (VN):

>Why not carry out a computer exercise?

>Take an arbitrary length of DNA, say 3x100 bases in the (putative) coding
>sequence. Call this sequence X0. Now create a number of variants from it.

>.. Let bases 40 to 74 (chosen arbitrarily) be duplicated, once tandemly
>and once not tandemly.
>.. Let bases 40-74 and 121-207 be duplicated, once again in different ways.

>You can think of several such variations. Call them X1, X2, etc. in
>increasing order of the number of stretches that are duplicated.

>Now compare X0 with X1, X2, and so on and see what the goodness of fit is.
>What I am suggesting is the most elementary situation. The complications
>increase if you also take into account transpositions from another
>sequence, inversions, etc.

>If you compare real aminoacid sequences the complications grow because you
>will need to distinguish between conservative substitutions from those
>that change the aminoacid.*

**Alternate Hypothesis** -- The longest protein sequence may not necessarily contain maximum information

##Background to the problem

Dynamical Patterning Modules (DPM) are proteins from Unicellular organisms that are responsible for multicellular behaviour.
Now the already published work on DPM, is mostly in context of higher multicellular eukaryotes.
But I am trying to test the DPM hypothesis using Dictyostelium which had branched from multicellular eukaryotes more than 600 million years ago. 

The first step of my work is to look for proteins that are have been mentioned as example of DPM in published literature, in the Dictyostelium genome. Some example are Wnt signalling pathway, Hedgehog pathway, Notch pathway, Fibroblast Growth Factor (FGF), etc.
Now if I search for these proteins in Swissprot (experimental evidence, manual curation) database, I get multiple (several hundreds) hits constituting multiple eukaryotes. 
Even if I narrow down the search by selecting only Human orthologs, still I get > 10 hits.

Now for a Blast search I require only one representative sequence, consequently I suggested the above mentioned Null hypothesis and in reply VN asked me to carry out a computational experiment to test the alternate hypothesis.


