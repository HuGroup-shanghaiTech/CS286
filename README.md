# CS286

## Backgroung

In the realm of surface reaction studies, quantum chemistry calculations, notably density functional theory (DFT), have revolutionized our approach since the 1990s. Serving as a cornerstone in catalysis research, DFT can give molecular-level insights that are often hard to obtain by experimental means. However, the scalability of DFT calculations has reached a plateau, as the simulations of larger reaction systems (exceeding 300 atoms) or extend our time scale to the nanosecond range, the computational demands escalate exponentially. 

Recently, machine learning interatomic potential (MLIP) has emerged as a promising way to break the limitation. Utilizing the ab intio calculations results, MLIP effectively 'learning' the dynamics of atomic interactions. By applying latest ML models such as CNN, GNN, and transformers, these models can simulate atomic forces and energy changes as atoms move. This way avoids the expensive ab intio calculation while giving acceptable results. Very recently, Transformer has emerged as a powerful ML approach for a wide range of applications, such as image recognition, natural language processing and computer vision. In this project, we are going to explore the possibility of improving current MLIP models, tailing them for catalytic reactions and thereby increase the overall accuracy of the model predictions.

## Goals

Goal:
In this project, students are expected to implement the Transformer or similar neural networks for machine learning interatomic potentials. The training data from DFT calculations will be given. Specific objectives are given as follows:

1.	Learning how the atomic data is translated for ML model training.
2.	Understanding mainstream MLIP models.
3.	Evaluating the Transformer performance and tring to improve the current MLIP models.    


## MLIP methods:
[DeepMD]: https://docs.deepmodeling.com/projects/deepmd/en/master/index.html
[Nequip]: https://github.com/mir-group/nequip
[Equiformer]: https://github.com/atomicarchitects/equiformer

## References

[1] Kang, P.-L.; Shang, C.; Liu, Z.-P. Large-Scale Atomic Simulation via Machine Learning Potentials Constructed by Global Potential Energy Surface Exploration. Acc. Chem. Res. 2020, 53 (10), 2119–2129.
[2] Batzner, S.; Musaelian, A.; Sun, L.; Geiger, M.; Mailoa, J. P.; Kornbluth, M.; Molinari, N.; Smidt, T. E.; Kozinsky, B. E(3)-Equivariant Graph Neural Networks for Data-Efficient and Accurate Interatomic Potentials. Nat Commun 2022, 13 (1), 2453.
[3] Zhang, Y.; Xia, J.; Jiang, B. Physically Motivated Recursively Embedded Atom Neural Networks: Incorporating Local Completeness and Nonlocality. Phys. Rev. Lett. 2021, 127 (15), 156002.


