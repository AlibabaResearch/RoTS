# Recovering Policy-Induced Errors: Benchmarking and Trajectory Synthesis for Robust GUI Agents

**[ICML 2026 Spotlight]** Official code for the paper:  
**"Recovering Policy-Induced Errors: Benchmarking and Trajectory Synthesis for Robust GUI Agents"**

> Tianpeng Bu\*, Xin Liu\*, Qihua Chen\*, Hao Jiang, Shurui Li, Hongtao Duan, Lu Jiang, Lulu Hu, Bin Yang, Minying Zhang (\* equal contribution)  
> Alibaba Cloud Computing

---

## Overview

GUI agents frequently fail to recover from their own policy-induced errors, limiting real-world deployment. This paper addresses the problem at both the evaluation and data levels:

- **GUI-RobustEval** — a benchmark of 1,216 executable test cases that systematically measure error recovery capabilities across 11 error types and 4 error depths.
- **RoTS** — a scalable, tree-based online trajectory synthesis framework that produces 800k high-quality training samples covering diverse policy-induced error modes and long-horizon recovery strategies.
- **RoTS-7B / RoTS-32B** — models fine-tuned on the RoTS dataset, achieving state-of-the-art performance among open-weight models on OSWorld.

For full details and results, please refer to the [paper](paper/rots_paper.pdf).

---

## Releases

**[2026/05/27 Update]** We are actively cleaning up our code and data for open-source release. Stay tuned — we look forward to sharing everything with the community soon!

| Artifact | Status |
|---|---|
| **GUI-RobustEval** | 🔜 In preparation |
| **RoTS Dataset** | 🔜 In preparation |
| **Sampling Pipeline** | 🔜 In preparation |
| **Post-processing Pipeline** | 🔜  In preparation |

---

## Citation

```bibtex
@inproceedings{bu2026rots,
  title     = {Recovering Policy-Induced Errors: Benchmarking and Trajectory Synthesis for Robust {GUI} Agents},
  author    = {Bu, Tianpeng and Liu, Xin and Chen, Qihua and Jiang, Hao and Li, Shurui and Duan, Hongtao and Jiang, Lu and Hu, Lulu and Yang, Bin and Zhang, Minying},
  booktitle = {Proceedings of the 43rd International Conference on Machine Learning},
  series    = {Proceedings of Machine Learning Research},
  volume    = {306},
  year      = {2026},
  publisher = {PMLR},
}
```

---

## License

This project is licensed under the Apache License 2.0. See [LICENSE](LICENSE) for details.
