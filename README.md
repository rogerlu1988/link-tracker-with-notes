# link-tracker-with-notes
A clean and modern web app built using HTML, Tailwind CSS, and vanilla JavaScript to track and manage local file or web links along with description notes.


# 📁 Link Tracker with Notes

A clean and modern web app built using HTML, Tailwind CSS, and vanilla JavaScript to track and manage local file or web links along with description notes.

## 🚀 Features

- 📌 Add and save links with a note or description
- 💾 Data is saved in the browser's local storage (persistent across sessions)
- 📂 Load saved links from a JSON `.txt` file
- 🔍 Live search through links and descriptions
- 🗑️ Delete links instantly and update storage
- ⚡ Responsive and professional UI using TailwindCSS

## 📁 File Format for Import

To load saved links from a file, the `.txt` must contain a valid JSON array:
```json
[
  {
    "url": "C:\\Users\\User\\Documents\\Project\\design.schdoc",
    "note": "Schematic file for power board design"
  },
  {
    "url": "https://datasheets.com/device/LM5146",
    "note": "Datasheet for LM5146 buck controller"
  }
]
