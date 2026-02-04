# Emerging Technologies Assignment

This repository contains solutions to the Emerging Technologies module assessment problems. The main deliverable is `problems.ipynb`, a Jupyter notebook exploring quantum algorithms and their advantages over classical computation, with a focus on the Deutsch–Jozsa algorithm and its implementation using Qiskit.

The notebook is structured with clear explanations, code implementations, tests and demonstrations for each problem. It demonstrates understanding of quantum computing concepts including superposition, quantum oracles, quantum circuits, and the quantum advantage through algorithm design.

## Target Audience

This submission is intended for an informed computing professional, such as a prospective employer. It assumes familiarity with programming concepts but may not be familiar with quantum computing. Therefore detailed explanations, references to quantum algorithms and Qiskit are included throughout.

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ianmcloughlin/emerging-technologies.git
   cd emerging-technologies-assignment
   ```

2. **Create and activate a virtual environment**:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```
   (On Windows, use `venv\Scripts\activate`)

3. **Install dependencies**:
   - Ensure Python 3.8+ is installed.
   - Install required packages:
     ```bash
     pip install --upgrade pip
     pip install -r requirements.txt
     ```

4. **Run the notebook**:
   ```bash
   jupyter notebook problems.ipynb
   ```
   Or use JupyterLab:
   ```bash
   jupyter lab problems.ipynb
   ```

## Repository Structure

```
emerging-technologies-assignment/
├── problems.ipynb              # Main notebook with solutions and explanations
├── requirements.txt            # Python package dependencies
├── README.md                   # This file
├── .gitignore                  # Git ignore file
├── data/                       # Test data files
```

## Notes

- The notebook uses Qiskit for quantum circuit implementation along with standard libraries and Jupyter.
- All code is reproducible; clone and run as described above.
- Each problem is clearly documented with explanations of quantum concepts and implementation details.

This repository is submitted as part of the Emerging Technologies Summer 25/26 assessment.