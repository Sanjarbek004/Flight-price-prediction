This project integrates Machine Learning and Deep Learning techniques to build an intelligent flight ticket recommendation system.
It predicts flight prices using ML models and combines them with DL-based user preference scoring to generate personalized and optimized flight suggestions.

Key Features:
ML Model (Random Forest / XGBoost): Predicts flight ticket prices based on airline, class, stops, duration, and days left.

DL Model (Neural Network): Learns user preferences from historical patterns using embeddings for airlines and destinations.

Hybrid Integration: Merges ML and DL results to generate a final ranking score for each flight option.

Encoders & Model Storage: All models and encoders are saved and reloaded for future predictions (.pkl and .h5 files).

Ranking System: Combines both models' outputs to recommend the most suitable flights for each user.

Technologies Used:

Python

Pandas, NumPy, Scikit-Learn

TensorFlow / Keras

Joblib

Matplotlib (for training visualization)
