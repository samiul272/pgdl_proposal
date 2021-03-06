This is a developed from starting kit for Predicting Generalization in Deep Learning challenge at NeurIPS 2020.

Prerequisites:
- Python 3.6.6
- Tensorflow 2.2
- pandas
- pyyaml
- scikit-learn

***Main code for my proposed algorithm can be viewed in baselines/proposed_complexity***

Usage:

(1) If you are a challenge participant:

- The three files in sample_code_submission.zip are sample submissions ready to go!

- modify sample_code_submission to provide a better predictor

- zip the contents of sample_code_submission (without the directory, but with metadata), or

- to verify your code will run properly (double check you are running the correct version of python):

  `python ingestion_program/ingestion.py sample_data sample_result_submission ingestion_program sample_code_submission`

- if you wish to test on the larger public data, download the public data and run:

  `python ingestion_program/ingestion.py **path/to/public/inptu_data** sample_result_submission ingestion_program sample_code_submission`

- if you wish to compute the score of your submission locally, you can run the scoring program:

  `python scoring_program/score.py **path/to/public/reference_data** **path/to/prediction** **path/to/output**`

The `baselines` directory contains a number of baselines that you may use as your starting points. If you are not familiar with the
Keras framework, these baselines should get you up to speed.
