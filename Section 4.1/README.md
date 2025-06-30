(1) Data Descriptionconda 
This case study involves two key datasets:
* mode shape.txt: Contains modal shape data of the structure (The continuous beams under moving load)
* Displacement.txt: Contains vibration response data of the continuous beams under moving load
Make sure both files are placed in the data/ directory, or adjust the data loading paths accordingly in your code.
(2) Environment Setup
* Requirements: Python: 3.8.20; CUDA: 11.2; TensorFlow-GPU : 2.7.0; DeepXDE: 1.3.1.
Make sure your NVIDIA GPU driver is compatible with CUDA 11.2 to enable GPU acceleration with TensorFlow.
(3) Create a Conda Environment
conda create -n myenv python=3.8.20
conda activate myenv
conda install cudatoolkit=11.2
pip install tensorflow-gpu==2.7.0
pip install deepxde==1.3.1
Jupyter Notebook as the development environment

