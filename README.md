A modal transfer enhanced deep learning for structural dynamic response with sparse spatial data 
* Requirements: Python: 3.8.20; CUDA: 11.2; TensorFlow-GPU : 2.7.0; DeepXDE: 1.3.1.
* Requirements: torch 2.5.1+cu124; python 3.12.3 (GCN)
Make sure your NVIDIA GPU driver is compatible with CUDA 11.2 to enable GPU acceleration with TensorFlow.
Create a Conda Environment
conda create -n myenv python=3.8.20
conda activate myenv
conda install cudatoolkit=11.2
pip install tensorflow-gpu==2.7.0
pip install deepxde==1.3.1
------------------------------------------
conda create -n myenv python=3.12.3
conda activate myenv
pip install torch==2.5.1+cu12.4 https://download.pytorch.org/whl/torch_stable.html

Jupyter Notebook as the development environment

In the code repository, we provide four sets of files: 
-	Section 3: Includes the implementation of the DL, GCN, and MT-DL models, along with modal and vibration data of a variable-stiffness beam. 
-	Section 4.1: Simulation of continuous beams under moving load. 
-	Section 4.2: A plate with complex boundary conditions subjected to impact loading. 
-	Section 4.3: Vortex-induced vibration of a flexible riser.

Author's Email: 2111378@tongji.edu.cn

