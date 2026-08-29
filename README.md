## Project Website

[Autonomous Green Hydrogen Power Plant Controller](https://jaimins2002-netizen.github.io/Autonomous_Green_Hydrogen_Controller_Web.ghithub.io/milestone3/)


# Autonomous Green Hydrogen Power Plant Controller — Milestone 3

Milestone 3 contains testing, analysis, and UI phases for the autonomous green hydrogen power plant controller. It builds on the Milestone 2 fuzzy-controller implementation and documents validation scenarios, output analysis, and a control interface.

# Autonomous Green Hydrogen Power Plant Controller – Milestone 3

> **Testing • Analysis • Interactive User Interface**

## 📖 Overview

Milestone 3 extends the core fuzzy controller developed in Milestone 2 by validating, analyzing, and demonstrating controller behavior through three independent phases:

- ✅ Phase 4 – Testing
- 📊 Phase 5 – Analysis
- 🖥️ Phase 6 – Interactive User Interface

This repository evaluates controller performance under different operating conditions, studies controller trends, and provides an interactive interface for educational demonstrations.

---

# Repository Objectives

- Validate the fuzzy controller.
- Test multiple operating conditions.
- Analyze controller behavior.
- Visualize controller response.
- Demonstrate high-pressure safety behavior.
- Generate reproducible results.

---

# Repository Structure

```
Milestone-3/
│
├── ipynb/
│   ├── Phase_4_Testing/
│   ├── Phase_5_Analysis/
│   ├── Phase_6_UI/
│   │
│   └── executed/
│       ├── Phase_4_Testing/
│       ├── Phase_5_Analysis/
│       └── Phase_6_UI/
│
├── resources/
│   ├── Phase_4_Testing/
│   ├── Phase_5_Analysis/
│   └── Phase_6_UI/
│
├── outputs/
│
├── screenshots/
│
├── requirements.txt
│
└── README.md
```

---

# Project Workflow

```
Milestone 1
      │
      ▼
Milestone 2
      │
      ▼
Milestone 3
      │
      ├── Phase 4 Testing
      ├── Phase 5 Analysis
      └── Phase 6 User Interface
```

---

# Controller Inputs

| Parameter | Unit |
|-----------|------|
| Renewable Power | kW |
| Water Flow Rate | L/min |
| Stack Temperature | °C |
| Hydrogen Tank Pressure | bar |

---

# Controller Output

| Parameter | Unit |
|-----------|------|
| Hydrogen Production Rate | kg/h |

---

# Phase 4 – Controller Testing

## Purpose

This phase validates the controller using multiple combinations of plant inputs.

### Activities

- Load controller
- Execute test cases
- Calculate output
- Verify controller response
- Store results
- Export CSV

### Outputs

- Executed Notebook
- Test Results
- CSV Files

---

# Phase 5 – Controller Analysis

## Purpose

Analyze how controller output changes when plant parameters vary.

### Analysis Includes

- Renewable Power variation
- Water Flow variation
- Temperature variation
- Tank Pressure variation
- Output trend observation

### Generated Outputs

- Graphs
- Trend Analysis
- Performance Results

---

# Phase 6 – Interactive User Interface

## Purpose

Provide an interactive controller demonstration.

### Features

- Adjustable input sliders
- Live controller output
- Rule firing visualization
- Membership display
- Controller response

### Demonstration Scenarios

- Normal Operation
- High Tank Pressure Protection

---

# Installation

## Clone Repository

```bash
git clone https://github.com/<username>/autonomous-green-hydrogen-power-plant-controller-milestone-3.git

cd autonomous-green-hydrogen-power-plant-controller-milestone-3
```

---

# Create Virtual Environment

```bash
python -m venv .venv
```

---

# Activate Environment

### Linux / macOS

```bash
source .venv/bin/activate
```

### Windows

```bash
.venv\Scripts\activate
```

---

# Install Requirements

```bash
pip install -r requirements.txt
```

---

# Run Phase 4

```bash
jupyter notebook ipynb/Phase_4_Testing
```

---

# Run Phase 5

```bash
jupyter notebook ipynb/Phase_5_Analysis
```

---

# Run Phase 6

```bash
jupyter notebook ipynb/Phase_6_UI
```

---

# Expected Outputs

- Testing Results
- CSV Reports
- Analysis Graphs
- Interactive Demonstration
- Screenshots
- Executed Notebooks

---

# Safety Statement

This project is intended solely for educational and research purposes. It is **not** a certified industrial control system and must not be connected to real hydrogen-production equipment.

---

# Repository Features

- Testing Framework
- Controller Validation
- Behaviour Analysis
- Interactive Demonstration
- Result Export
- Notebook Execution
- Documentation
- Reproducible Workflow

---

# Technologies Used

- Python
- Jupyter Notebook
- scikit-fuzzy
- NumPy
- Pandas
- Matplotlib
- ipywidgets

---

# Repository Progress

- ✅ Phase 4 – Testing
- ✅ Phase 5 – Analysis
- ✅ Phase 6 – Interactive UI

---

# Authors

- Krupa Ashishkumar Rajput
- Jaimin Sanghani
- Harsh Shingala
- Makwana Shlock

---

# License

Educational and Research Use Only.
