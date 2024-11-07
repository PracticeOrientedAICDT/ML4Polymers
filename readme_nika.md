1. Create venv in CONDA

conda create --name polyNC1 python=3.10 
conda activate polyNC1

2. conda install pytorch::pytorch torchvision torchaudio -c pytorch
(3. conda install -c conda-forge rust) --not neccessary with 3.10
2.1 conda install -c conda-forge sentencepiece


3. pip install -r requirements.txt
4. #install kernel:# 
python -m pip install ipykernel
python -m ipykernel install --user --name polyNC1 --display-name "Python (polyNC1)"
5. pip install tensorboard
6. pip install nltk





NOTE::: TRIED PYTHON 3.13 but missing packages, so went to 3.10 - as above
1. Used the following to create v env and activate:
python3 -m venv PolyNC
source polyNC/bin/activate 

---
it should have python 3.13

