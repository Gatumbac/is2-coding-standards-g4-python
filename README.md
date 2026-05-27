# loan-eligibility-python

Loan eligibility calculator for a cooperativa de ahorro y crédito. Computes whether a member is eligible for a loan and at what rate, based on income, debt, employment, and savings history.

## Setup

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Run the tests

```bash
pytest
```

## Use it from the CLI

```bash
python -m loan.cli --income 1200 --debt 320 --tenure-months 18 --age 34 --savings-balance 850
```

## Tool for linting selected

flake8           7.3.0
flake8-html      0.4.3

## Figures

### Setup and dependencies

![Installing requirements and committing](docs/figures/Screenshot%20From%202026-05-27%2014-51-28.png)
*Figure 1: Installing dependencies from requirements.txt*

### Test results

![Pytest run - 22 tests passed](docs/figures/Screenshot%20From%202026-05-27%2014-51-46.png)
*Figure 2: Pytest run — 22 tests passed*

![Pytest run after fixes](docs/figures/Screenshot%20From%202026-05-27%2014-53-48.png)
*Figure 3: Pytest run after flake8 fixes — 22 tests still passing*

### Flake8 linting

![Initial flake8 report generation](docs/figures/Screenshot%20From%202026-05-27%2014-53-38.png)
*Figure 4: Generating initial flake8 HTML report (25 violations found)*

![Flake8 initial report - summary](docs/figures/Screenshot%20From%202026-05-27%2014-54-35.png)
*Figure 5: Initial flake8 report — 25 violations in src/loan/eligibility.py*

![Flake8 initial report - details](docs/figures/Screenshot%20From%202026-05-27%2014-54-30.png)
*Figure 6: Violation details — F841, E712, E501*

![Final flake8 report generation and push](docs/figures/Screenshot%20From%202026-05-27%2014-53-57.png)
*Figure 7: Generating final flake8 report and pushing to origin*

![Flake8 final report - all good](docs/figures/Screenshot%20From%202026-05-27%2014-54-40.png)
*Figure 8: Final flake8 report — no errors found*
