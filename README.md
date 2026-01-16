<img width="1375" height="765" alt="image" src="https://github.com/user-attachments/assets/3a74c84f-acf5-4f72-9a19-4a9aa9f561b1" /><img width="1375" height="765" alt="image" src="https://github.com/user-attachments/assets/dd2e0a11-af1f-404a-b77b-f4f1209ddfd3" /># ADNeuroNet: A Neuroevolution-Based Neural Network Algorithm for the Diagnosis of Neurodegenerative Diseases

This repository provides a research-oriented implementation of **ADNeuroNet**, 
a neuroevolution-based deep learning framework for the diagnosis of 
neurodegenerative diseases (CN / MCI / AD), as published in:

**Afreen Khan, Swaleha Zubair, Irfan Ali**  
*Neural Computing and Applications*, 2025  
📄 [Paper PDF](https://link.springer.com/content/pdf/10.1007/s00521-025-11021-y.pdf)

## Overview

ADNeuroNet is a population-based neuroevolution framework that automatically 
optimizes neural network architectures for robust clinical prediction.

Key characteristics:
- Neuroevolution instead of gradient-only optimization
- Non-invasive clinical and neuropsychological features
- Evaluation across three ADNI cohorts (ADNI-1, ADNI-2, ADNI-3)
- Focus on generalization and clinical applicability

## Methodology

<p align="center">
  <img src="figures/adneuronet_pipeline.png" alt="ADNeuroNet Pipeline" width="700">
</p>

<p align="center">
  <em>Figure 1: ADNeuroNet framework illustrating the neuroevolution-based
  optimization pipeline for neurodegenerative disease diagnosis.</em><br>
  <em>(Source: Khan et al., <i>Neural Computing and Applications</i>, 2025)</em>
</p>

The ADNeuroNet pipeline follows six stages:

1. Data preprocessing (clean, integrate, transform, reduce)
2. Neural network construction
3. Neuroevolutionary optimization
4. Model training and cross-validation
5. Performance evaluation
6. Dimensionality reduction and interpretability

The architecture corresponds to **Figure 1** in the paper.


## Results Summary

Across three ADNI datasets, ADNeuroNet achieved:

- Maximum test accuracy: **93.42%**
- Stable performance across k=5 and k=10 cross-validation
- Robust generalization across cohorts

For full experimental details, refer to Tables 5–7 in the paper.

## Citation

If you use this code or framework in your research, please cite:

```bibtex
@article{khan2025adneuronet,
  title={ADNeuroNet: A neuroevolution-based neural network algorithm for the diagnosis of neurodegenerative diseases},
  author={Khan, Afreen and Zubair, Swaleha and Ali, Irfan},
  journal={Neural Computing and Applications},
  year={2025},
  publisher={Springer},
  doi={10.1007/s00521-025-11021-y}
}
```bibtex

Please cite both the paper and this repository when using ADNeuroNet in academic work.

## License

This project is released under the **Apache License 2.0**.

You are free to use, modify, and distribute this code for research and commercial
purposes, provided that proper attribution is given.

See the [LICENSE](LICENSE) file for details.




