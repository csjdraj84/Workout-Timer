# 🏋️ Workout Timer

**A fully responsive single-file workout timer** built for quick circuit training.  

Customize your workout, save presets, and get automatic beep + voice countdowns in the last 5 seconds of every work and rest interval. Works perfectly on phones, tablets, and desktop — no install required.


## ✨ Features

- **Fully customizable circuits**
  - Workout name
  - Number of exercise types
  - Reps per type
  - Editable exercise names
  - Work time & rest time (in seconds)
- **Live total time calculator**
- **Smart audio & voice callouts**
  - Beep + spoken countdown ("5… 4… 3…") in the **last 5 seconds** of every work **and** rest interval
- **Save / Load workouts**
  - Save presets locally (up to 12)
  - Download & upload as JSON
- **Clean timer screen**
  - Large countdown
  - Progress bar
  - Types & reps counter
  - Skip forward/back buttons
- **Mobile-first & fully responsive**
  - Optimized for iOS Safari and Android Chrome
  - Safe area insets supported
- **Offline-first** — works without internet
- **No backend, no accounts, no tracking**

## 🚀 How to Use

1. Download or copy the file **`workout-timer.html`**
2. Open it in any modern browser (Chrome, Safari, Firefox, Edge)
3. Configure your workout on the left
4. Tap **▶️ Start Workout**
5. Sweat! 💪

**Pro tip:** On mobile, add the page to your home screen for an app-like experience.

## 📋 Quick Configuration Guide

| Setting                  | Description                              | Default     |
|--------------------------|------------------------------------------|-------------|
| Workout Name             | Name of your session                     | Morning Circuit |
| Number of Workout Types  | How many different exercises             | 7           |
| Reps per Type            | Repeats per exercise                     | 3           |
| Workout Type Names       | Tap to rename each exercise              | Exercise 1… |
| Time per Work            | Duration of each work interval           | 36 seconds  |
| Rest Time                | Rest between intervals                   | 30 seconds  |

The **Total workout time** updates instantly.

## 💾 Saving & Loading

- **💾 Save** → Stores the current configuration locally
- **⬇️ Download JSON** → Export as a file
- **⬆️ Load Config** → Import a saved JSON file
- All saved workouts appear on the right panel

## 🛠️ Tech Stack

- Single HTML file (no build step)
- Vanilla JavaScript + CSS
- LocalStorage for saving presets
- Web Speech API + Web Audio API for voice & beeps
- Fully responsive with CSS Grid & Clamp

## 📱 Browser Support

- ✅ Chrome / Edge (desktop & mobile)
- ✅ Safari (iOS & macOS)
- ✅ Firefox

## 📄 License

MIT License — feel free to use, modify, and share!

## 👨‍💻 Made with ❤️

Built as a fun, practical fitness tool.  
If you enjoy it, star the repo or share it with your gym buddies!

---

**Would you like me to also create:**
- A shorter version for GitHub?
- A version with installation instructions for GitHub Pages?
- Or add contribution guidelines?

Just say the word and I’ll tweak it instantly! 💪

## Live App

Access the app here: [https://csjdraj84.github.io/Workout-Timer/](https://csjdraj84.github.io/Workout-Timer/)
