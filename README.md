<!DOCTYPE html>
<html>
<head>
    <title>StackingMetalearner</title>
</head>
<body>
    <h1>StackingMetalearner</h1>
    <p>An application for operational chlorophyll-a forecasting.</p>
    
    <h2>Prerequisites</h2>
    <p>Python 3.8 or higher<br>
    pip package manager</p>
    
    <h2>Install Dependencies</h2>
    <pre><code>pip install pandas numpy scikit-learn matplotlib tkinter xgboost statsmodels</code></pre>
    
    <h2>Application Workflow</h2>
    
    <h3>Step 1: Data Upload</h3>
    <p>Upload your raw CSV data and configure the preprocessing settings.</p>
    <img src="https://images/data_upload.png" alt="Data Upload Tab" width="600">
    <p><em>Configure data columns and feature engineering settings</em></p>
    
    <h3>Step 2: Baseline Models</h3>
    <p>Train and evaluate multiple baseline forecasting models.</p>
    <img src="https://images/baseline_models.png" alt="Baseline Models Tab" width="600">
    <p><em>Select models to train and view individual performance</em></p>
    
    <h3>Step 3: Metalearner</h3>
    <p>Combine baseline model predictions using an intelligent meta-learner.</p>
    <img src="https://images/metalearner.png" alt="Metalearner Tab" width="600">
    <p><em>Configure and train the metalearner to combine model predictions</em></p>
    
    <h3>Step 4: Results & Comparison</h3>
    <p>Compare all models and export results.</p>
    <img src="https://images/results_comparison.png" alt="Results & Comparison Tab" width="600">
    <p><em>Compare model performance and export final results</em></p>
    
    <p><strong>Comparison Views:</strong><br>
    - <strong>Scatter Plots</strong>: Side-by-side comparison of all models<br>
    - <strong>Metrics Table</strong>: Numerical comparison of performance metrics</p>
</body>
</html>
