This repository contains analysis code and data used to generate the quantitative results reported in the manuscript.

Files:
- analysis_results.py
    Computes all numerical results reported in the main text, including
    transition latency statistics, scaling exponents, and critical slowing
    down indicators. The script produces numerical output only (no figures).

- sweep_results.csv
    Results of parameter sweep simulations across adaptation rate (eps)
    and noise intensity (sigma), including transition latency.

- time_series.csv
    Time-series data used to evaluate variance and lag-1 autocorrelation
    of the state variable prior to transition.

- recovery_times.csv
    Recovery time measurements used to assess divergence near the
    structural transition.

Usage:
Run the analysis script with:
    python analysis_results.py

All results in the manuscript can be reproduced directly from the
printed numerical output of this script.
