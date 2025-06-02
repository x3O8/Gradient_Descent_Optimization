# OptimizerHub: Advanced Gradient Descent Optimizers

Welcome to **OptimizerHub**, a repository dedicated to advanced gradient descent optimization algorithms for deep learning. This project features **AdamSafe**, a groundbreaking optimizer that enhances the classic Adam optimizer by introducing a **Gradient Stability Factor (GSF)** for improved stability and convergence in noisy gradient scenarios.

## 🌟 Key Features

- **AdamSafe Optimizer**: Extends Adam with a GSF to dynamically scale learning rates, achieving a test accuracy of **95.71% ± 0.58%** on the Cats and Dogs dataset, rivaling Adam's **95.95% ± 0.34%** with superior stability.
- **Comprehensive Comparisons**: Includes implementations and evaluations of popular optimizers like **Adam**, **RMSProp**, and **Lion**.
- **Lightweight Design**: AdamSafe requires minimal memory overhead, making it ideal for resource-constrained environments like Google Colab.
- **Easy Integration**: Designed for seamless integration into **PyTorch** workflows.

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.8+
- PyTorch 1.9+
- NumPy
- A compatible deep learning dataset (e.g., Cats and Dogs dataset from Kaggle)

### Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/OptimizerHub.git
cd OptimizerHub
