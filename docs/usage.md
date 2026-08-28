# Usage

The README covers the basics. This page collects the
longer examples and the notes that did not fit up front.

## Basic

```bash
python train.py --epochs 5 --synthetic
# metrics land in runs/metrics.csv
```

## Notes

- Cosine LR schedule with warmup
- Synthetic dataset mode: no download needed to smoke-test
