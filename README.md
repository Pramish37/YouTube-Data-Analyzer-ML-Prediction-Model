# YouTube-Data-Analyzer-ML-Prediction-Model

Hi! This is a project I built to see if I could use Machine Learning to figure out what makes a YouTube video go viral. I used a dataset of trending videos and focused mainly on the titles to see if certain words or lengths help a video get more views.

What this Project deos?
1. Predicts Virality: I built a model that can tell if a video will be "popular" (top 25% of views) with about 75% accuracy.
2. Finds Key Words: It identifies which words (like "Official or "Tralier") are most common in hit videos.
3. Recommends Videos: If you give it a video title, finds and suggests 5 other similar videos from the dataset.

   The Tech I Used
- Python: The main language.
- Pandas: To clean and organize the data.
- Scikit-Learn: For the Random Forest model and text processing (TF-IDF).
- Matplotlib & Seaborn: To make the charts and word clouds.

  
How it works?
I cleaned the video titles by removing punctuation and common words (like "the" or "is"). Then, I turned those titles into numbers so the computer could "read" them. I trained a Random Forest model to learn the difference between a normal video and a viral one. Finally, I used Cosine Similarity to build the recommendation part.


How to use it?
- In your GitHub repo, click the "Add file" button and select "Create new file".
- Name the file exactly README.md.
- Copy the text I wrote above and paste it into the box.
- Scroll down and click "Commit changes".







