# CineMate AI – Your Movie Assistant 🎥

CineMate AI is a smart movie recommendation assistant that helps users discover movies tailored to their mood, preferences, and watch history. The project uses an API-powered backend to provide intelligent movie suggestions and renders these recommendations dynamically on the frontend.

---

## Problem It Solves
Finding the perfect movie can often be overwhelming, given the vast amount of options available. CineMate AI simplifies this by:
- Understanding user preferences such as mood, watch history, and favorite genres.
- Generating personalized recommendations that are fun, engaging, and suitable for the user's current mood.
- Saving time and effort by suggesting curated movie options.

---

## Features
- 🌟 **Mood-Based Recommendations**: Suggest movies based on how you feel.
- 🎬 **Genre Preferences**: Get results tailored to your favorite genres.
- 📜 **Watch History Integration**: Avoid repetitive suggestions by learning your movie-watching patterns.
- 🖼️ **Dynamic Frontend Rendering**: Beautifully displays recommendations with genres, descriptions, and personalized reasons for the suggestion.

---


## Technologies Used
- **Frontend**: React.js, TailwindCSS
- **API**: Mira Recommendation API

---

## How It Works

### Input
Users provide:
- Their **current mood** (e.g., happy, sad, excited).
- Their **watch history** (e.g., a movie they’ve recently enjoyed).
- Their **genre preferences** (e.g., Action, Comedy).

### Output
The backend sends this input to the **Mira Recommendation API**, which returns a list of movies. The frontend dynamically displays these recommendations with additional context, such as why each movie is recommended.

---
