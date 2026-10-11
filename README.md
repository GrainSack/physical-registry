# World Models Need a Physical Registry

**Learning Internal Predictive States for Physically Plausible World Models**

Shinseong Kim<sup>1,2</sup>, Jaeseok Jeong<sup>1</sup>, Jianlong Fu<sup>2</sup>, Youngjung Uh<sup>1</sup>&#9993;  
<sup>1</sup>Yonsei University · <sup>2</sup>Microsoft Research Asia · &#9993; Corresponding author

<!-- TEMPORARY LINKS: replace the arXiv URL with https://arxiv.org/abs/<ID> and the Hugging Face URL with the model repo once released. -->
[![arXiv](https://img.shields.io/badge/arXiv-coming%20soon-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/)
[![Project page](https://img.shields.io/badge/Project-page-34d399?logo=googlechrome&logoColor=white)](https://grainsack.github.io/physical-registry/)
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-weights%20coming%20soon-ffd21e)](https://huggingface.co/GrainSack)

> **Code release soon.** This repository will host the official implementation. Model weights will be released on Hugging Face.

## Overview

Physical Registry adds dedicated, forecast-initialized registry slots inside a video DiT. The slots co-evolve with video tokens, receive future-representation supervision, and stay readable, so predicted dynamics become an explicit state of the generator. The Physical Registry Selector (PRS) uses these readouts to pick a candidate future before full denoising.

## Release plan

- [ ] Paper on arXiv
- [ ] Training and inference code
- [ ] Model weights on Hugging Face

## Citation

```bibtex
@article{kim2026physicalregistry,
  title   = {World Models Need a Physical Registry: Learning Internal
             Predictive States for Physically Plausible World Models},
  author  = {Kim, Shinseong and Jeong, Jaeseok and Fu, Jianlong and Uh, Youngjung},
  journal = {arXiv preprint},
  year    = {2026}
}
```
