# ⚽ Premier League Match Analysis Dashboard  
### Bournemouth vs Manchester City (2025/26 Season)

---

## 📌 Objective  

To analyze a high-intensity Premier League match between **AFC Bournemouth** and **Manchester City F.C.** using event-level data, xG models, and shot-level insights to evaluate:

- Attacking efficiency  
- Chance quality  
- Tactical patterns  
- Shot-level decision making  

---

## 📊 Data Used  

- Shot-level event data (location, xG, shot outcome, body part)  
- Expected Goals (xG) model outputs  
- Shot situation classification (Open Play, Set Pieces, Free Kicks)  
- Player-level shot contribution data  
- Spatial coordinates (X, Y pitch mapping)  

---

## 🔍 Key Findings  

### 1️⃣ Bournemouth created higher-quality chances  
- xG: **Bournemouth 1.73 vs Manchester City 1.28**  
- Despite fewer shots, Bournemouth generated better scoring opportunities  

---

### 2️⃣ Shot efficiency vs volume contrast  
- Bournemouth: **0.17 xG per shot**  
- Manchester City: **0.09 xG per shot**  

➡️ City had volume, Bournemouth had quality  

---

### 3️⃣ Open-play dominance  
- Over **70% of total xG** came from open play  
- Bournemouth were especially dangerous in transition phases  

---

### 4️⃣ Fine margins decided the game  
- Bournemouth hit the post multiple times  
- One **0.48 xG chance missed by Evanilson**  
- Manchester City converted lower-xG opportunities efficiently  

---

## 📈 Visual Insights (What was built)  

- Shot map (X/Y spatial distribution)  
- xG by player dashboard  
- Shot outcome classification breakdown  
- xG by situation (open play, corners, free kicks)  
- Shot type analysis (left foot, right foot, head)  

---

## 🎯 Tactical Insights  

### 🔵 Bournemouth Strategy  
:contentReference[oaicite:0]{index=0}  
- Direct vertical attacking  
- High-quality transition opportunities  
- Strong penetration into central zones  
- Efficient chance creation but inconsistent finishing  

---

### 🔷 Manchester City Strategy  
:contentReference[oaicite:1]{index=1}  
- Possession-based control  
- Higher shot volume but lower shot quality  
- Reliance on individual finishing moments  
- Less penetration into high-value central zones  

---

## ⚔️ Tactical Implications  

- Possession ≠ chance quality  
- Transition efficiency can outperform territorial dominance  
- Shot location matters more than shot volume  
- Finishing efficiency can decide balanced xG games  

---

## 💡 Actionable Recommendations  

### For Bournemouth  
:contentReference[oaicite:2]{index=2}  
- Improve finishing in high-xG situations  
- Maintain transition-based attacking structure  
- Continue exploiting central defensive gaps  

---

### For Manchester City  
:contentReference[oaicite:3]{index=3}  
- Improve chance quality in settled possession  
- Increase central box penetration  
- Reduce low-value shot attempts  

---

## 🧠 Conclusion  

This match demonstrates a key principle in football analytics:

> **“The most dangerous team is not always the one with the ball — it is the one that creates the best chances.”**

Despite Manchester City’s dominance in shot volume, Bournemouth produced superior chance quality and remained highly competitive in expected goals.

---

## 🛠 Tools Used  

- Python (Pandas, NumPy)  
- Shot-level event data processing  
- xG modeling concepts  
- Spatial football analytics (X/Y mapping)  
- Data storytelling techniques  

---
