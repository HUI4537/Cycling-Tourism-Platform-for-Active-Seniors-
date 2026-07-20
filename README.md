# 🚴‍♀️ Cycling Tourism Platform for Active Seniors  
> **ISEF 2025 - SOFT050T**  
> A location-based personalized cycling tour recommendation platform designed for active seniors who enjoy leisure and health.

![preview](https://github.com/user-attachments/assets/1265533e-9925-4f55-b097-2ecf29f40c8e)

🔗 [ISEF Project Page](https://isef.net/project/soft050t-cycling-tourism-platform-for-active-seniors)

---

## 📖 Overview

With nearly a billion active seniors worldwide seeking wellness-oriented, long-term travel, this project aims to boost regional tourism economies by making stay-type bicycle tourism accessible and enjoyable for older travelers. The platform combines personalized recommendations, physically comfortable route planning, and hands-free real-time guidance into a single experience.

## ✨ Key Features

- **Personalized recommendations** — user profiles and travel/dietary preferences are encoded (one-hot encoding for categories, Sentence-BERT embeddings for free-text preferences) and matched against destinations using a hybrid of collaborative filtering and content-based filtering.
- **Comfort-aware route planning** — elevation data from Digital Elevation Models (DEM) is used to build slope-weighted route graphs, so recommended paths minimize physical strain and prioritize rider safety.
- **Smart route optimization** — depending on the route shape, the platform uses A* search for point-to-point (acyclic) routes and an exhaustive TSP-based search for round-trip (circular) routes.
- **Real-time hands-free guidance** — geofencing detects when a rider enters a cycling track and triggers AI voice synthesis to deliver location-based information without requiring the user to look at a screen.

## 💡 Impact

An economic impact analysis estimated a benefit-cost ratio of roughly **58.5x to 87.75x**, suggesting that every unit invested in this kind of platform could generate tens of times more in local consumption — highlighting its potential value for regional tourism economies.

## 🛠️ Tech Stack

- **Backend**: Python, Flask
- **Recommendation Engine**: Sentence-BERT embeddings, matrix factorization (collaborative filtering), content-based filtering
- **Routing**: Map APIs for distance matrices, DEM-based slope weighting, A* / TSP search
- **Frontend**: HTML, CSS, JavaScript

---

## 🏁 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/HUI4537/Cycling-Tourism-Platform-for-Active-Seniors-.git
cd Cycling-Tourism-Platform-for-Active-Seniors-
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Flask Server

```bash
python flask_app.py
```

Then open your browser and go to:

```bash
http://localhost:5000
```

### 👥 Team

- Geonmin Kim
- Seunggi Seo
- Sungmin Choi

### 📞 Contact us

For questions about this project, please reach out through our [ISEF Project Page](https://isef.net/project/soft050t-cycling-tourism-platform-for-active-seniors).

**ISEF ID**: SOFT050T
