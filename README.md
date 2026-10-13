# Matplotlib Tutorial

Jupyter notebook and data files for learning data visualization with Python's Matplotlib library.

## What you'll learn

The notebook walks through basic plots and real-world examples, including:

- Line and bar charts
- Histograms, pie charts, and box plots
- Plot labels, legends, figure sizing, and saving charts
- Visualizing gas-price trends and FIFA 2018 player data

## Repository contents

- `Matplotlib Tutorial.ipynb` — the hands-on tutorial notebook
- `gas_prices.csv` — gas-price data used in the line-chart examples
- `fifa_data.csv` — FIFA 2018 player data used in distribution and comparison plots

## Run the notebook locally

1. Install Python 3 and create/activate a virtual environment (recommended).
2. Install the notebook dependencies:

   ```bash
   python -m pip install jupyter matplotlib numpy pandas
   ```

3. Clone this repository and move into its directory:

   ```bash
   git clone https://github.com/GeneralSubhra/matplotlib_tutorial.git
   cd matplotlib_tutorial
   ```

4. Start Jupyter:

   ```bash
   jupyter notebook
   ```

5. Open `Matplotlib Tutorial.ipynb` and run the cells in order. Keep the CSV files in the same directory as the notebook so the data-loading cells can find them.

## Notes

Some cells save chart images (for example, `barchart.png` and `histogram.png`) in the working directory. Re-running those cells will regenerate the images.

This is an educational tutorial; use it as a starting point and experiment with the plots and datasets.
