# RhombixTechnologies_Tasks
Internship tasks completed for Rhombix Technologies - Machine Learning Domain

🎵 Spotify-Style Music Recommendation System

📚 Internship Task for Rhombix Technologies

This project was developed as part of the **Machine Learning Internship** at [Rhombix Technologies](https://www.linkedin.com/company/rhombix-technologies/).

The goal was to build a **Personalized Music Recommendation System** that predicts whether a user will **repeat a song within 30 days**, and recommend songs accordingly.

📈 Problem Statement

- Predict if a **user** will **replay a song** within the next **30 days** based on their **listening behavior**.
- Build a **machine learning model** capable of recommending songs users are likely to re-listen to.


🛠️ Technologies Used
- Python
- Pandas & NumPy
- Scikit-learn
- LightGBM (Gradient Boosting Framework)
- TF-IDF Vectorization
- Data Visualization (Seaborn, Matplotlib)
- Joblib (for model serialization)

🔍 Project Workflow

1. **Data Preprocessing**
   - Handled missing values.
   - Encoded categorical features (`user_id`, `track_name`).
   - Extracted time-based features (`hour`, `day of week`).

2. **Feature Engineering**
   - Created user-level listening patterns (`user_hour`, `user_dayofweek`).
   - Applied TF-IDF vectorization on song names for semantic representation.

3. **Model Building**
   - Used **LightGBM Classifier** for predicting song replay behavior.
   - Trained on processed features to maximize prediction accuracy.

4. **Model Evaluation**
   - Evaluated using **confusion matrix** and **classification report**.
   - Improved precision and recall for the positive class (replayed songs).

5. **Model Saving**
   - The trained model was serialized using `joblib` for future use.

6. **Recommendation System**
   - For a given user, recommended top songs they are most likely to replay based on prediction probabilities.

📂 Files Included

| File | Description |
|:----|:------------|
| `Spotify_Recommendation_System.ipynb` | Full code: preprocessing, modeling, and recommendation generation |
| `lightgbm_recommendation_model.pkl` | Saved trained LightGBM model |
| `README.md` | Project Documentation |

🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/EmanAli-07/RhombixTechnologies_Tasks.git


2. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn lightgbm seaborn matplotlib


3. Run the Jupyter Notebook `Spotify_Recommendation_System.ipynb`.

4. Load the trained model if needed:
   ```python
   import joblib
   model = joblib.load('lightgbm_recommendation_model.pkl')
   ```
🎥 Video Explanation

A detailed walkthrough video explaining the project is available (Upload_linkedin).

🔗 GitHub Repository Link

> [GitHub Repository]([https://github.com/YOUR_USERNAME/RhombixTechnologies_Tasks](https://github.com/EmanAli-07/RhombixTechnologies_Tasks))

✨ Acknowledgment

Special thanks to [Rhombix Technologies](https://www.linkedin.com/company/rhombix-technologies/) for the opportunity to work on real-world machine learning problems during the internship.
