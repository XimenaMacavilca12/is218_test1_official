# IS 218 Test 1 Project

**Student:** Ximena Macavilca
**Purpose:** Build and test the calculator package for the IS 218 assessment.

## Setup and tests

Create and activate the local environment, install the committed dependencies, and
run pytest:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
python -m pytest
```

The `.venv` directory is local and ignored because it contains machine-specific
installed packages. `requirements.txt` is committed so another developer or CI can
recreate the same dependency versions.

## Issue tracking

- [Issue 1: Set up a reproducible Python project](https://github.com/XimenaMacavilca12/is218_test1_official/issues/1)