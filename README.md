# GRAND Modifications

Re-implementation of *GRAND: Graph Neural Diffusion* (Chamberlain et al., ICML 2021) with four proposed modifications: signed-tanh attention (`grand_nls`), a gated softmax/signed-tanh mix (`grand_nls_gated`), per-node and per-feature diffusivity, and structural attention. Evaluated on eight datasets (three homophilic, five heterophilic). Self-contained Jupyter notebook; modern PyTorch + PyTorch Geometric. See `report.pdf` for full writeup.

Run the the python notebook, there are many cells which output results to different experiments
