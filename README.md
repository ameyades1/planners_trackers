# Habit Trackers

A collection of simple, printable habit tracking sheets optimized for A4 landscape printing.

## Features

- **Clean, minimalist design** — Yellow headers with checkbox squares for tracking
- **A4 landscape optimized** — Fits perfectly on standard A4 paper
- **Interactive digital version** — Click checkboxes in your browser before printing
- **Digital data persistence** — Tracks are saved to browser localStorage
- **Print-ready PDFs** — Pre-formatted with 10mm margins on all sides

## Trackers

### Monthly Habit Tracker v1
Track 12 habits over 31 days of a month.

**Files:**
- `monthly_v1/monthly_habit_tracker.html` — Interactive web version
- `monthly_v1/monthly_habit_tracker.pdf` — Print-ready PDF

**Features:**
- 31-day grid (all days of the month)
- 12 customizable habit rows
- 36px row height (~9mm when printed) — comfortable for handwriting
- Spacious Notes and Goals sections

### Weekly Habit Tracker v1
Track 12 habits over a single week.

**Files:**
- `weekly_v1/weekly_habit_tracker.html` — Interactive web version
- `weekly_v1/weekly_habit_tracker.pdf` — Print-ready PDF

**Features:**
- 7-day grid (Monday through Sunday)
- 12 customizable habit rows
- 36px row height (~9mm when printed) — comfortable for handwriting
- Spacious Notes and Goals sections

## How to Use

### Digital Version
1. Open the `.html` file in your web browser
2. Type habit names in the leftmost column
3. Click checkbox squares to mark daily completions
4. Data persists in browser storage

### Print Version
1. Open the `.pdf` file
2. Print with these settings:
   - **Paper size:** A4
   - **Orientation:** Landscape
   - **Margins:** 0mm (none) — margins are built into the PDF
   - **Scale:** 100% (actual size)

## Specifications

**Paper Size:** A4 Landscape (297mm × 210mm)

**Built-in Margins:** 10mm on all sides

**Row Height:** 36px (~9mm when printed) — optimized for comfortable handwriting

**Habits:** 12 rows per tracker

**Design:**
- Font: Arial (sans-serif)
- Header: Yellow (#f4d76a) with black title
- Alternating columns: Yellow (#fff9e6) and white for easy scanning
- Checkboxes: 12px × 12px black squares

## Browser Compatibility

Works on all modern browsers:
- Chrome/Chromium
- Firefox
- Safari
- Edge

Data is stored locally in browser localStorage and does not require any account or internet connection to use.

## Customization

Both trackers are fully customizable:

1. **Change habit names** — Click on any habit cell and type a new name
2. **Add/remove habits** — Edit the `numHabits` variable in the HTML (currently set to 12)
3. **Modify colors** — Edit CSS color values in the `<style>` section

## Files Structure

```
habit_tracker/
├── README.md
├── .gitignore
├── monthly_v1/
│   ├── monthly_habit_tracker.html
│   └── monthly_habit_tracker.pdf
└── weekly_v1/
    ├── weekly_habit_tracker.html
    └── weekly_habit_tracker.pdf
```

## License

Open source — feel free to use, modify, and share.

## Tips

- **Print quality:** For best results, print on standard 80gsm white paper
- **Multiple weeks:** Print several copies of the weekly tracker for consecutive weeks
- **Combine usage:** Use monthly tracker for overview, weekly tracker for detailed daily tracking
- **Handwriting:** The 36px row height (9mm) matches wide-rule notebook spacing for comfortable writing

---

Made with ❤️ for habit tracking.
