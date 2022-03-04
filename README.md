# lyrics-style-transfer
lyrics style transfer final project for MIT NLP
https://github.com/ChenweWu/lyrics-style-transfer/blob/main/6_864_Project_Draft_Style_Transfer.pdf
Up here is our full final paper!

# ABSTRACT 

While interest in text style transfer has grown
in recent years, little work has addressed its potential applications to music. In this paper, we
investigate an intriguing question: what would
a lyric from a Taylor Swift song look like if
it were written by Drake? And what would
a Drake verse look like if it were penned by
Taylor Swift? This problem is challenging, as
both artist have distinct styles and there is no
set of parallel corpora to translate between the
two. Our work uses unsupervised text style
transfer to address this problem and translates
each artist’s lyrics into the other’s style. We
consider a variety of approaches from recent
literature that combine a sequence-to-sequence
autoencoder (with or without attention) with
either a classifier or discriminator. We evaluate
these models on fluency, content preservation,
and style, and find that a simple model that uses
a non-attention autoencoder and an adversarial
discriminator achieves the best results


# Architecture

![image](https://user-images.githubusercontent.com/36363910/156785691-91f6cc98-fa40-4bfc-89d8-1011f3f8ca8b.png)


# Results

![image](https://user-images.githubusercontent.com/36363910/156785777-d8b27d18-0447-4398-9bc3-8dbf915fa8a1.png)


# Qualitative Evaluation

![image](https://user-images.githubusercontent.com/36363910/156785829-2f8e9e85-68a6-42c8-a2e3-c572caf49cc5.png)
