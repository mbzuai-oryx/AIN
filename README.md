
<img src='images/AIN_logo1.pdf' align="right" width="30%" />

# AIN: The Arabic INclusive Multimodal Model <br> 


[![arXiv](https://img.shields.io/badge/arXiv-2410.18976-b31b1b)](https://arxiv.org/abs/2410.18976)
[![GitHub issues](https://img.shields.io/github/issues/mbzuai-oryx/Camel-Bench)](https://github.com/mbzuai-oryx/Camel-Bench/issues) [![GitHub stars](https://img.shields.io/github/stars/mbzuai-oryx/Camel-Bench)](https://github.com/mbzuai-oryx/Camel-Bench/stargazers) [![GitHub license](https://img.shields.io/github/license/mbzuai-oryx/Camel-Bench)](https://github.com/mbzuai-oryx/Camel-Bench/blob/main/LICENSE) [![Dataset on HuggingFace](https://img.shields.io/badge/HuggingFace-Dataset-orange)](https://huggingface.co/collections/ahmedheakl/camel-bench-670750f3998395452cd3b7b1)

## Overview

AIN, the **Arabic Inclusive Multimodal Model**, bridges the gap in generative AI for Arabic by leveraging Modern Standard Arabic (MSA) data to achieve state-of-the-art performance across diverse tasks and specialized domains. Built on Qwen-2-VL, AIN empowers Arabic speakers with advanced, inclusive AI capabilities, outperforming leading models in key benchmarks.

![CAMEL-Bench Diversity](assets/CAMEL-B.png)

The benchmark includes **eight diverse domains** and **38 sub-domains** to rigorously assess the performance of LMMs in visual reasoning and understanding tasks. It comprises over **29K questions**, curated by native Arabic speakers, ensuring high-quality evaluation.

## Key Features

- **Eight Domains of Evaluation:** Multimodal Understanding and Reasoning, OCR and Document Understanding, Chart and Diagram Understanding, Video Understanding, Cultural-Specific Understanding, Medical Imaging, Agricultural Image Understanding, and Remote Sensing Understanding.
- **Over 29,000 Questions:** Carefully curated by native Arabic speakers to ensure quality and accuracy.
- **Broad Scope:** Evaluates models in domains such as **medical imaging**, **cultural-specific understanding**, and **remote sensing**.
- **Open and Closed Source Evaluation:** We provide a leaderboard featuring results from both closed-source models (e.g., GPT-4o) and open-source LMMs.

## 📢 Latest Updates
- **Jan 2025** 🔥  [ 🤗]


## Leaderboard

[![Leaderboard on HuggingFace](https://img.shields.io/badge/HuggingFace-Leaderboard-yellow)](https://huggingface.co/spaces/ahmedheakl/CAMEL-Bench-leaderboard)

Our leaderboard provides a performance comparison of different models evaluated on CAMEL-Bench. Current top performers include **GPT-4o** with an overall score of **62%** and other notable models such as **Gemini-1.5-Pro**.

![Leaderboard Snapshot](assets/eval-samples-figure.png)

## Installation

To get started with CAMEL-Bench, clone the repository and install the dependencies:

```sh
$ git clone https://github.com/mbzuai-oryx/Camel-Bench.git
$ cd Camel-Bench
$ pip install -r requirements.txt
```

## Getting Started

The benchmark can be easily executed using the provided scripts:

```sh
$ python scripts/eval_qwen.py
```

To evaluate on your model, just modify the `generate_qwen` function in `scripts/eval_qwen.py`. 

## Dataset

Our dataset is hosted on HuggingFace, and can be accessed here: [CAMEL-Bench Dataset 🤗](https://huggingface.co/collections/ahmedheakl/camel-bench-670750f3998395452cd3b7b1).

## Citation

If you use CAMEL-Bench in your research, please consider citing:

```bibtex

```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Join Us!

We welcome contributions to CAMEL-Bench! Just push a pull request or issue to get started.


[![GitHub forks](https://img.shields.io/github/forks/mbzuai-oryx/Camel-Bench?style=social)](https://github.com/mbzuai-oryx/Camel-Bench/network/members)
[![GitHub stars](https://img.shields.io/github/stars/mbzuai-oryx/Camel-Bench?style=social)](https://github.com/mbzuai-oryx/Camel-Bench/stargazers)

## Contact

For questions or suggestions, feel free to reach out to us on [GitHub Discussions](https://github.com/mbzuai-oryx/AIN/discussions).

