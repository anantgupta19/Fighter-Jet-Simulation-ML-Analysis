project:
  name: Fighter Jet Simulation - Machine Learning Analysis
  version: 1.0.0
  domain: Aerospace Engineering + Applied Machine Learning
  description: >
    End-to-end machine learning analysis on custom fighter jet
    simulation data generated from SolidWorks, focusing on
    performance prediction and model error comparison.

data:
  source: SolidWorks simulation output
  type: Custom engineering simulation dataset
  format: CSV
  location: data/fighter_jet_simulation_data.csv
  characteristics:
    - simulation_generated
    - non_public
    - physics_informed
    - contains_noise

features:
  input_parameters:
    - wing_span
    - wing_area
    - angle_of_attack
    - air_density
    - velocity
    - pressure
  target_variables:
    - lift
    - drag
    - efficiency

preprocessing:
  missing_value_handling: drop_or_impute
  scaling: standard_scaler
  feature_selection: domain_knowledge_based
  outlier_handling: visual_and_statistical

models:
  type: regression
  algorithms:
    - linear_regression
    - polynomial_regression
    - ridge_regression
    - lasso_regression

training:
  train_test_split:
    test_size: 0.2
    random_state: 42
  cross_validation:
    enabled: false

evaluation:
  metrics:
    - MAE
    - MSE
    - RMSE
  model_comparison: true

visualization:
  enabled: true
  plots:
    - feature_correlation_matrix
    - prediction_vs_actual
    - error_distribution

environment:
  language: Python
  version: "3.10"
  libraries:
    numpy: latest
    pandas: latest
    matplotlib: latest
    seaborn: latest
    scikit-learn: latest

execution:
  notebook: notebooks/FighterJet_Simulation_Data_Model.ipynb
  results_path: results/
  save_metrics: true

collaboration:
  workflow: simulation_to_ml
  roles:
    - simulation_and_design
    - data_analysis_and_modeling

future_scope:
  - advanced_regression_models
  - simulation_ml_feedback_loop
  - scalable_pipeline_design


