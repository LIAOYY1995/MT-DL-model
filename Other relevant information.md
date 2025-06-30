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

Author's Email: 2111378@tongji.edu.cn
