# Fitness Tracker

An exploratory data analysis project for daily fitness and workout data. The
Jupyter notebook uses pandas to inspect and prepare the data, with Plotly
available for interactive visualizations.

## Dataset

The notebook expects a file named `fitness_data.csv` in the project root. The
dataset is synthetic; the `date` values were generated using ChatGPT's Data
Mockstar. It does not represent real people or real health measurements.

### Data dictionary

| Column | Description |
| --- | --- |
| `date` | Date the data was recorded. The dataset covers a 185-day period. |
| `steps` | Total daily step count. |
| `weight` | Body weight in kilograms. |
| `resting_heart_rate` | Heart rate in beats per minute while at complete rest. |
| `sleep_hours` | Total daily sleep duration in hours. |
| `active_minutes` | Total time spent in physical activity, in minutes. |
| `total_calories_burned` | Total daily energy expenditure, including resting and activity-based calories. |
| `fat_burn_minutes` | Minutes spent at 50–69% of maximum heart rate. |
| `cardio_minutes` | Minutes spent at 70–84% of maximum heart rate. |
| `peak_minutes` | Minutes spent at 85% or more of maximum heart rate. |
| `workout_type` | Category of exercise performed. |
| `workout_duration` | Workout session length, in minutes. |
| `workout_calories` | Calories expended during the workout. |
| `workout_avg_hr` | Mean heart rate during the workout, in beats per minute. |
| `workout_max_hr` | Highest heart rate during the workout, in beats per minute. |

## Getting started

1. Clone or download this repository.
2. Put `fitness_data.csv` in the project root, next to `tracker.ipynb`.
3. Install Python and the notebook dependencies:

   ```bash
   python -m pip install pandas plotly jupyter
   ```

4. Start Jupyter and open the notebook:

   ```bash
   jupyter notebook tracker.ipynb
   ```

## Project status

The notebook is a work in progress. It currently begins with exploratory data
checks; further analysis and visualizations can be added as the project
develops.

## Disclaimer

This project and its synthetic data are for learning and demonstration only.
They are not medical advice and should not be used to make health decisions.