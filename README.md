# gradlab-lab

Tiny CNN experiments on synthetic image data

Small but I use it weekly.

## Features

- Single file model definition, easy to hack
- Synthetic dataset mode: no download needed to smoke-test
- Gradient clipping and clean metrics logging
- Cosine LR schedule with warmup
- Metrics logged to CSV for plotting

## Install

```bash
pip install -r requirements.txt
```

## How to use

```bash
python train.py --epochs 5 --synthetic
# metrics land in runs/metrics.csv
```

## Project structure

```text
├── .github/
│   └── pull_request_template.md
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── tests/
│   └── test_smoke.py
├── .gitignore
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── Makefile
├── model.py
├── requirements.txt
└── train.py
```

## Development

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
python -m pytest -q
```

## License

MIT - see [LICENSE](LICENSE).
