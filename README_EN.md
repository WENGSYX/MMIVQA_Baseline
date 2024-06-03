# MMIVQA Baseline 🌟

<p align="center">
    <img alt="GitHub" src="https://img.shields.io/github/license/WENGSYX/MMIVQA_Baseline.svg?color=blue&style=flat-square">
    <img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/WENGSYX/MMIVQA_Baseline">
    <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/WENGSYX/MMIVQA_Baseline">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/WENGSYX/MMIVQA_Baseline">
</p>


<p align="center">
  <img src="./task1/image/mmivqa.png" alt="cmivqa" width="95%" height="65%">
</p>

## Welcome to the MMIVQA Baseline Code Repository!

This repository provides the baseline code for solving the tasks in the MMIVQA challenge, including Track 1, Track 2, and Track 3. Below you'll find an overview of the repository's contents and instructions on how to train and test using the baseline code. Each sub-project includes two main sections: Environment Setup and Quick Start. Ensure you follow the instructions to configure your environment correctly and use the provided sample code for training and testing. Good luck! 😃

## Table of Contents
1. [MMIVQA Overview](#mmivqa-overview)
2. [Track 1: mTAGSV](#track-1-mtagsv)
3. [Track 2/3: mVCR and mTAGVC](#track-2-3-mvcr-and-mtagvc)
4. [Evaluation Code](#evaluation-code)
5. [Issues and Support](#issues-and-support)
6. [Citation](#citation)
7. [WeChat Group](#wechat-group)
8. [Acknowledgements](#acknowledgements)

## MMIVQA Overview

The Multilingual Medical Instructional Video Question Answering (MMIVQA) challenge involves high-quality Chinese and English medical instructional videos with expert annotations. The tasks include:
- Track 1: Multilingual Temporal Answer Grounding in Single Video (mTAGSV)
- Track 2: Multilingual Video Corpus Retrieval (mVCR)
- Track 3: Multilingual Temporal Answer Grounding in Video Corpus (mTAGVC)

The ultimate goal is to develop a system for multilingual Q&A functions using moment-to-moment video clips for medical education.

## Track 1: mTAGSV

This task involves locating the visual answer in a single medical instructional video using a natural language question. We propose a Cross-modal Mutual Knowledge Transfer Span Localization (MutualSL) method to address cross-modal knowledge bias.

For detailed method descriptions and implementation, refer to the [README.md](https://github.com/WENGSYX/CMIVQA_Baseline/tree/main/task1) in the subdirectory.

### Evaluation Code
[EVAL CODE](https://github.com/WENGSYX/CMIVQA_Baseline/tree/main/task1/eval.py)

## Track 2/3: mVCR and mTAGVC

These tasks focus on visual answer localization in large, untrimmed video corpora. We decompose this into:
- Video Corpus Retrieval (VCR)
- Temporal Answer Grounding in Video Corpus (TAGVC)

We propose a Cross-modal Contrastive Global Span (CCGS) method, combining training for video corpus retrieval and visual answer localization.

For detailed method descriptions and implementation, refer to the [README.md](https://github.com/WENGSYX/CMIVQA_Baseline/tree/main/task23) in the subdirectory.

### Evaluation Code
[EVAL CODE](https://github.com/WENGSYX/CMIVQA_Baseline/tree/main/task23/eval.py)

## Issues and Support

If you encounter any issues with environment setup or code execution, feel free to raise an [issue](https://github.com/WENGSYX/CMIVQA_Baseline/issues) or contact:
- Yixuan Weng: [wengsyx@gmail.com](mailto:wengsyx@gmail.com)
- Bin Li: [libincn@hnu.edu.cn](mailto:libincn@hnu.edu.cn)

## Citation

If you use our code in your research, please cite the following papers:

```
@INPROCEEDINGS{10095026,
  author={Weng, Yixuan and Li, Bin},
  booktitle={ICASSP 2023 - 2023 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)}, 
  title={Visual Answer Localization with Cross-Modal Mutual Knowledge Transfer}, 
  year={2023},
  pages={1-5},
  doi={10.1109/ICASSP49357.2023.10095026}}

@INPROCEEDINGS{10096391,
  author={Li, Bin and Weng, Yixuan and Sun, Bin and Li, Shutao},
  booktitle={ICASSP 2023 - 2023 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)}, 
  title={Learning To Locate Visual Answer In Video Corpus Using Question}, 
  year={2023},
  pages={1-5},
  doi={10.1109/ICASSP49357.2023.10096391}}
```

## WeChat Group

Due to the large number of participants, please add a WeChat friend for an invitation to the official group (note "NLPCC 2024").

<p align="center">
  <img src="./task1/image/tjs.jpg" alt="cmivqa" width="45%" height="45%">
</p>
---



We wish you great success in the MMIVQA competition! 🏆🎉

