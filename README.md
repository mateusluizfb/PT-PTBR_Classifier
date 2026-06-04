## PT-PTBR_Classifier fine tunings

This is a PT-PTBR_Classifier based on a pre-existing model: https://huggingface.co/bastao/PeroVaz_PT-BR_Classifier

The refenrece model above is a fine-tuning of the [bert-tiny](https://huggingface.co/prajjwal1/bert-tiny) model, using an [extensive dataset](https://huggingface.co/datasets/bastao/VeraCruz_PT-BR).

This repository's classifier aims to perform the same fine-tuning with the same dataset, but using different models:

- BERTimbau Base: https://huggingface.co/tubyneto/bertimbau

Parameters:

- Environment: Google Colab
- Runtime: Python 3 - T4 GPU - Latest version
- Python version: 3.12.13 (main, Mar  4 2026, 09:23:07) [GCC 11.4.0]
