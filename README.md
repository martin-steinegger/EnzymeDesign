# EnzymeDesign

Enzyme search using ESM-1b and colabfold database
This colab enables you to find potential proteins that will act similarly as your input enzymes. You will need to provide a fasta file with any numerical value representing your enzymes (i.e. Km, Kcat/Km, toxicity, ...), then the colab will give you a list of proteins similar to the given enzymes, sorted by the numerical value predicted by the regressor.

<br>
<b>What you need to prepare</b>
* A fasta file containing the sequence and numerical value representing the sequence (see the example fasta format below)

