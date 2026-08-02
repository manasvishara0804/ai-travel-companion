# 🍜 AI Travel & Food Companion

An AI-powered travel intelligence platform that personalizes day-by-day itineraries, recommends authentic local food, identifies hidden gems, and summarizes reviews using NLP — so travelers spend less time watching YouTube and scrolling Google Maps, and more time actually exploring.

## 💡 Vision

While traveling, I realized people spend hours watching YouTube and searching Google Maps just to plan a single day. This project is my attempt to fix that: an AI system that asks a few simple questions — budget, food preference, time available, travel style — and instantly generates a personalized, realistic day plan with genuine local food recommendations, not just generic top-10 lists.

Example flow — someone lands in Delhi and opens the app. It asks:
- Budget?
- Veg / Non-veg?
- Street food or cafés?
- Time available?
- Family trip or solo?
- Walking or cab?
- Hidden gems or popular spots?

...and generates the entire day, personalized to the answers.

## ✨ Features

**Built (MVP):**
- 📝 Preference-based input form (budget, food type, time, travel style)
- 🎯 Content-based recommendation engine — matches user preferences against place attributes to score and rank options
- 🗺️ AI-generated day itinerary using an LLM, combining preferences with real place data
- 💬 Review sentiment summarization (NLP) — turns dozens of raw reviews into a short, honest summary (e.g. *"great butter chicken, but expect a wait on weekends"*)
- 💎 Hidden gems filter — surfaces high-rated, low-visibility places instead of only the obvious tourist spots
- 🛣️ Simple route ordering for the day's stops to minimize backtracking

**Planned / Future Work:**
- 🤝 Collaborative filtering ("people with similar taste loved these") — requires user history data not yet available at this stage
- 📈 Demand/crowd prediction — requires historical footfall data from a paid data source
- 🎥 Real photos and short videos instead of generated visuals, to keep recommendations trustworthy

## 🛠️ Tech Stack

| Layer | Tool |
|---|---|
| Frontend + Backend | Python (Streamlit) |
| Places Data | Google Places API |
| AI / Itinerary Generation | LLM API (Claude / GPT) |
| NLP | Review sentiment summarization via LLM |
| Recommendation Logic | Content-based scoring (Python) |
| Maps | Google Maps embed |
| Deployment | Streamlit Community Cloud |

## 🚧 Status

**In Progress** — building an MVP scoped to a single city, single-day itinerary, before expanding scope.

## 📌 Why This Project

This isn't just a travel app — it's a hands-on exploration of core data science concepts: recommendation systems, NLP-based sentiment analysis, and route optimization, applied to a real problem I personally experienced while traveling.
