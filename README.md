# Task Dependent Importance of Small Singular Values During Fine-Tuning

## Abstract

Singular value decomposition (SVD) is vital for model compression, enabling matrix approximation with fewer parameters. In this work, we systematically remove singular values (SVs) from fine-tuned DistilBERT models across GLUE tasks of varying complexity. Our experiments show that small SVs are essential for complex reasoning during early fine-tuning, though their importance diminishes with prolonged training. We localize these performance-critical small SVs primarily to early feed-forward network layers in the transformer. These findings enable optimized compression schemes that preserve essential small SVs in critical regions while permitting aggressive pruning elsewhere.
