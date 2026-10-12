# DSCI 552 — Homework 3

Coursework on time-series feature extraction using the [UCI AReM activity recognition dataset](https://archive.ics.uci.edu/dataset/366/activity+recognition+system+based+on+multisensor+data+fusion+arem).

## Repository structure

```text
DSCI552_HW3/
├── data/
│   └── AReM/
│       ├── bending1/    # dataset1.csv ... dataset7.csv
│       ├── bending2/    # dataset1.csv ... dataset6.csv
│       ├── cycling/     # dataset1.csv ... dataset15.csv
│       ├── lying/       # dataset1.csv ... dataset15.csv
│       ├── sitting/     # dataset1.csv ... dataset15.csv
│       ├── standing/    # dataset1.csv ... dataset15.csv
│       └── walking/     # dataset1.csv ... dataset15.csv
├── notebook/
│   └── <completed-HW3-notebook>.ipynb  # add your actual notebook here
├── requirements.txt
└── README.md
```

All 88 original CSV files are present in the seven activity folders.

## Notebook setup

Put your **completed** Homework 3 notebook into `notebook/` before committing. The original notebook supplied to ChatGPT was a template, not your completed notebook, so this ZIP intentionally contains no `.ipynb`.

When running the notebook from `notebook/`, refer to the data using a relative path:

```python
from pathlib import Path
data_dir = Path("../data/AReM")
```

Ensure the notebook does not still point to `AReM/` relative to the old location. Restart the kernel, run all cells, verify the results, and save the notebook before committing.

## Install requirements

```bash
python -m pip install -r requirements.txt
```

## Data and submission note

The repository is intended to be **public**, not a GitHub Classroom repository. Review your notebook for personal identifiers, credentials, and API tokens before pushing anything to a public repository.
