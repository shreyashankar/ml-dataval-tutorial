# Data Validation Techniques for Machine Learning

## Installation

You must be using Python 3.10 or later, and you must have `wget` and `bazelisk` installed. You can install `wget` and `bazelisk` with `brew`.

You can install the required packages for this module with:

```bash
pip install -r requirements.txt
```

Then, download the data with:

```bash
bash download.sh
```

The data may take a while to download, since it is 7.0 GB.

## TODOs

- [x] Scaffold: continuous training pipeline
- [x] Scaffold: synthetic corruptions that cause MSE to increase/performance drop
- [x] Schema validation with TFX
- [x] Inter-batch data validation: distance measures
- [x] GATE
- [x] Instrument with logging and alerts via wandb
- [ ] Move notebooks to colab