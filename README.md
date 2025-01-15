# CourtVision-AI--Machine-Learning-Program

**CourtVision AI** is an advanced machine learning program designed to predict NBA game outcomes with high accuracy. By leveraging cutting-edge analytics, rolling averages, and the power of XGBoost, CourtVision AI provides actionable insights into team performance and game results. This project showcases expertise in data preprocessing, feature engineering, and predictive modeling, making it an invaluable tool for sports analytics.

## Features
- **Predictive Modeling:** Utilizes XGBoost, a state-of-the-art machine learning algorithm, to classify game outcomes as wins or losses.
- **Feature Engineering:** Includes advanced metrics such as rolling averages, opponent matchups, and game context features.
- **Backtesting Framework:** Ensures robust evaluation of model performance over historical NBA seasons.
- **Scalable Design:** Built with a modular approach, making it easy to adapt to other sports or prediction tasks.
- **High Accuracy:** Achieves a predictive accuracy of 61.7% with balanced precision and recall.

## Technical Highlights
- **Machine Learning Algorithm:**
  - XGBoost for classification and feature importance analysis.
  - Hyperparameter tuning for optimal performance.
- **Data Preprocessing:**
  - Handling missing values, scaling numeric features, and encoding categorical variables.
  - Rolling averages over a 10-game window to capture team trends.
- **Evaluation Metrics:**
  - Accuracy, precision, recall, and F1-score.
  - Classification report for detailed performance insights.
- **Backtesting Implementation:**
  - Simulates predictions season by season for a realistic evaluation.

## How It Works
1. **Data Loading:** Reads and preprocesses NBA game data, including historical performance metrics.
2. **Feature Engineering:** Computes rolling averages, team strengths, and opponent matchups.
3. **Model Training:** Trains an XGBoost classifier using the selected features.
4. **Backtesting:** Tests the model on historical seasons to evaluate its predictive power.
5. **Performance Evaluation:** Generates detailed reports on accuracy, precision, recall, and F1-score.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/meritbh/courtvision-ai.git
   ```
2. Navigate to the project directory:
   ```bash
   cd courtvision-ai
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the program:
   ```bash
   python main.py
   ```

## Dependencies
- Python 3.10+
- pandas
- numpy
- scikit-learn
- xgboost

## Results
- **Accuracy:** 61.7%
- **Precision and Recall:** Balanced at 62% for both win and loss predictions.
- **F1-Score:** Consistent across all classes, demonstrating reliable predictions.

## Why CourtVision AI?
CourtVision AI is not just a prediction tool—it’s a showcase of advanced machine learning and data science capabilities. With its modular design and strong performance, it highlights:
- Expertise in building end-to-end data pipelines.
- Proficiency in deploying machine learning algorithms for real-world applications.
- A strong understanding of sports analytics and domain-specific feature engineering.

## Future Enhancements
- Incorporate player-level statistics for more granular insights.
- Experiment with additional algorithms such as LightGBM and CatBoost.
- Integrate live game data for real-time predictions.
- Build a user-friendly dashboard for non-technical users.

## Contact
For inquiries or collaborations, reach out via:
- **Email:** meritbhusal@example.com
- **LinkedIn:** [linkedin.com/in/merit-bhusal](https://www.linkedin.com/in/merit-bhusal-53304832b/)
- **GitHub:** [github.com/meritbh](https://github.com/meritbh)
