# 🎼 4 Measures: A Simple Music Practice Staff + Keyboard (Saving with No Backend)

A lightweight, vibecoded, browser-based music staff tool for quickly building and playing back simple melodies, harmonies, and descants. Main use case was for practicing Choir parts as a newb of music notation.

No login. No database. Yes save files. Everything runs locally in your browser OR in the demo page online. 

NOTICE: Because this is vibecoded, there will be many bugs, especially as it relates to 8th and 16th notes. You've been warned! 

---

## ✨ Features

* 🎹 Clickable piano keyboard (C2–C6)
* 🎵 Visual grand staff (treble + bass)
* ➕ Click or right-click to add notes
* ✏️ Drag notes vertically to change pitch
* ❌ Right-click notes to delete
* ▶️ Playback with adjustable BPM
* 💾 **Download your composition as a save file (JSON)**
* 📂 **Upload a save file to restore your work later**
* 🔒 100% client-side — no data leaves your computer

---

## 🚀 How to Use

1. Open the HTML file in your browser
2. Click on the staff or keyboard to add notes
3. Drag notes to adjust pitch
4. Use **Play Staff** to hear your composition
5. Use:

   * **Download Save File** → saves your work locally
   * **Upload Save File** → restores a previous session *(must reset staff first)*

---

## 💾 Save File Format

Save files are simple JSON and look like this:

```json
{
  "version": 1,
  "bpm": 86,
  "notes": [
    {
      "pitch": "C4",
      "type": "quarter",
      "beats": 1,
      "startBeat": 0
    }
  ]
}
```

This means:

* Files are portable
* You can back them up anywhere
* You can even edit them manually if needed

---

## 🧠 Design Philosophy

This tool is intentionally:

* **Simple** → no accounts, no friction
* **Local-first** → your data stays on your machine
* **Fast to use** → open → click → create

It’s built as a quick practice/composition aid, not a full DAW or notation engine.

---

## ⚠️ Limitations (by design)

* Fixed to **4 measures**
* No staff wrapping
* No sharps/flats placement beyond visual approximation
* No time signature or key signature support
* No multi-voice/polyphony

---

## 🛠️ Future Ideas

* Pending personal time and daily-life allowances

---

## 📂 Running the Project

No setup required. No libraries to install.

Just open:

```
choir_practice_staff_keyboard.html / index.html
```

in any modern browser.

---

## 📜 License

MIT

---

## 🙌 Why This Exists

Built to make it easy to:

* Sketch musical ideas quickly
* Practice pitch relationships
* Avoid the cost and overhead of full music software
* Practice choir parts in an easy, fast and light weight environment

---

## 👤 Author

Benjamin White
Vibecoded using ChatGPT
