# quantum-playground
A Jupyter notebook environment to play around with quantum circuits/calculations using Qiskit.

Before running install packages:
```bash
pip install qiskit
pip install pylatexenc
```

# Highlights
## Experiments

### Bell inequality - 3 bases

[An example](https://github.com/DeDuckProject/quantum-playground/blob/master/experiments/EPR-experiment-3-bases.ipynb) of a simple Bell inequality violation using only 3 bases, based on one of Preskill's lectures.

### 3-qubit repetition code
A simple quantum error correction (QEC) scheme. This [experiment](https://github.com/DeDuckProject/quantum-playground/blob/master/experiments/basic-error-correction.ipynb) shows a comparison between different implementations of the scheme, and between not applying it at all.

### Teleportation
A simple [demo](https://github.com/DeDuckProject/quantum-playground/blob/master/experiments/teleportation.ipynb) of quantum teleporation, where all players (ie. Alice and Bob) are in fact simulated on the same machine.