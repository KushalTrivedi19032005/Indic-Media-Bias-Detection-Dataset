# Indic-Media-Bias-Detection-Dataset
In this paper, we introduce the first exhaustive annotated dataset consisting of 300 unique articles from two leading Indian news agencies publishing in Hindi. We focus on Hindi, the most spoken and an official language of India.  
# Indic Media Bias Detection Dataset

## Overview

The **Indic Media Bias Detection Dataset** is an annotated dataset designed to support research on media bias detection in low-resource Indian languages. The dataset consists of **300 unique news articles** collected from **two leading Indian news agencies** that publish content in **Hindi**.

This dataset is intended to facilitate the development and evaluation of computational models for identifying political bias in news media, with a particular focus on Indic languages.

## Motivation

Media bias detection has received significant attention in English-language contexts, but similar resources for Indic languages remain limited. Hindi, being the most widely spoken language in India and one of its official languages, represents a critical yet underexplored domain. This dataset aims to bridge that gap by providing a carefully annotated benchmark for bias analysis in Hindi news articles.

## Dataset Description

The repository contains the following files:

* **`Indic Media Bias Detection.csv`**
  The main dataset file containing Hindi news articles along with their bias annotations.

* **`Bias Rules.txt`**
  A detailed description of the annotation guidelines and bias identification rules followed by the annotators.

## Annotation Scheme

Each article in the dataset is annotated by multiple annotators for the presence and degree of bias. The annotations include:

* **Binary Bias Label**: Bias / No Bias
* **9 Bias Labels**: Binary labels (0 or 1) indicating the presence or absence of each bias type—selection, framing, linguistic, emotional, clickbait, omission, factual, ideological, and stance bias.


### Inter-Annotator Agreement

To ensure annotation reliability, inter-annotator agreement was measured using **Cohen’s Kappa**:

* **0.81** for simple bias/no-bias classification
* **0.60** for the top-three average bias score

These values indicate **moderate to strong agreement** among annotators.

## Language and Domain

* **Language**: Hindi
* **Domain**: Indian news media
* **Article Sources**: Two major Indian news agencies

## Potential Use Cases

* Media bias detection and classification
* Low-resource NLP research for Indic languages
* Political discourse analysis
* Bias-aware news recommendation systems
* Cross-lingual and multilingual bias studies

## Ethical Considerations

This dataset is intended for research purposes only. The annotations reflect human judgments and may contain subjective interpretations of bias. Users are encouraged to apply appropriate caution when drawing conclusions or deploying models trained on this data in real-world applications.

## Citation

If you use this dataset in your research, please cite the corresponding paper:

```
https://doi.org/10.5281/zenodo.18253270
```

## License

Please refer to the repository for licensing information. If not explicitly specified, contact the authors before using the dataset for commercial purposes.

## Contact

For questions, feedback, or collaboration inquiries, please reach out via the GitHub repository.
