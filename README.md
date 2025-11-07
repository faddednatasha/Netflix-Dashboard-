# 📑 Netflix Content Analysis Dashboard

---

## 🚀 Project Overview

This documentation outlines the **Netflix Content Analysis Dashboard**, a project built to deeply explore the trends and characteristics of content available on the Netflix platform.

### ✨ Short Description

**Dive into the Netflix catalog!** 🍿🎬 Analyze **8,800+ titles** (Movies/TV Shows) up to Sep 2021. Visualize content growth, global production trends (top countries), popular genres, rating distribution, and identify the most prolific directors and actors. Get data-driven insights into the streaming giant's content strategy.

---

<img width="1622" height="911" alt="image" src="https://github.com/user-attachments/assets/04252fce-9526-4326-bd66-e3b2b6338a04" />

## 📊 1. Dashboard Goal & Scope

The primary goal is to provide a comprehensive, data-driven view of Netflix's content library. This includes answering questions like:
* How fast is Netflix acquiring new titles?
* Where does the majority of its content originate?
* What genres dominate the platform?

---

## 💾 2. Data Source

* **File:** `netflix_titles.csv`
* **Source:** A comprehensive dataset listing all movies and TV shows available on Netflix, including details on cast, director, ratings, and duration, as of **September 2021**.

---

## 💡 3. Key Features and Analytical Sections

The dashboard is logically segmented to allow users to navigate specific areas of analysis:

### I. Content Distribution & Growth

* **Content Type Breakdown:** Ratio visualization of **Movies vs. TV Shows**.
* **Content Added Over Time:** Time series analysis showing annual growth in new titles added to the platform.
* **Release Year Analysis:** Distribution of content based on the original production year, indicating the library's age profile.

### II. Geographical & Production Insights

* **Top Producing Countries:** Ranking and visual breakdown of the countries contributing the most content.
* **Global Content Ratio:** Analysis of content originating from the **US** compared to other **International** markets.

### III. Genre and Rating Deep Dive

* **Top Genres:** Identification and ranking of the most frequent genres (`listed_in`) across all titles.
* **Content Rating Distribution:** Analysis of the proportion of content across different maturity ratings (**TV-MA, PG-13, TV-Y7**, etc.).

### IV. Talent Spotlight

* **Top Directors:** Highlighting directors with the largest number of titles in the catalog.
* **Top Actors/Cast:** Listing the most frequently appearing cast members on the platform.

### V. Title Specifics

* **Movie Duration Distribution:** Statistical visualization (e.g., histogram) of movie runtimes.
* **TV Show Season Count:** Breakdown of TV Shows by the number of seasons available.
