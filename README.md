# PercepMamba
Configuration for PercepMamba:

conda create -n mambayolo -y python=3.10
conda activate mambayolo
pip install torch==2.1.0 torchvision==0.16.0 torchaudio==2.1.0 --index-url https://download.pytorch.org/whl/cu118
pip install seaborn thop timm einops
