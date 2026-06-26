# Hi, I'm Anushka Gupta  

### Data Science and ML Enthusiast  

Aspiring **Data Scientist** with a strong passion for **data-driven problem solving**. Currently building expertise in **Python, Statistics, Machine Learning, and Deep Learning**. I enjoy working on real-world datasets, applying ML techniques, and exploring AI to create impactful solutions.  




##  Technical Skills  
- **Programming:** Python ecosystem for data analysis & ML (NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn); Deep Learning (TensorFlow, Keras, Hugging Face Transformers)  
- **Tools:** Jupyter Notebook, Google Colab, Git & GitHub, MySQL 
- **Concepts:** Supervised ML (Regression, Classification), Unsupervised ML, Deep Learning (ANN, CNN, RNN, LSTM), Computer Vision, NLP (Transformers) 



## Projects  



### I. [Nifty 50 News & Earnings Sentiment Signal Research](https://github.com/CrossAnushka/sentiment-analysis)

- Built an end-to-end Python research pipeline that scores financial news and earnings-call transcripts for the Nifty 50 universe using FinBERT and a Loughran–McDonald finance lexicon, then rigorously tests whether the resulting sentiment predicts forward stock returns.
- Engineered a production-grade daily harness — fetch → score → snapshot → backtest — backed by a versioned SQLite store with dual CSV/DB writes. Implemented a "score once, re-weight many" architecture where the expensive transformer pass runs once and all downstream parameter sweeps derive from stored raw probabilities, making cross-sectional sensitivity analysis tractable across the full 50-stock universe.
- Built and validated multiple signal variants: cross-sectional news sentiment (IC +0.05, p≈0.13 over 11 biweekly windows), earnings-tone QoQ surprise (in-sample IC +0.17 at 20-day horizon, p≈0.02), and a long-only pick engine with human-readable decision cards and realized-outcome grading. Applied strict out-of-sample and information-barrier gates throughout — the leakage-free evaluation harness asserts no post-cutoff data reaches the model.
- No signal clears the bar for a tradeable edge. News sentiment does not beat a price-momentum baseline; earnings-tone surprise inflates ~70% train→test with the long-short spread flipping negative on held-out quarters. The primary contribution is a falsification harness that can cleanly kill a bad signal — earnings-tone surprise remains the strongest candidate pending live forward quarters.

### II. [Bank Customer Churn Prediction (ANN vs. Gradient Boosting)](https://github.com/CrossAnushka/bank-customer-churn-ann)

- Reframed churn on 10,000 records (~20% positive) as an imbalanced-classification problem, optimizing PR-AUC and recall over accuracy; engineered 25 features (ratio, flag, interaction, and binned terms), with 8 ranking in the top-20 importances led by a products×activity interaction.
- Benchmarked a Keras ANN against XGBoost under stratified 5-fold CV — trees won on every metric (PR-AUC 0.71 vs 0.67, ROC-AUC 0.87 vs 0.85).
- Tuned the decision threshold to a retention-cost model, lifting churn recall from 44% to 71%, and showed class weighting only slides the operating point along a fixed precision-recall frontier.

### III. [Image Classification with Artificial Neural Networks (ANN)](https://github.com/CrossAnushka/Image-Classification-using-ANN)
- Built an image classification model in TensorFlow/Keras on the Fashion-MNIST dataset to classify grayscale images into 10 apparel categories.
- Preprocessed data through normalization and train/validation/test splitting, then trained a Keras Sequential neural network with ReLU, softmax, Adam, and sparse categorical cross-entropy.
- Evaluated performance using test predictions, confusion matrix. Visualized training/validation accuracy and loss with Matplotlib and Seaborn.

### IV. [Breast Cancer Detection using Random Forest](https://github.com/CrossAnushka/breast-cancer-detection)  
- Built a predictive model using the **UCI Breast Cancer dataset**.  
- Benchmarked Random Forest against other classifiers, achieving strong accuracy and recall.  
- Engineered preprocessing, scaling, model training, and cross-validation.  

### V. [SONAR: Rock vs Mine Prediction](https://github.com/CrossAnushka/SONAR--rock-vs-mine-prediction-model)  
- Implemented a binary classifier to distinguish **rock vs mine signals**.  
- Explored Random Forest performance, optimized preprocessing and evaluation pipeline.  
- Compared results with accuracy metrics and confusion matrices.  

### VI. [Handwritten Digit Recognition](https://github.com/CrossAnushka/handwritten-digit-recognition)  
- Designed supervised ML models (SVM, KNN) for digit classification.  
- Preprocessed and split dataset, analyzed results with confusion matrices.  
- Achieved high generalization with **SVM (RBF kernel)**.  




*Eager to collaborate on ML & AI projects, open to internships and research opportunities!*  
