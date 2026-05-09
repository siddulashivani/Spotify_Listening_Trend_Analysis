# Spotify Listening Trend Analysis
A 5-page interactive Power BI dashboard analysing Spotify streaming trends across 76,101 tracks, 114 genres, and 17,062 artists to uncover popularity patterns, genre dominance, and audio feature insights.

Spotify Analytics • Interactive Dashboards • Audio Feature Insights • Trend Analysis

## Project Overview

> **This Spotify Listening Trend Analysis Dashboard was built using Microsoft Power BI to analyse 76,101 Spotify tracks across 114 genres and 17,062 unique artists.The dashboard helps uncover music streaming trends, track popularity patterns, artist performance, genre dominance, and audio feature behavior — all in one interactive analytical view.**

---

## Dataset Details

| Property | Value |
|----------|-------|
| **Total Rows** | 76,101 |
| **Total Columns** | 23 |
| **Unique Artists** | 17,062 |
| **Unique Genres** | 114 |
| **Unique Albums** | 44,419 |
| **Popularity Range** | 1 – 100 |

--- 

##  Dashboard Pages

| Page | Title | Slicer Used |
|------|-------|-------------|
| 1 | 📊 Overview & KPIs | Genre (Dropdown) |
| 2 | 🎵 Track Popularity Analysis | Popularity Category (Dropdown) |
| 3 | 🎤 Artist Stats Analysis | Content Type (Tile) |
| 4 | 🎸 Genre Trends Analysis | Genre Explorer (Tile) |
| 5 | 🎚️ Audio Features Analysis | Energy Level (Tile) |

---

## DAX Measures (66 Total)

| Page | Measures | Key Measures |
|------|----------|--------------|
| Overview | 13 | Total Tracks, Viral Track %, Top Track, Top Genre |
| Track Popularity | 11 | Explicit Avg Pop, Clean Avg Pop, Max Popularity |
| Artist Stats | 11 | Vocal Avg Pop, Instrumental Avg Pop, Artist Rank |
| Genre Trends | 9 | Genre Avg Popularity, Top Genre, Bottom Genre |
| Audio Features | 22 | Avg Danceability, Energy, Valence, Sweet Spot measures |

---

## Key Findings

### Page 1 - Overview & KPIs
- 📊 Total catalog contains **76,101 tracks** across **114 genres** 
  and **17,062 unique artists**
- 🔥 Only **1.6%** of all tracks (1,243) achieve viral status 
  with 75+ popularity score
- ⭐ Overall average popularity score is **37.5 out of 100**
- 🏆 **Unholy** by Sam Smith is the top track with score of **100**
- 🎵 **44.1%** of tracks fall in Moderate popularity category
- 🎤 **Pop** leads all 114 genres in average popularity
- 💿 **44,419 unique albums** tracked across the catalog

### Page 2 - Track Popularity
- 🔥 Only **1.6%** of tracks (1,243) achieve viral status (75+ popularity)
- 🏆 **Unholy** by Sam Smith tops the chart with a perfect score of **100**
- 🎤 **Bad Bunny** dominates with 4 tracks in the top 10
- 🔞 Explicit tracks score **41.4** avg vs **37.1** for clean — **4.3 point advantage**

### Page 3 - Artist Stats
- 👑 **Bizarrap** is the top artist by average popularity at **99.0**
- 🎤 Vocal tracks (**80.6%** of catalog) average **39.17** popularity
- 🎸 Instrumental tracks (**19.4%**) average only **30.59** popularity
- 📊 Vocal vs Instrumental gap = **8.6 popularity points**

### Page 4 - Genre Trends
- 🥇 **Pop** leads all genres with **65.9** average popularity
- 📉 **Iranian** genre struggles at only **6.5** — a **10x gap** vs Pop
- 🌟 Top 5: Pop (65.9), Electro (63.0), House (62.1), Metal (59.6), EDM (59.3)
- ❌ Bottom 5: Iranian (6.5), Romance (9.4), Detroit Techno (11.2), Chicago House (12.3), Grindcore (14.6)

### Page 5 - Audio Features
- 💃 Avg Danceability: **0.56** (Moderately danceable)
- ⚡ Avg Energy: **0.64** (Fairly energetic)
- 😊 Avg Valence: **0.47** (Slightly melancholic)
- 🥁 Avg Tempo: **122 BPM** (Fast paced)
- 🏆 Sweet Spot: **Medium Energy (0.4–0.75)** scores highest at **39.9 avg popularity**
- 🏆 Sweet Spot: **Medium Danceability (0.4–0.7)** scores highest at **38.4 avg popularity**
  
---

## Slicers Guide

| Page | Slicer | How to Use |
|------|--------|------------|
| Page 1 | Genre | Select any of 114 genres to filter all KPI cards and charts |
| Page 2 | Popularity Category | Click Viral/Popular/Moderate/Low to filter track data |
| Page 3 | Avg Popularity by Content Type | Click Vocal/Instrumental to filter artist data |
| Page 4 | Genre Explorer | Click any genre pill to filter genre analysis |
| Page 5 | Energy Level | Click Low/Medium/High to filter audio feature data |

---

## Dashboard Visuals Summary

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

## Project Highlights

```
✅ 76,101 tracks analyzed
✅ 114 genres covered
✅ 17,062 unique artists
✅ 66 DAX measures created
✅ 5 interactive dashboard pages
✅ 5 slicers for dynamic filtering
```

## Tools Used

| Tool | Purpose |
|------|---------|
| **Microsoft Power BI Desktop** | Interactive dashboard development |
| **Power Query** | Data transformation and cleaning |
| **DAX** | Measure calculations | Project documentation and reporting | 
