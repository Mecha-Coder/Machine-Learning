1) Cd into the project folder

2) Create custom environment inside this folder
```bash
conda create -p ./env python
```


3) Activate the conda environment
```bash
conda activate ./env
```

4) Install dependencies - jupyter, matplotlib
```bash
conda install jupyter numpy pandas matplotlib
```

To save the depencency, use:
pip freeze

Faster
```bash
conda create --prefix . / env pandas numpy matplotlib scikit-learn jupyter
```

To deactivate
```bash
conda deactivate
```