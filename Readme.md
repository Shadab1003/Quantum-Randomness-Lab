# Quantum Randomness Laboratory

A mini project demonstrating **Quantum Random Number Generation (QRNG)** using IBM Qiskit.

## Overview

This project uses quantum superposition and measurement to generate truly random bits, contrasting with classical pseudo-random number generators.

### Features
- Generate quantum random numbers
- Visualize results with histogram
- Perform statistical analysis
- Compare classical vs quantum randomness

## Project Structure

```
Quantum-Randomness-Lab/
├── venv/                    # Python virtual environment
├── qrng.py                  # Basic QRNG script
├── histogram.py             # Generates histogram visualization
├── statistics.py            # Statistical analysis
├── comparison.py            # Classical vs Quantum comparison
└── README.md                # This file
```

## Setup Instructions

### 1. Create Virtual Environment
```bash
python -m venv venv
venv\Scripts\activate    # Windows
```

### 2. Install Dependencies
```bash
pip install qiskit qiskit-aer matplotlib numpy scipy
```

## How to Run

Make sure `(venv)` is active in the terminal.

```bash
python qrng.py
python histogram.py
python statistics.py
python comparison.py
```

## Expected Output

**qrng.py** example:
```
Quantum Random Numbers
{'0': 503, '1': 497}
```

The histogram shows a near 50/50 distribution thanks to quantum superposition.

*(Full README content is available in the file)*
```

---

Would you like me to:
- Add any extra sections (e.g., screenshots, explanation of quantum code, or troubleshooting)?
- Generate a `requirements.txt` file?
- Improve the code in any of the `.py` files?

Just tell me!