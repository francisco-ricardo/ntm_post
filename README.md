# Machine Translation: Brief Overview

This repository contains the LaTeX source code for the post titled **Machine Translation: Brief Overview**, authored by **Francisco Ricardo Taborda Aguiar**. The post explores the evolution of machine translation, from early statistical models to the dominance of neural machine translation (NMT) techniques, such as sequence-to-sequence models and the Transformer architecture.

## Summary

The post provides a brief history and technical discussion on the key approaches in machine translation (MT), including:

- **Statistical Machine Translation (SMT)**: Early systems using statistical methods to extract translations from bilingual corpora.
- **Neural Machine Translation (NMT)**: A breakthrough using deep neural networks, specifically Recurrent Neural Networks (RNN) and the Transformer model, to handle translations with greater accuracy and flexibility.
- **Sequence-to-Sequence (Seq2Seq)**: This technique, utilizing RNNs, encodes and decodes sentences for translation.
- **The Transformer Architecture**: The state-of-the-art model for machine translation, employing self-attention mechanisms instead of recurrency or convolution.

## LaTeX Compilation

To compile the LaTeX source and generate the PDF, follow these steps:

- Navigate to the `latex` directory:

```bash
cd latex
```

- Use the provided `Makefile` to build the document:

```bash
make doc=article build
```

After running the command, the compiled PDF will be available in the output folder.

## References

The post cites various studies from the machine translation literature, including key works by Brown (1993), Vaswani (2017), and Sutskever (2014), highlighting the progress and advancements in MT techniques over the decades.
