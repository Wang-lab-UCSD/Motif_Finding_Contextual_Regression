# Motif Finding Contextual Regression
Sequence Data Download:

<code>!wget -r -np -nH --reject "index.html*" --cut-dirs 6 https://krishna.gs.washington.edu/content/members/vagar/Xpresso/data/datasets/pM10Kb_1KTest/</code>

Runnning the model
if you tensorflow version is 1.x simply run the code
if you tensorflow version is 2.x, add the following code after importanting libraries

<code># Maintain tf 1.x behaviour under tf 2.x
import tensorflow.compat.v1 as tf
tf.disable_v2_behavior()

JASPAR Motif Data:

JASPAR motif data is included in all_JASPAR_fimo.csv, the motifs are generated using fimo the sames way as in the Xpresso paper (https://github.com/vagarwal87/Xpresso/blob/master/Fig4_S4/runme.sh)

Model Generation:

Run the data division block. Then run the section in the model generating block multiple times to generate all the model.

Linear Model Fitting:

Run the part after generate linear model in order.
