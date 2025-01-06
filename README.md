# ITMol
##### A Multimodal Foundation Model for Molecular Property Prediction via Image-Text Pre-training
  - [Overview](#overview)
  - [Introduction](#Introduction)
  - [Dataset](#description-of-data-files)
  - [Usage](#Usage)
  - [Citation](#citation)
## Overview

![ITMol Architecture](assets/overview.jpg)

The overview of the proposed ITMol model. (a) The data construction phase results in a dataset of 500k molecular image-text pairs.
(b) The pre-training phase aligns text and image modalities. (c) The fine-tuning phase predicts molecular properties.

##Introduction

In this work, we present a molecular image-text foundation model, named ITMol, pretrained on 500k molecular image-text pairs. ITMol effectively designs three self-supervised learning strategies on molecular image-text pairs and adopts cross-attention mechanism to capture molecular representation.