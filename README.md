__AI Symptom Diary – Mood & Symptom Tracker__
 
An AI-powered Python tool that allows users to write daily journal entries, analyze their emotional mood using sentiment analysis, extract physical symptoms using keyword detection, and visualize mood trends over time.

__Features__

- Sentiment Analysis using TextBlob (Positive, Neutral, Negative)

- Symptom Extraction using Regex and predefined medical keyword list

- Mood Trend Visualization with matplotlib

- CSV Logging for daily entries

- Offline Local Data storage (privacy-safe)

 __Objective__

 To help mental health patients, therapists, chronic illness users, and individuals practicing self-care track emotional and physical health in a private, AI-assisted manner.

__How It Works__

- User enters a journal entry
-  TextBlob analyzes the mood
-  Regex detects symptoms from a list
-  Data is stored in diary_log.csv
-  Mood graph is updated over time

  __Tech Stack__

  | Tool             | Purpose                    |
| ---------------- | -------------------------- |
| Python           | Programming Language       |
| Jupyter Notebook | Development Environment    |
| TextBlob         | Sentiment Analysis         |
| re (Regex)       | Symptom Keyword Extraction |
| matplotlib       | Mood Graph Visualization   |
| pandas           | CSV File Handling          |

## 📁 Project Structure

```
AI_Symptom_Diary/
├── AI_Symptom_Diary_Mood_Tracker.ipynb
├── diary_log.csv  ← (auto-generated)
```

__Example__

__Input__

I had a bad headache and felt tired today. No energy at all.

__Output__

```
🧠 Mood: Negative  
💊 Symptoms found: ['headache', 'fatigue']
✅ Entry saved to diary_log.csv
```

__Mood Chart Sample__

The mood trend chart shows how your mood changes over time.

- X-axis: Date
- Y-axis: Mood Score
  - +1 = Positive
  -  0 = Neutral
  - -1 = Negative

 __Target Users__

 - Mental Health Patients
 - Doctors / Therapists
 - Chronic Illness Users
 - Self-Care Enthusiasts
 - Data Researchers

__Data Privacy__

Your entries are saved locally in a CSV file. No data is sent online.

__Setup Instructions__

 -  Clone the repository:

  ```
  git clone https://github.com/your-username/AI-Symptom-Diary.git
  cd AI-Symptom-Diary
  ```
  - Install dependencies:
    ```
    pip install textblob matplotlib pandas
    python -m textblob.download_corpora
    
    ```
  - Run the notebook or script and start journaling!!

__Future Ideas__

  - Add emojis for moods 😄 😐 😢
  - Symptom frequency tracker
  - Streamlit web version
  - Triggers and trend detection

__Made With__

  - Python
  - Jupyter Notebook
  - ❤️ for self-care and mental health
  
__License__

  __This project is for educational use only.__

---

##  About Me

**Name:** Sanjanaa S 

**Course:** B.Tech Artificial Intelligence and Data Science

**College:** Rajalakshmi Institute of Technology

**Year:** 3rd Year  

**Email:** sanjanaasrinivasan7@gmail.com

**LinkedIn:**  www.linkedin.com/in/sanjanaa-srinivasan-802ba5290

**GitHub:**  https://github.com/Sanjanaa7

---

    
  


    
  





