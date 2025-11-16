# P2_ML_Lectures
Notebooks for the lectures by Pablo Tejerina and Pedro Tarancon for the ML part of the course "Mathematical and Statistical techniques" of the Master in Astrophysics, Particle Physics and Cosmology of University of Barcelona.


## How to create a python virtual environnt using conda

conda create -n myenv python=3.10
conda activate myenv

conda install pip  #If there is no pip
pip install -r requirements.txt

pip list # Verify installed packages


## How to create a Python environment sithout conda:
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
pip list # Verify installed packages
