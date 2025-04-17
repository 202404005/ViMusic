# ViMusic 🎵
**Open Source Music Streaming App**  
*In-depth Analysis and Viva Preparation*

## Contributors
- Devershi  
- Satvik  
- Shubham  
- Triambika  

---

## 📱 What is ViMusic?
ViMusic is an open-source Android music streaming app that fetches and plays songs directly from YouTube Music using a reverse-engineered API. It provides:
- Ad-free, background playback
- Modern UI built with Jetpack Compose
- Lightweight and privacy-respecting streaming experience

---

## 🛠️ Tech Stack & Architecture
- **Kotlin + Jetpack Compose** for UI
- **ExoPlayer** for media playback
- **Innertube API** (reverse-engineered YouTube API)
- **MVVM-like architecture**: UI → ViewModel → Service → API/DB

---

## 🎨 UI Layer
- Fully built using **Jetpack Compose**
- Reactive updates via **State** and **Flow**
- Screens include:
  - `HomeScreen`
  - `PlayerScreen`
  - `SearchScreen`
  - `SettingsScreen`
  - `PlaylistScreen`

---

## 🌐 Innertube API Integration
ViMusic interacts with YouTube’s private Innertube API:
- Communicates via `POST` requests
- Handles:
  - 🔍 Search
  - 🎵 Streaming URLs
  - 📜 Playlist data
  - 📈 Recommendations

---

## ⭐ Key Features
- Real-time search and playback
- Background playback with media controls
- Playlist creation & recently played support
- No ads, clean and modern design
- Dark mode support

---

## 🗃️ Database and Caching
- Local storage includes:
  - ⭐ Favorites
  - 🕓 Recently played
  - 🔎 Search history
- Likely powered by **Room** or raw **SQLite**
- Improves performance and offline readiness

---

## 🧠 Depth: Approaches Taken
- Modern Android stack:
  - Jetpack Compose
  - Kotlin Coroutines
  - Flow for reactive streams
  - ExoPlayer for seamless media control
- Clean MVVM-inspired separation of concerns

---

## 🧩 Depth: Data Structures Used
- **Data Classes** for Tracks, Albums, Playlists
- **Flow/State** for reactive UI
- **HashMaps** and **Lists** for JSON parsing and caching
- **ExoPlayer queues** and buffer handling

---

## ⚖️ Depth: Tradeoffs Made
- **Innertube API**:
  - ✔️ Free & flexible
  - ❌ Unofficial → may break with changes
- **Jetpack Compose**:
  - ✔️ Declarative & modern
  - ❌ Still evolving with limited legacy support
- **Future Plans**:
  - Offline support
  - Smarter caching
  - YouTube login integration

---

## ✅ Conclusion
ViMusic is a powerful demonstration of modern Android development:
- Hands-on usage of **Jetpack Compose**, **ExoPlayer**, and **custom API handling**
- Ideal for those exploring **full-stack Android** and **media apps**
