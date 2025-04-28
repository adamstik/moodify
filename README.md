# Moodify 🎧

Moodify is a web-based playlist builder that helps users create custom vibe-based playlists using Spotify’s Web API.  
Pick a mood, select your favorite songs, and save your playlist — all without logging in!

---

## 🚀 Live Demo

[Visit Moodify Here](https://yourusername.github.io/moodify/)  
_(Replace with your GitHub Pages link once deployed)_

---

## 🎯 Features

- 🔎 Search songs based on a mood (e.g., chill, party, study)
- 🎶 Randomly fetch 9 songs per search
- ➕ Add selected songs to a custom \"Your Playlist\"
- 🗑️ Remove individual songs or clear the entire playlist
- 💾 Save your playlist to a cloud database (Firebase)
- 📚 View previous saved playlists
- ❌ Delete old playlists directly from the database
- 🔄 Refresh for a new batch of suggestions with \"Need More Songs?\"
- 🎨 Clean, mobile-responsive design built with Tailwind CSS

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, TailwindCSS, Vanilla JavaScript
- **APIs:** Spotify Web API, Firebase Firestore (Google Cloud)
- **Hosting:** GitHub Pages

---

## 🧠 How It Works

1. User types a vibe (e.g., \"chill\", \"hype\", \"focus\").
2. App fetches random songs matching the mood from Spotify.
3. User clicks **\"Add to My Playlist\"** on songs they like.
4. User clicks **\"Save Playlist\"** to store the playlist into Firebase.
5. User can view and delete previous playlists later.

---

## 📋 Project Structure

| File | Purpose |
|:--|:--|
| `index.html` | Main application frontend |
| `README.md` | Project overview and documentation |

---

## 🌎 How to Deploy

1. Push all your files to a GitHub repository.
2. In GitHub:
   - Go to **Settings > Pages**
   - Set **Source** to `main` branch and `/ (root)` folder.
   - Save and GitHub Pages will generate a live link!
3. Share the public URL 🎉

---

## 🛡️ Security Notice

- **Spotify Client Secret** is temporarily exposed for demo purposes only.
- **Firebase Firestore** is initially in \"Test Mode\" (open read/write access).
- In production environments:
  - Spotify API calls should be handled securely through a backend server.
  - Firestore rules should be restricted to authenticated users.
- **Credentials should be rotated or disabled after project submission**.

---

## 📜 License

Open source for educational purposes only.  
Built with ❤️ for a cloud computing + AI integrated final project.

---

## ✨ Future Enhancements

- 🔒 OAuth login to allow users to save playlists directly into their Spotify accounts
- 🎼 Play 30-second audio previews directly on the site
- 🤖 AI Mood Detection based on text input
- 📈 Analytics dashboard showing popular moods/trends

---
