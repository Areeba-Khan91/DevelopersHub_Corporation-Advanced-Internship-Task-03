🏠 Task 3: Multimodal Housing Price Prediction

🎯 Objective

To predict house prices by combining:

Structured tabular data (e.g., bedrooms, area)

Unstructured image data (frontal house images)

🛠 Methodology / Approach

Architecture: Dual-Branch Neural Network using Keras Functional API

CNN Branch:

Extracted visual and spatial features from house images

MLP Branch:

Processed numerical features such as area, bathrooms, and zip code

Feature Fusion:

Combined outputs from both branches using a concatenate layer

Optimization:

Normalized features and target prices

Trained for 50 epochs to ensure stable convergence

📊 Key Results & Observations

Evaluation Metrics: MAE and RMSE

Insight: Visual features (house style, condition) provide valuable signals that numerical data alone cannot capture, improving price prediction accuracy
