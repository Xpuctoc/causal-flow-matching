## Causal Flow Matching

In order to reproduce the experiments, you will need the following:

1. Install python>=3.9.0

2. Install requirements
```commandline
pip install -r requirements.txt
```

3. Run all experiments:
```commandline
python3 run_experiments.py
```

If you want to additionally run experiments on VACA and CAREFL:

1. Install vaca dependencies
```commandline
pip install -r vaca/vaca_requirements.txt
```

2. Run experiments, using VACA:
```commandline
python3 run_experiments.py use_vaca
```