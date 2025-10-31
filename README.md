# 🎵 Exploratory Data Analysis (EDA) on Spotify Tracks

## 📘 Project Overview
This project presents an **Exploratory Data Analysis (EDA)** of Spotify music track data. The goal was to uncover patterns and insights related to track popularity, musical attributes, artist and album trends, and correlations among features.

Prepared by **Debmalya Das**.

---

## 🧩 Key Insights

### 🔹 Popularity
- **Highly Skewed Distribution:** Most tracks have very low popularity scores, with only a few achieving high popularity — the classic “hit song” phenomenon.  
- **Low-Popularity Concentration:** A significant number of tracks fall in the 0–5 popularity range.  
- **Dominance of Few Popular Tracks:** A small subset of songs captures the majority of listener attention.

---

### 💃 Danceability
- **Right-Skewed Towards Higher Values:** Most tracks score between 0.5–0.8, making them fairly danceable.  
- **Peak Around 0.7:** Indicates that moderately to highly danceable songs dominate the dataset.

---

### ⚡ Energy
- **Moderately High Energy Tracks Dominate:** Most tracks have energy levels between 0.5–0.9.  
- **Left-Skewed Distribution:** High-energy songs are more common than mellow ones.

---

### 😊 Valence
- **Positive Emotion Dominance:** Most songs range between 0.4–0.8 in valence, indicating a cheerful or upbeat tone.  
- **Few Sad Tracks:** Lower-valence (sad) songs are less represented.

---

### 🎸 Acousticness
- **Low Acousticness Dominates:** The dataset primarily consists of electronic or heavily produced songs.  
- **Gradual Decline:** Fewer tracks are purely acoustic.

---

## 🎤 Top Artists and Albums

### 🎙️ Top 10 Artists
- **Shankar Mahadevan** leads with the highest track count.
- The dataset includes both **Indian** and **international** artists (e.g., A.R. Rahman, Arijit Singh, Taylor Swift).

### 💿 Top 10 Albums
- **‘Dawn FM (Alternate World)’** ranks first with around 85 tracks.
- A mix of **global and Indian albums** reflects diverse genres and cultures.

---

## 📈 Tracks Released Per Year
- **Post-2010 Boom:** A sharp rise in song releases due to digital platforms and streaming services.
- **Peak in 2020–2023:** Reflects continued growth and easy music distribution.

---

## 🔍 Correlation Insights

| Feature Pair | Correlation | Insight |
|---------------|-------------|----------|
| Danceability ↔ Popularity | Weak Positive | Danceable songs tend to be slightly more popular. |
| Energy ↔ Popularity | Weak Positive | Energetic songs attract more listeners. |
| Valence ↔ Popularity | Weak Negative | Happiness doesn't always mean popularity. |
| Acousticness ↔ Popularity | Weak Negative | Acoustic tracks are less favored overall. |
| Tempo ↔ Energy | Strong Positive | Faster tempo correlates with higher energy levels. |

---

## 🔗 Pairwise Relationships
Pairplots among audio features (danceability, energy, valence, acousticness, tempo) visualize the multidimensional relationships and patterns across musical characteristics.

---

## 🧠 Conclusions

- **Promote High-Energy, Danceable Songs:** Such tracks are more likely to achieve higher popularity.
- **Support Emerging Artists:** A few artists dominate — promoting new talent can diversify listener experiences.
- **Feature Acoustic Songs Strategically:** Use in niche playlists like “Acoustic Moods” or “Relax & Unplugged.”
- **Leverage Release Trends:** Capitalize on post-2010 growth and highlight yearly trends or throwback playlists.

---

## 👨‍💻 Author
**Debmalya Das**
