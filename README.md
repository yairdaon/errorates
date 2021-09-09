#Code and Tex files for "An Accurate Model for SARS-CoV-2 Pooled
 RT-PCR Test Errors"

All code can be found in the iPython notebook file comment.ipynb. It
runs out-of-the-box, assuming some common packages are installed
(numpy, scipy, pandas and matplotlib). Code is written for python 3+
and was not tested for python 2 (although it will probably work,
modulo some minor modifications).

The **first cell** generates Figure 2 from the paper. One can explore
various (reasonable) values for the false-positive rate and see
results are qualitatively similar.


The **second cell** performs Fisher's exact test with the data from
table 1. The code prints out the odds ratio value, as well as p-values
for the two-sided and one-sided greater alternative hypotheses.

The **third cell** contains code that should be ignored.
