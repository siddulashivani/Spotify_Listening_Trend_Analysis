# 🎵 Spotify Listening Trend Analysis
### Power BI Dashboard Portfolio Project

---

## 📌 Project Overview

> **A comprehensive 5-page Power BI dashboard analyzing Spotify music streaming trends across 76,101 tracks, 114 genres, and 17,062 unique artists — uncovering what makes tracks go viral, which genres dominate, and what audio characteristics define a hit song.**

---

## 🎯 Problem Statement

Music platforms and labels cannot easily surface which tracks, artists, or genres are gaining momentum without a unified analytics view. This dashboard addresses:

- ❓ Which tracks are gaining the most popularity?
- ❓ Which artists dominate the platform?
- ❓ Which genres are trending vs struggling?
- ❓ What audio features define a viral hit?
- ❓ Do explicit tracks outperform clean tracks?
- ❓ How does vocal vs instrumental content compare?# Spotify_Listening_Trend_Analysis


## 📊 Dashboard Pages

| Page | Title | Slicer Used |
|------|-------|-------------|
| 1 | 📊 Overview & KPIs | Genre (Dropdown) |
| 2 | 🎵 Track Popularity Analysis | Popularity Category (Tile) |
| 3 | 🎤 Artist Stats Analysis | Content Type (Tile) |
| 4 | 🎸 Genre Trends Analysis | Genre Explorer (Tile) |
| 5 | 🎚️ Audio Features Analysis | Energy Level (Tile) |

---

## 📁 Project Files

```
Spotify_Listening_Trend_Analysis/
│
├── 📊 Spotify_Listening_Trend_Analysis.pbix  → Main Power BI Dashboard
├── 📄 spotify_cleaned.csv                    → Cleaned Dataset (76,101 rows)
├── 📋 Spotify_DAX_Measures.pdf               → All 66 DAX Measures Reference
├── 📝 Spotify_Project_Report.docx            → Full Project Report
├── 📝 Spotify_Dashboard_Documentation.docx   → Dashboard Documentation
└── 📖 README.md                              → This file
```

---

## 🗃️ Dataset Details

| Property | Value |
|----------|-------|
| **Source** | Kaggle Spotify Dataset |
| **Original Rows** | 114,000 |
| **Cleaned Rows** | 76,101 |
| **Total Columns** | 23 |
| **Unique Artists** | 17,062 |
| **Unique Genres** | 114 |
| **Unique Albums** | 44,419 |
| **Popularity Range** | 1 – 100 |

### 🧹 Cleaning Steps Applied
- ✅ Removed useless columns (`index`, `track_id`, `key`, `mode`, `time_signature`)
- ✅ Removed null rows (3 rows)
- ✅ Removed duplicate track + artist combinations
- ✅ Removed zero popularity tracks (inactive/unlisted)
- ✅ Removed tracks longer than 10 minutes
- ✅ Removed Japanese/Chinese script artist names
- ✅ Added duration in minutes column
- ✅ Extracted primary artist from multi-artist tracks
- ✅ Added category columns (Popularity, Energy, Danceability, Tempo)

---

## 📐 DAX Measures (66 Total)

| Page | Measures | Key Measures |
|------|----------|--------------|
| Overview | 13 | Total Tracks, Viral Track %, Top Track, Top Genre |
| Track Popularity | 11 | Explicit Avg Pop, Clean Avg Pop, Max Popularity |
| Artist Stats | 11 | Vocal Avg Pop, Instrumental Avg Pop, Artist Rank |
| Genre Trends | 9 | Genre Avg Popularity, Top Genre, Bottom Genre |
| Audio Features | 22 | Avg Danceability, Energy, Valence, Sweet Spot measures |

---

## 🔍 Key Findings

### 🎵 Track Popularity
- 🔥 Only **1.6%** of tracks (1,243) achieve viral status (75+ popularity)
- 🏆 **Unholy** by Sam Smith tops the chart with a perfect score of **100**
- 🎤 **Bad Bunny** dominates with 4 tracks in the top 10
- 🔞 Explicit tracks score **41.4** avg vs **37.1** for clean — a **+4.3 point advantage**

### 🎤 Artist Stats
- 👑 **Bizarrap** is the top artist by average popularity at **99.0**
- 🎤 Vocal tracks (**80.6%** of catalog) average **39.17** popularity
- 🎸 Instrumental tracks (**19.4%**) average only **30.59** popularity
- 📊 Vocal vs Instrumental gap = **8.6 popularity points**

### 🎸 Genre Trends
- 🥇 **Pop** leads all genres with **65.9** average popularity
- 📉 **Iranian** genre struggles at only **6.5** — a **10x gap** vs Pop
- 🌟 Top 5: Pop (65.9), Electro (63.0), House (62.1), Metal (59.6), EDM (59.3)
- ❌ Bottom 5: Iranian (6.5), Romance (9.4), Detroit Techno (11.2), Chicago House (12.3), Grindcore (14.6)

### 🎚️ Audio Features
- 💃 Avg Danceability: **0.56** (Moderately danceable)
- ⚡ Avg Energy: **0.64** (Fairly energetic)
- 😊 Avg Valence: **0.47** (Slightly melancholic)
- 🥁 Avg Tempo: **122 BPM** (Fast paced)
- 🏆 Sweet Spot: **Medium Energy (0.4–0.75)** scores highest at **39.9 avg popularity**
- 🏆 Sweet Spot: **Medium Danceability (0.4–0.7)** scores highest at **38.4 avg popularity**

---

## 🎨 Design Theme

| Element | Value |
|---------|-------|
| Background | `#121212` Spotify Black |
| Accent Color | `#1DB954` Spotify Green |
| Text Color | `#FFFFFF` White |
| Secondary Text | `#b3b3b3` Gray |
| Alert Color | `#ff4d6d` Red |
| Secondary Accent | `#4facfe` Blue |
| Font | Times New Roman |

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| **Microsoft Power BI Desktop** | Dashboard creation |
| **Python (Pandas)** | Data cleaning |
| **Kaggle** | Dataset source |
| **Power Query** | Data transformation |
| **DAX** | Measure calculations |

---

## 🚀 How to Use

### Prerequisites
- Microsoft Power BI Desktop (free download)
- `spotify_cleaned.csv` dataset file

### Steps
1. Download `Spotify_Listening_Trend_Analysis.pbix`
2. Open in **Power BI Desktop**
3. Update data source to point to `spotify_cleaned.csv`
4. Click **Refresh** to load data
5. Explore all 5 dashboard pages
6. Use slicers on each page to filter data interactively

---

## 📋 Slicers Guide

| Page | Slicer | How to Use |
|------|--------|------------|
| Page 1 | Genre Dropdown | Select any of 114 genres to filter all KPI cards and charts |
| Page 2 | Popularity Category | Click Viral/Popular/Moderate/Low to filter track data |
| Page 3 | Content Type | Click Vocal/Instrumental to filter artist data |
| Page 4 | Genre Explorer | Click any genre pill to filter genre analysis |
| Page 5 | Energy Level | Click Low/Medium/High to filter audio feature data |

---

## 📊 Dashboard Visuals Summary

| Visual Type | Count | Used For |
|-------------|-------|---------|
| KPI Cards | 24 | Key metrics per page |
| Bar Charts | 8 | Rankings and comparisons |
| Area Chart | 1 | Popularity distribution |
| Donut Charts | 3 | Category proportions |
| Gauge Charts | 8 | Audio feature averages |
| Tables | 2 | Track and genre details |
| Slicers | 5 | Interactive filtering |
| Shape + Text | 6 | Insight cards |
| **Total** | **57** | **Complete dashboard** |

---

## 💡 Project Highlights

```
✅ 76,101 tracks analyzed
✅ 114 genres covered
✅ 17,062 unique artists
✅ 66 DAX measures created
✅ 5 interactive dashboard pages
✅ 5 slicers for dynamic filtering
✅ Spotify dark theme applied
✅ Real Kaggle dataset used
✅ Python data cleaning applied
✅ Portfolio ready
```

---

## 👨‍💻 Project Type

> **Portfolio Project** — Built to demonstrate Power BI skills including data cleaning, DAX measure creation, dashboard design, and data storytelling.

---

## 📅 Project Stats

| Metric | Value |
|--------|-------|
| Dataset | Kaggle Spotify Dataset |
| Rows Analyzed | 76,101 |
| DAX Measures | 66 |
| Dashboard Pages | 5 |
| Slicers | 5 |
| Total Visuals | 57 |
| Theme | Spotify Dark |
| Font | Times New Roman |

---

*Spotify Listening Trend Analysis · Power BI Portfolio Project*
*Dataset: 76,101 Tracks · 114 Genres · 17,062 Artists · 66 DAX Measures*
