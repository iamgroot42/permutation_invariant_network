# Permutation Invariant Network

PyTorch implementation for [Permutation Invariant Network](https://dl.acm.org/doi/pdf/10.1145/3243734.3243834). This implementation has been tested to recreate experimental results from the original paper (more information [here](https://arxiv.org/pdf/2106.03699.pdf))


# Setup

You can either via pip:

```bash
pip install perminvnetwork
```

Or clone and install directly, if you wish to make changes:

```bash
git clone https://github.com/iamgroot42/perminvnetwork.git
pip install -e perminvnetwork
```

## Features

- Contains example code for extracting features from Pytorch model (current support for linear layers) as well as training/testing
- Supports batched data training
