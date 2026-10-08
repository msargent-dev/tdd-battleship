# tdd-battleship

Battleship board game, developed test-first.

## Setup

```sh
python3 -m venv .venv
source .venv/bin/activate
pip install -e ".[dev]"
```

## Workflow

```sh
pytest                      # run tests
pytest --cov=battleship     # with coverage
ruff check .                # lint
```

Code lives in `src/battleship/`, tests in `tests/`.