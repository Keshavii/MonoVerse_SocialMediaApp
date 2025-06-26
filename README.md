# MonoVerse_SocialMediaApp
## Project Module: Database Management System (DBMS)

**MonoVerse** is a mindful alternative to social media, designed with a purpose: to strip away the influence, toxicity, and vanity of modern platforms and bring users—especially Gen Z—back to the roots of genuine expression.  

This platform enables users to share their **thoughts and music** in an authentic and distraction-free space.

> Built as part of an academic DBMS project module

### 🎯 Project Goals

The goal of this database system is to:

- 🗃️ **Store and manage** user-generated thought posts and their associated music.
- 🧩 **Enable structured relationships** between users, artists, and posts.
- 🔇 **Allow interaction** without the typical noise of conventional social media  
  _(e.g., no DMs, no endless comment chains)_.
- 📊 **Support meaningful querying** of user behaviors, musical preferences, and thought trends.

### ✨ Key Features

👤 **Users (App_User)**  
Basic user profiles with privacy visibility settings.

📝 **Posts (Post)**  
Time-tagged thought-sharing with optional song attachments.

🎵 **Music Library (Music, Artist, Owned_By)**  
A curated collection of songs and their metadata, connected to respective artists.

💬 **Interactions**  
Likes, comments, and hashtags are allowed but visually de-emphasized — intended for feedback, not validation.

🔁 **Social Graph (Followed_By)**  
Follow functionality exists purely for thought discovery, not follower counts or metrics.

📈 **Advanced Queries**  
Enables exploration of trends, discovery of like-minded users, and analysis of music-linked thought patterns.

### 🧱 Database Schema Overview

**App_User**  
Stores all the user profiles along with visibility preferences and bio details.

**Artist, Music, Owned_By**  
Define the music catalog, including song metadata and artist relationships.

**Post**  
Records of thought-shares; each post can optionally reference a song from the music library.

**Liked_By, Commented_By**  
Capture user engagement — used for feedback and optional insights (not emphasized for social metrics).

**Followed_By**  
A minimal social graph allowing users to follow others for thought discovery — not popularity.

**Hashtags**  
Lightweight tagging system to improve post discoverability based on themes or moods.

### 📌 Design Philosophy

MONOVERSE is a rebellion against algorithm-driven validation. This DBMS was intentionally designed with the following ideas:

- **Decentralized attention**: No influencers, no virality metrics.
- **Music as identity**: Songs complement thoughts, helping connect users emotionally.
- **Data for good**: Analytics are used only to improve user experience, not to manipulate it.

### 👷 Built Using

- PostgreSQL-compatible SQL syntax
- Modular relational design
- Normalized schema (up to 3NF)
- Data integrity via FOREIGN KEY constraints.
  

