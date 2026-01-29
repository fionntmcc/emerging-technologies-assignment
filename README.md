# Emerging Technologies Assignment

# TODO - Fill in with project-specific info.

This repository contains solutions to the Computational Theory module assessment problems. The main deliverable is `problems.ipynb`, a Jupyter notebook implementing various cryptographic functions and algorithms defined in the [Secure Hash Standard](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.180-4.pdf), including SHA-1 and SHA-256 primitives, message padding, and hash computation.

The notebook is structured with clear explanations, code implementations, and tests for each problem. It demonstrates understanding of hashing algorithms, bitwise operations, and computational theory concepts.

## Target Audience

This submission is intended for an informed computing professional, such as a prospective employer. It assumes familiarity with programming concepts and cryptographic basics but provides detailed explanations and references of technologies and algorithms used.

## Setup Instructions

1. **Clone the repository**:
   ```
   git clone https://github.com/fionntmcc/Computational-Theory.git
   cd computational-theory
   ```

2. **Install dependencies**:
   - Ensure Python 3.8+ is installed.
   - Install required packages:
     ```
     pip install numpy jupyter
     ```
   - `hashlib` is part of Python's standard library, so no additional installation is needed.

3. **Install Jupyter** (if not already installed):
   ```
   pip install jupyter
   ```

4. **Data files**: All necessary data files are included in the repository:
   - `data/primes.0000`: List of prime numbers for testing.
   - `data/sha1_constants.txt`: Expected SHA constants for validation.
   - `data/rockyou.txt`: Common passwords list for Problem 5.

## Usage

1. **Open the notebook**:
   ```
   jupyter notebook problems.ipynb
   ```
   Or use JupyterLab:
   ```
   jupyter lab problems.ipynb
   ```

2. **Run the cells**: Execute cells in order. The notebook includes:
   - Helper functions (bitwise operations)
   - SHA functions (Parity, Ch, Maj, Sigma0, Sigma1, sigma0, sigma1)
   - Prime generation and cube root calculations for SHA constants
   - Message padding (block_parse)
   - Full SHA-256 implementation
   - Password cracking from hashes

3. **Tests**: Run the test cells to verify implementations. All tests should pass if the code is correct.

## Repository Structure

- `problems.ipynb`: Main notebook with solutions and explanations.
- `data/`: Test data files (`primes.0000`, `sha1_constants.txt`, `rockyou.txt`).
- `README.md`: This file.

## Notes

- The notebook uses only standard libraries plus numpy for array operations.
- All code is reproducible; clone and run as described.
- For questions, refer to the notebook's explanations or the assessment guidelines in `assessment.md`.

This repository is submitted as part of the Winter 25/26 Computational Theory assessment.