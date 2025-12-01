DESCRIPTION:
This project aims to examine the thematic evolution of music over the decades by analyzing predefined theme scores associated with songs. By tracking how themes such as love, heartbreak, politics, violence, and social justice change over time, we aim to understand broader cultural and societal shifts reflected in music. We use a dataset of songs with theme scores and musical features to train classification Random Forest and XGBoost models, and use the models to predict the decade of a song based on its features. The code includes preprocessing steps such as handling missing values, downsampling for imbalance, feature scaling, and dimensionality reduction via PCA. 


INSTALLATION:
1. Open the notebook musical_themes.ipynb in Google Colab
2. Install required Python libraries: pip install pandas numpy scikit-learn matplotlib
3. Place the dataset CSV file (e.g., tcc_ceds_music.csv) in the same directory as the notebook.


EXECUTION:
1. Run all cells sequentially:
   - Preprocess the dataset
   - Train the Random Forest and XGBoost models
   - Generate PCA outputs and predictions
3. Export PCA outputs, prediction probabilities, etc., to CSV for Tableau visualization 


To create the heatmap:
1. Open the notebook correlation.ipynb in Google Colab
2. Run all cells sequentially:
* Preprocess and clean the data
* Compute the overall correlation of themes across genres
* Reshape the correlation matrix into a long format for Tableau
* Compute per-genre theme correlations
3. Export both .csv files for Tableau visualization


Tableau dashboard link: https://public.tableau.com/app/profile/sarah.friedrichs/viz/DVADashboardFinal/Dashboard1 


Link to Dataset:
https://www.kaggle.com/datasets/saurabhshahane/music-dataset-1950-to-2019