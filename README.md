# Mean, Median and Mode

A Python exercise that reads a CSV of people and weights, then calculates the mean, median, and an approximate grouped mode.

## Project structure

- `Mean_median_mode-master/Mean_median_mode-master/mean.py` — calculations and CSV loading.
- `Mean_median_mode-master/Mean_median_mode-master/data.csv` — input data.

## Run

Run from the directory containing `data.csv`:

```bash
python mean.py
```

## Notes

The script expects the weight in the third CSV column and converts it to an integer. Its mode is estimated from fixed 10-unit ranges, so it is not the exact statistical mode. The original data source and units should be verified before interpreting the result.