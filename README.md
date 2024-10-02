# Efficient Data Stream Anomaly Detection

## Project Description
This project implements a real-time anomaly detection algorithm using Isolation Forest. It simulates a data stream with seasonal patterns, noise, and anomalies, and detects unusual points using a sliding window approach.

## Requirements
- Python 3.x
- Libraries: `numpy`, `matplotlib`, `scikit-learn`

## How to Run
1. Install the required libraries using the following command:
   ```
   pip install -r requirements.txt
   ```
2. Run the project file in Jupyter Notebook or any Python IDE.

## Project Structure
```
├── project.ipynb         # Main Jupyter Notebook file
├── README.md             # Project documentation
├── requirements.txt      # Dependencies file
```

## Results
The detected anomalies are visualized in the graph, where normal data points are shown in blue, and anomalies are marked in red.

## Algorithm Used
Isolation Forest is a well-known anomaly detection algorithm that isolates observations by randomly selecting a feature and then randomly selecting a split value between the maximum and minimum values of the selected feature. The fewer splits required to isolate a point, the more likely it is an anomaly.

## License
This project is licensed under the MIT License.
