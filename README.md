## To run RL model with super mario-bros on Mac M1

```
# Conda env with python 3.8
conda create -n mario python=3.8
conda activate mario

% python --version
Python 3.8.19

# jupyter
conda install conda-forge::jupyter

# torch for Apple M1 with GPU
!pip3 install --pre torch torchvision torchaudio --index-url https://download.pytorch.org/whl/nightly/cpu

# Mario emualtor and RL models
pip install nes-py
pip install gym-super-mario-bros==7.3.0
pip install pip==22.0.4 setuptools==59.8.0 wheel==0.37.1
pip install gym==0.21
pip install "stable-baselines3[extra]==1.6.0"

```

