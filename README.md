## Project Website

[Autonomous Green Hydrogen Power Plant Controller](https://jaimins2002-netizen.github.io/)

## Project Website


# Autonomous Green Hydrogen Power Plant Controller — Milestone 3

Milestone 3 contains testing, analysis, and UI phases for the autonomous green hydrogen power plant controller. It builds on the Milestone 2 fuzzy-controller implementation and documents validation scenarios, output analysis, and a control interface.

## Organized Folder Structure

| Folder | Contents |
|---|---|
| `python/` | Python exports grouped by phase: testing, analysis, and UI. |
| `ipynb/` | Jupyter notebooks grouped by the same phases. |
| `resources/` | Phase-specific READMEs, dependency files, CSV results, plots, and UI screenshots. |

### Phase 4 — Testing

The testing phase exercises the controller across multiple input combinations and includes executed and validated notebooks, Python exports, test results, and output plots.

### Phase 5 — Analysis

The analysis phase examines how controller output changes with plant parameters and includes analysis notebooks, Python exports, result CSV files, and visualizations.

### Phase 6 — UI

The UI phase exposes the controller inputs through a live interface and includes executed and validated notebooks, Python exports, and screenshots for nominal operation and high-pressure protection.

## Central Executed Notebook Structure

Fresh executed notebooks are grouped in one phase-wise directory:

- `ipynb/executed/Phase_4_Testing/phase_4_testing_executed.ipynb`
- `ipynb/executed/Phase_5_Analysis/phase_5_analysis_executed.ipynb`
- `ipynb/executed/Phase_6_UI/phase_6_ui_executed.ipynb`

These files are the completed outputs from executing the source notebooks in the testing, analysis, and UI phases.

## Usage

Install the dependencies for the phase you want to run. The original phase-specific requirements files are preserved under `resources/Phase_*/requirements.txt`.

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r resources/Phase_4_Testing/requirements.txt
```

Open a source notebook from the corresponding `ipynb/Phase_*/` directory, or review the completed output from the centralized `ipynb/executed/Phase_*/` directories.

## Safety Disclaimer

This repository contains an educational simulation. It is **not** a certified process-safety system and must not be used to control real hydrogen-production equipment without qualified engineering validation, independent hardware safeguards, regulatory review, and professional oversight.

## Authors

Krupa Ashishkumar Rajput; Jaimin Sanghani; Harsh Shingala; Makwana Shlock.

## License

No license has been specified for this milestone.
