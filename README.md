# Classifying Gene Expression Data

Train a simple neural network based classifier on the [Toil TCGA, TARGET and GTEX expression datasets](https://xenabrowser.net/datapages/?host=https://toil.xenahubs.net)

To get started look at ingest.ipynb to wrangle the dataset and train.ipynb for a very simple fully connected neural net tumor/normal classifier. infer.ipynb can be opened in colab and run standalone on uploaded abundance.tsv from Kallisto.

# Alternate Versions

There are several experimental versions in branches:

**master**: Predict tumor/normal and primary site using Kallisto gene expression from TCGA+GTex. Infer notebook is able to run in Colab and as Kallisto is feasible on a laptop this version is nominally intended to allow self service.

**treehouse**: Predict disease using only the Treehouse public compendium

**hugo**: Predict using RSEM transcript expression. This is deprecated by may contain useful snippets

**transcript**: Predict using transcripts all the way through. Never managed to get working well likely becuase feature count is so much larger then N and pruning never managed to work well. YMMV
