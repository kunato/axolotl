# Fine-tune Typhoon

## Install
```
conda create -n axolotl python=3.10 -c conda-forge
pip install torch==2.1.2 torchvision==0.16.2 torchaudio==2.1.2 --index-url https://download.pytorch.org/whl/cu121
pip install -e .
pip install flash-attn
```

## Run
```
python scripts/finetune.py examples/typhoon/typhoon-qlora.yml
```

## Credit & Thank you
```
https://github.com/OpenAccess-AI-Collective/axolotl
```