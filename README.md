# Phys763.HW4b-Detuning-ReturningQubits

This repository contains a coursework assignment developed as part of **PHY 763** at the University of Wisconsin–Madison.

The work focuses on the **analysis and physical interpretation of single-qubit calibration and benchmarking experiments** performed on a superconducting qubit platform using **QOLab / Qualibrate nodes**.

The datasets analyzed in this repository include **both course-provided measurements and data personally acquired by the author during in-class experimental sessions**.

---

## Context

This notebook corresponds to **Homework 4b** of PHY 763 and is **not an independent research project**.

The goal of the assignment was to gain hands-on experience with **experimental qubit calibration workflows**, understand how control parameters affect gate performance, and develop physical intuition for sources of error in superconducting qubits, rather than to optimize software performance.

---

## Objectives

The analysis aims to:

- Analyze **single-qubit randomized benchmarking (RB)** data and extract gate performance metrics
- Study the effect of **intentional detuning** on qubit gate fidelity
- Retune control pulses using **Power Rabi experiments** and evaluate performance improvements
- Use **Ramsey experiments** to probe frequency offsets and dephasing behavior
- Connect observed gate errors to underlying physical and experimental limitations

---

## Data Disclaimer

All experimental datasets included or referenced in this repository:

- Include **measurements provided by the PHY 763 instructional staff**
- Include **datasets acquired by the author by running calibration experiments in Qualibrate during class**
- Are used **strictly for educational and instructional purposes**
- Do not represent independent research data collected outside the course framework

The analysis and interpretation of the data were performed independently by the author as part of the coursework.

---

## Learning Outcomes

Through this assignment, I developed experience in:

- Running and analyzing **calibration and benchmarking experiments** on superconducting qubits
- Interpreting **randomized benchmarking results** and gate error metrics
- Understanding the impact of **detuning and pulse miscalibration** on gate fidelity
- Using **Power Rabi and Ramsey experiments** for qubit control optimization
- Working with **real hardware datasets** using Python and Jupyter notebooks within the QOLab framework

---

## Skills Demonstrated 

- Qubit calibration and benchmarking using QOLab / Qualibrate
- Randomized benchmarking analysis and error extraction
- Pulse detuning and retuning via Power Rabi
- Physical interpretation of gate errors and SPAM fidelity
- Python scripting with xarray, scipy, pandas, and matplotlib

---

## Usage

This notebook is intended to be **read and reviewed**, rather than executed independently.

It depends on experimental datasets and calibration infrastructure available through the **QOLab / Qualibrate environment used in PHY 763**, which are not publicly accessible.

For this reason, the `data` directory is intentionally excluded from this repository.

The notebook and accompanying PDF are provided to illustrate the **full analysis workflow, methodology, and physical interpretation** of the experiments.
