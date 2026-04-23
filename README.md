# 📺 TV Show Rating Dashboard

An Excel-based analytics dashboard exploring **2,408 TV shows** spanning 1951–2026, built from a structured dataset of ratings, popularity scores, and metadata.

---

## 📊 Dashboard Overview

The project contains **three dashboard views**, each exploring the data from a different angle:

### 1. Rating Index
> *What makes a highly-rated show?*

- **Avg. Movie Rating:** 7.7 &nbsp;|&nbsp; **Ratings below avg:** 45%
- Bar chart of average ratings by decade — the **2000s peaked** at ~7.75
- Ratings distribution histogram showing most shows cluster between **7.5 and 8.5**
- Scatter plot: *Did more shows per decade lead to higher ratings?* (Spoiler: not really)

### 2. Popularity Index
> *Is popular the same as good?*

- **Avg. Movie Popularity:** 18.1 &nbsp;|&nbsp; **Shows below avg popularity:** 50%
- Decade breakdown of average popularity scores — the **1950s and 1990s** lead
- Scatter: *Does higher popularity mean better ratings?* — shows a mild **negative correlation**
- Hidden gems: highest-rated shows with **below-average popularity**, including:
  - The Boy's Word: BotA
  - Cosmos: A Personal Voyage
  - Planet Earth II & Blue Planet II

### 3. Overview Dashboard *(Interactive)*
> *The full picture with a decade slicer*

- Filterable by decade (1950s–2020s)
- **TV shows popularity over the years** — line chart showing explosive growth post-1990
- **Average show rating over the years** — relatively stable around 7.5–8.0
- **Most popular TV shows:** Law & Order, Family Guy, Friends, The Sopranos, The X-Files
- **Highest rated TV series:** ONE PIECE, Cosmos: A Personal Voyage, Cardcaptor Sakura, Neon Genesis Evangelion, Robotech

---

## 🗂️ Dataset

| Column | Description |
|---|---|
| `name` | TV show title |
| `first_air_date` | Date of first broadcast |
| `overview` | Plot summary |
| `popularity` | iMDB popularity score |
| `vote_average` | Avg. user rating (0–10) |
| `vote_count` | Number of votes |
| `adult` | Adult content flag |

**Source:** TMDB (The Movie Database) — 2,546 rows, filtered to top-rated shows

---

## 🛠️ Tools Used

- **Microsoft Excel** — PivotTables, charts, slicers, conditional formatting
- Data cleaning and decade bucketing done within Excel

---

## 💡 Key Insights

1. **The 2000s produced the highest average-rated shows** (~7.75), possibly due to the rise of prestige TV (The Wire, The Sopranos, Breaking Bad).
2. **Popularity ≠ quality** — the scatter plot reveals no strong positive correlation between a show's popularity score and its rating.
3. **Hidden gems are everywhere** — many of the highest-rated shows (e.g. documentary series like Planet Earth, niche anime) have well-below-average popularity scores.
4. **Post-1990 explosion** — the number of shows and their popularity scores surged dramatically, reflecting the streaming era's content boom.

---

## 📁 Files

```
📦 tv-show-dashboard
 ┣ 📊 [excel file](./top_rated_tv.xlsx)        ← Raw dataset
```
 ## 📸Screenshots
 ### Overview
 ![Overview Dashboard](./tv%20show%20db.png)

 ### Popularity Index
 ![Popularity Index](./tv%20show%20db-%20pop.png)

 ### Rating Index
 ![Rating Index](./tv%20show%20db-%20rat.png)
---

*Built with Excel, by Mololuwa Adenuga, 2026.*
