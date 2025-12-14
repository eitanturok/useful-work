# ⛏️ Mining Crypto While Training AI

Turn your matrix multiplications into cryptocurrency at zero extra cost.

## What Is This?

When training neural networks, your GPU spends most of its time doing matrix multiplication (matmul). Traditionally, cryptocurrency mining secures blockchain networks through computationally expensive but fundamentally useless hash checking. This project implements a breakthrough that changes everything.

Based on the paper [*Proofs of Useful Work from Arbitrary Matrix Multiplication*](https://arxiv.org/abs/2504.09971), this repository demonstrates how **the same matmul operations used in AI training can simultaneously mine cryptocurrency**, securing blockchain networks with genuinely useful computation.

## Why This Matters

- **Zero waste**: Your AI training workload now serves dual purposes
- **Free mining**: No additional computational cost—mine crypto while training models
- **Useful work**: Replace meaningless hash calculations with productive matrix operations
- **Network security**: Blockchain consensus built on real computational work

## Implementation

The core algorithm is implemented in `main.ipynb`. The notebook demonstrates how to:
- Integrate proof-of-useful-work into existing matmul operations
- Generate valid blockchain proofs during AI model training
- Verify the computational work for network consensus

## Getting Started
```bash
# Clone the repository
git clone https://github.com/eitanturok/useful-work.git

# Install dependencies
uv pip install -r requirements.txt

# Open the notebook
jupyter notebook main.ipynb
```

## How It Works

Instead of solving arbitrary cryptographic puzzles, the network validates transactions by verifying that miners performed legitimate matrix multiplications—the exact same operations needed for AI training. This creates an economic incentive structure where useful computation secures the network.

<div align="center">
    <img src="assets/paper.png" alt="Proofs of Useful Work Paper" width="500">
</div>

## Citation
```bibtex
@article{proofsofusefulwork2025,
  title={Proofs of Useful Work from Arbitrary Matrix Multiplication},
  journal={arXiv preprint arXiv:2504.09971},
  year={2025}
}
```

## Contributing

This is an experimental implementation of cutting-edge research. I will not be accepting contributions as this is a standalone implementation.

## License
