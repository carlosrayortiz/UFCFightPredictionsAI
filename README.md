# UFCFightPredictionsAI

# UFC Fight Forecaster

This repository contains a machine learning model for predicting the outcomes of UFC fights. The model uses historical fighter data, including physical attributes, fight statistics, and average performance metrics, to predict the winner of a bout.

## Project Overview

This project was developed to explore the application of machine learning in the domain of mixed martial arts (MMA). The goal was to build a model that could accurately predict the outcome of UFC fights based on available fighter data.

## Data Source

The model was trained using the "UFC Dataset 2024" available on Kaggle. This dataset provides comprehensive information on UFC fighters, events, and fight statistics.

*   **Kaggle Dataset Link:** [https://www.kaggle.com/datasets/thasankakandage/ufc-dataset-2024](https://www.kaggle.com/datasets/thasankakandage/ufc-dataset-2024)

## Model Development

The model was developed using the following steps:

1.  Data acquisition and cleaning
2.  Feature engineering
3.  Model selection and training (Logistic Regression)
4.  Model evaluation and visualization

## Files

*   `UFC_Fight_Prediction.ipynb`: Jupyter Notebook containing the complete code for data preprocessing, model training, evaluation, and prediction.
*   `ufc_fighters.csv`: Dataset containing information about UFC fighters.
*   `ufc_event_fight_stats.csv`: Dataset with fight statistics for UFC events.
*   `ufc_fighters_avg.csv`: Dataset containing average fighter statistics.

## Usage

1.  Clone the repository: `git clone https://github.com/your-username/UFC-Fight-Forecaster.git`
2.  Install the required libraries: `pip install -r requirements.txt`
3.  Open and run the Jupyter Notebook: `jupyter notebook UFC_Fight_Prediction.ipynb`

## Results

The model achieved [mention your model's performance metrics, e.g., accuracy, F1-score] on the test dataset. The notebook also includes visualizations of predicted fight outcomes and feature importance.
### Predicted Fight Outcomes for UFC 309

| Fight                       | Predicted Winner | Probability |
| --------------------------- | ---------------- | ----------- |
| Jon Jones vs Stipe Miocic   | Jon Jones        | 0.85        |
| Charles Oliveira vs Michael Chandler | Charles Oliveira | 0.62        |
| Bo Nickal vs Paul Craig     | Bo Nickal       | 0.91        |
| Viviane Araujo vs Karine Silva | Viviane Araujo   | 0.58        |
| Mauricio Ruffy vs James Llontop | Mauricio Ruffy  | 0.75        |


## Future Work

*   Incorporate more data sources (e.g., fight narratives, judges' scores)
*   Explore more advanced feature engineering techniques
*   Experiment with different machine learning algorithms
*   Address class imbalance

## Disclaimer

This model is intended for educational and entertainment purposes only. It should not be used for gambling advice.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

[Choose a license, e.g., MIT License]
