Echo Classification with Unsupervised Learning

This project applies unsupervised learning (K-Means clustering) to classify radar echoes from Sentinel-3 SAR altimetry into leads and sea ice.

📂 Repository Contents
Chapter1_Unsupervised_Learning_Methods.ipynb – Google Colab notebook with the full implementation.
README.md – Overview of the project and instructions.

🚀 How to Use
Open Chapter1_Unsupervised_Learning_Methods.ipynb in Google Colab.
Run all cells in order to:
Load Sentinel-3 SAR altimetry echo data.
Extract relevant waveform features.
Perform K-Means clustering to classify echoes.
Compute and visualize the average echo shape for each class.
Compare results with ESA's official classification using a confusion matrix.

📊 Summary of Results
The clustering algorithm successfully groups echoes into leads and sea ice.
The confusion matrix shows how well the model aligns with ESA's classification.
Visualization of the mean echo shapes highlights differences between the two classes.

📌 Additional Notes
Data comes from Sentinel-3 SAR altimetry.
K-Means clustering was used for classification.

✍️ Author: Jiazheng Jason Li

🎓 Student Number: 22093300

📖 UCL Assignment – Week 4

