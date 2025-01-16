# 🎬 Netflix Recommendation System

## 🎯 <font color="#F20400">AIM</font>
The aim of this project is to build a recommendation system for Netflix users. This system will suggest movies and TV shows based on user preferences and viewing history, enhancing the user experience by providing personalized recommendations. 

---

## 📂 <font color="#F20400">Dataset Description</font>
The dataset contains information about movies and TV shows available on Netflix. Each record represents a unique content item with various attributes describing its metadata. Below is a detailed explanation of the columns in the dataset:

### 📋 <font color="#F20400">Columns:</font>
1. **🎫 Show Id**: A unique identifier for each content item.
2. **🎥 Title**: The title of the movie or TV show.
3. **📝 Description**: A brief summary of the content's storyline or theme.
4. **🎬 Director**: The director(s) of the content (if applicable).
5. **🎭 Genres**: The genres associated with the content, such as Horror, Comedy, or Documentary.
6. **👥 Cast**: The main actors or actresses featured in the content.
7. **🌎 Production Country**: The country where the content was produced.
8. **📅 Release Date**: The year when the content was released.
9. **🔞 Rating**: The age rating of the content (e.g., TV-MA, TV-14).
10. **⏳ Duration**: The length of the content (in minutes for movies or number of seasons for TV shows).
11. **⭐ IMDb Score**: The IMDb rating of the content, showing user feedback and quality.
12. **📀 Content Type**: Indicates whether the item is a "Movie" or a "TV Show."
13. **📆 Date Added**: The date when the content was added to Netflix.

---

## 🎯 <font color="#F20400">Objective</font>
By leveraging this dataset, the project aims to:
- 🔍 Analyze user preferences based on genres, ratings, and IMDb scores.
- 🤝 Use similarity measures (e.g., cosine similarity) to recommend similar content to users.

---

## 📊 <font color="#F20400">Results</font>

The recommendation system allows users to input the title of a movie or TV show, and it provides a list of similar content based on the genres. Using the **TF-IDF vectorizer** and **cosine similarity**, the system analyzes the genre descriptions to find content with the highest similarity to the input title.

This recommendation system provides:
- 🎯 Personalized suggestions by identifying related genres and similar content.
- 📈 Enhanced user engagement by helping users explore more movies and TV shows they may enjoy.

---
