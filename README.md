<div align='center'>
<h1>💫SSR-Zero: Simple Self-Rewarding Reinforcement Learning for Machine Translation</h1>

[![Paper](https://img.shields.io/badge/paper-5f16a8?style=for-the-badge&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2505.16637)
<a href="https://huggingface.co/collections/wjyccs/ssr-zero-6830189a8d2fd6fc7ce6fba6" target="_blank"><img alt="Hugging Face"
    src="https://img.shields.io/badge/HuggingFace-fcd022?style=for-the-badge&logo=huggingface&logoColor=000&labelColor"/></a>
</div>


## Overview
We introduce a Simple Self-Rewarding (💫**SSR**) Reinforcement Learning (RL) approach for machine translation (MT). Using SSR training, our models **SSR-Zero-7B** and **SSR-X-Zero-7B** show state-of-the-art performance among open-source models under 72B parameters in English-to-Chinese and Chinese-to-English translation tasks. This is based on evaluations using WMT23, WMT24, and Flores200 benchmarks using automatic evaluation metics XCOMET-XXL and COMETKIWI-XXL.

<div align='center'>
<img src="img/ssr-overview.png" width = "80%" />
</div>

💫SSR is a highly effective training approach that **doesn't need external supervision from human reference data or pre-trained reward models**. It relies solely on the training model's own judgment to improve itself. For more details, please [check our paper on arXiv](https://arxiv.org/abs/2505.16637).

👷Note that this repository is still under construction, and more content will be added soon.

## Releases 📰
[2025-05-23] We've released our models [SSR-Zero-7B](https://huggingface.co/wjyccs/SSR-Zero-7B) and [SSR-X-Zero-7B](https://huggingface.co/wjyccs/SSR-X-Zero-7B) on Hugging Face!