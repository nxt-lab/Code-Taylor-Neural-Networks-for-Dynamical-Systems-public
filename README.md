# Physics-Constrained Taylor Neural Networks for Learning and Control of Dynamical Systems

## Abstract of the Paper

This repository accompanies our research on **Monotonic Taylor Neural Networks (MTNN)** for data-driven system identification and control of dynamical systems. It includes the implementation of multiple variants of Taylor Neural Networks (TNN), both with and without physics-based monotonic constraints, applied to HVAC and TCLab systems. The models are structured to enable comparison between standard learning, monotonic-constrained learning, and learning with inductive bias. 

All scripts are provided as Jupyter notebooks for easy experimentation and reproducibility.

---
## Install Required Packages
Install all required Python libraries from the `requirements.txt` file:

```sh
pip install -r requirements.txt
```

## Model Overview Table

| Model Category                        | Run File                        |
|--------------------------------------|---------------------------------|
| **MTNN & TNN (1st & 2nd Order)**     | [`HVAC-MTNN.ipynb`](HVAC-MTNN.ipynb)               |
| **MTNN with Learning Bias (1st & 2nd)** | [`HVAC-MTNN_soft.ipynb`](HVAC-MTNN_soft.ipynb)     |
| **Baseline Model for HVAC**          | [`HVAC-Baseline.ipynb`](HVAC-Baseline.ipynb)       |
| **Min-Max Model for HVAC**           | [`HVAC-Min_max.ipynb`](HVAC-Min_max.ipynb)         |
| **MTNN with Learning Bias for TCLab**| [`TC-MTTN_soft.ipynb`](TC-MTTN_soft.ipynb)         |

---

## Citation

If you use this code or method in your work, please cite the following:

```bibtex
@inproceedings{nguyen2025PhysicsConstrainedTaylorNeural,
  title = {Physics-Constrained {Taylor} Neural Networks for Learning and Control of Dynamical Systems},
  booktitle = {2025 {{American Control Conference}} ({{ACC}})},
  author = {Nguyen, Nam and Rangel, Juan and Nghiem, Truong X.},
  year = {2025}
}
```
