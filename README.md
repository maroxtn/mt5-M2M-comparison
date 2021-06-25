# Comparing mT5 and M2M models

In this project, I fine tuned both of mT5 and M2M on a small dataset (10k) of Yoruba - English sentence pairs, and compared the results. Both models were trained on multi-lingual data, and both are being used for translation. They were released during relatively the same, mT5 is a little bit bigger than M2M.

I use both `fairseq` and `simpletransformers` for training and it took around two hours on a P100 GPU.

<h2>TLDR; M2M is much better</h2>
More details, blog post: https://medium.com/@abdessalemboukil/comparing-facebooks-m2m-to-mt5-in-low-resources-translation-english-yoruba-ef56624d2b75

If you find this useful please star the repo.
