# Journal article summarizer

a course project

## Datasets

<!-- The model is fine-tuned on several datasets. -->

<!-- The data to train the classification model is taken from the [arXiv Dataset](https://www.kaggle.com/datasets/Cornell-University/arxiv), which can be accessed through [arxiv_dataset](https://huggingface.co/datasets/arxiv_dataset) on Hugging Face. -->

<!-- The [arxiv-abstracts-2021](https://huggingface.co/datasets/gfissore/arxiv-abstracts-2021) dataset is used to train the classification model.
This model is used to predict the subject category of a provided article. -->

<!-- NOTE: this dataset should be downloaded manually and unzipped to reveal the JSON file which is placed in the `data/` directory within this git directory. -->

Abstracts of journal articles are taken as a representation for summarization of articles from the [arxiv-summarization](https://huggingface.co/datasets/ccdv/arxiv-summarization) dataset on Hugging Face. This contains articles and abstracts taken from [arXiv](https://arxiv.org/).

## Models

The basis of the model is the [BERT](https://huggingface.co/docs/transformers/model_doc/bert) model.

Tuned models are in the `results/` directory. Note that [git lfs](https://git-lfs.com/) may be required to clone this repository.

### Model performance

Model performance under the current training parameters is rather poor. Full training could be done on a different device or via a cloud provider to provide better results. Nonetheless, the training procedure could likely be similar to that utilized here.

## Bibliography

<!-- 1. C. B. Clement, M. Bierbaum, K. P. O’Keeffe, and A. A. Alemi, “On the Use of ArXiv as a Dataset.” arXiv, 2019. doi: 10.48550/ARXIV.1905.00075. -->
1. A. Cohan et al., “A Discourse-Aware Attention Model for Abstractive Summarization of Long Documents,” Proceedings of the 2018 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies, Volume 2 (Short Papers). Association for Computational Linguistics, 2018. doi: 10.18653/v1/n18-2097.
2. Jacob Devlin, Ming-Wei Chang, Kenton Lee, and Kristina Toutanova. 2019. BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding. In Proceedings of the 2019 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies, Volume 1 (Long and Short Papers), pages 4171–4186, Minneapolis, Minnesota. Association for Computational Linguistics. doi: 10.18653/v1/N19-1423.
