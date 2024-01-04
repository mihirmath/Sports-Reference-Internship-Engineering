# Head-to-Head Records Visualization

This Python script demonstrates a method to visualize head-to-head records between teams using Pandas. The visualization creates a color-coded matrix representing team performance against each other.

## Installation

Ensure Python is installed and then install the required libraries:

```bash
pip install pandas
```

## Usage
JSON Data File: Replace data.json with your JSON file containing head-to-head records.
Execute the Script: Run the provided Python script in your preferred environment (Jupyter Notebook, Python script, etc.).

## How It Works
Data Loading: The script loads head-to-head records from a JSON file into a Pandas DataFrame.
DataFrame Creation: An empty DataFrame is initialized to store the head-to-head records, filled by iterating through each team's data.
Color-Coding Logic: Records are color-coded based on win ratios between teams. The gradient ranges from red (0 wins) to green (all wins).
Visualization: Pandas' styling functionality applies color-coding to DataFrame cells, creating a visual representation of team performance against each other.

## Customization
Data Input: Replace data.json with your dataset following the same structure for the script to visualize head-to-head records.

## Output
The output is a styled table (DataFrame) presenting head-to-head records between different teams, with colors indicating win ratios.

