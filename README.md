# Work Duration aka Time Interval Calculator ⏱️

A simple browser-based tool to calculate total time from multiple intervals.  
Built as a single-page **HTML + JavaScript app** (no backend required).  

---

## 🚀 Features
- Paste times in different formats:
  - `HH:MM`
  - `HH:MM:SS`
  - Plain numbers (interpreted as minutes or seconds, toggle supported)
- Toggle between **minutes mode** and **seconds mode** for plain numbers
- Auto-calculates as you type or paste
- Copy result with one click
- Auto-select result text for quick manual copy

---

## 📖 Example Inputs
```text
1:30
0:45:20
90
3600
```

## Minutes mode
- `90` → 90 minutes → `01:30:00`  
- `3600` → 3600 minutes → `60:00:00`

## Seconds mode
- `90` → 90 seconds → `00:01:30`  
- `3600` → 3600 seconds → `01:00:00`

## Usage
1. Download or clone this repository.  
2. Open `index.html` in your browser.  
3. Paste or type your times into the textarea.  
4. Toggle between minutes/seconds for plain numbers if needed.  
5. Copy the result with the button or by selecting it.

## Deploy on GitHub Pages
1. Push this repository to GitHub.  
2. Go to **Settings → Pages**.  
3. Under **Build and deployment**:  
   - Source: **Deploy from a branch**  
   - Branch: `main`  
   - Folder: `/ (root)`  
4. Save.

Your calculator will be available at:
```url
https://<username>.github.io/time-calculator/
```

## Project structure
```text
work-duration-calculator/ 
├── work_duration_calc_app.html 
└── README.md
```
