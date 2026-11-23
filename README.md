# P2_ML_Lectures
Notebooks for the lectures by Pablo Tejerina and Pedro Tarancon for the ML part of the course "Mathematical and Statistical techniques" of the Master in Astrophysics, Particle Physics and Cosmology of University of Barcelona.

## Structure
- `1_VdP_and_PINNs/`: Van der Pol oscillator with PINNs (exercise and solved), the harmonic oscillator example, and pretrained models in `results/`.
- `2_Dimensionality_reduction/`: dimensionality reduction with neural networks. `Dimensionality_reduction_NN.ipynb` is the notebook used in class; the exercise and solved versions are also here (`requirements_dim_red.txt` is an older environment, replaced by the root `requirements.txt`).
- `3_Inversion_of_V/`: inverse problem of reconstructing the potential V with PINNs (free fall and several choices of V).
- `Neural_Network_lectures.pdf`: lecture notes.
- `requirements.txt`: Python packages for all the notebooks.

## Setup
Create a conda environment and install the requirements:
```
conda create -n ML_lectures python=3.11
conda activate ML_lectures
conda install pip -y
pip install -r requirements.txt
```
Then open the notebooks with `jupyter lab`, or select the `ML_lectures` kernel in VS Code.
