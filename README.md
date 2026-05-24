# 🪐 Exoplanet Summer School

> **Find real planets around other stars using real NASA data — in 1 hour, no coding experience needed.**

A complete summer school activity for students in **Class 5 to 10**. By the end of one hour, every student will have downloaded actual data from the Kepler Space Telescope and discovered a real planet 1,160 light-years away.

---

## ✨ What students will do

- 🌍 Learn what exoplanets are and why scientists hunt them
- 🔭 Understand the 3 main detection methods (radial velocity, transit, direct imaging)
- 💻 Run a live Python notebook in Google Colab (no installation needed)
- 📉 Plot a real planet's transit and measure its size
- 🏆 Earn a "Certificate of Discovery"

**Everything runs in a web browser. No software to install.**

---

## 📁 What's in this repository

| File | What it is | Who uses it |
|------|------------|-------------|
| `Kepler8b_Live_Demo.ipynb` | The main hands-on activity — runs in Google Colab | Students |
| `Exoplanet_Targets_To_Try.xlsx` | 4 more planets students can experiment with | Students |
| `How_To_Run_The_Notebook_BEGINNER_GUIDE.docx` | Step-by-step Colab guide for first-timers | Students |
| `Teacher_Script_45_Pages.docx` | Full 1-hour session script | Teacher |
| `Detection_Methods_10_Pages.docx` | Focused booklet on Part 2 (detection methods) | Teacher |

---

## 🚀 Quick start (3 steps)

1. Open **[Google Colab](https://colab.research.google.com)** in your web browser
2. Click `File → Upload notebook` and choose `Kepler8b_Live_Demo.ipynb`
3. Click the ▶ play button on each cell, one at a time, from top to bottom

That's it. Within 5 minutes you'll be looking at a real planet's transit from real NASA data.

**First time using Colab?** Read `How_To_Run_The_Notebook_BEGINNER_GUIDE.docx` first — it's designed for absolute beginners.

---

## 🔬 The science behind it

- **Data source:** [NASA Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu) + [MAST](https://archive.stsci.edu)
- **Python library:** [`lightkurve`](https://docs.lightkurve.org) — the same tool NASA scientists use
- **Telescope:** Kepler Space Telescope (2009–2018)
- **Target planet:** Kepler-8b — a Hot Jupiter, ~1,160 light-years away, 3.5-day orbit

The notebook performs the same analysis astronomers use to confirm exoplanets:
1. Download brightness data from MAST
2. Clean and normalize the light curve
3. Phase-fold at the known orbital period
4. Measure transit depth → estimate planet radius

The data is **real**. The analysis is **real**. Only the discovery year is different — students rediscover what NASA found in 2010.

---

## 👩‍🏫 For teachers

The activity is designed for **60 minutes** with fast-paced delivery:

- **~35 min** — conceptual content (what's an exoplanet, planet types, habitability, atmospheres, missions)
- **~15 min** — hands-on transit data activity
- **~10 min** — final project + Certificate of Discovery

Use `Teacher_Script_45_Pages.docx` as your minute-by-minute guide. It has the script for what to say on every page, plus "Key Science" bullet points to drop in for older kids.

---

## ✅ Scientific accuracy

All planet parameters (orbital period, transit center time, transit depth) come from **published peer-reviewed research** and the NASA Exoplanet Archive (verified February 2026).

The detection-method explanations match NASA's official descriptions. Confirmed exoplanet count and other current figures were verified at the time of writing.

A few items are appropriate simplifications for the age group:
- "Glass rain on HD 189733b" describes silicate cloud condensation
- The 2025 K2-18b dimethyl sulfide (DMS) detection is noted in the booklet as still being scientifically debated

The data students analyze is genuine — not a simulation.

---

## 🛠️ Requirements

- A laptop, desktop, or tablet with a keyboard
- A web browser (Chrome, Firefox, Safari, or Edge)
- A free Google account (Gmail)
- Internet connection

No Python installation, no library setup, no admin rights needed. Everything is in the cloud.

---

## 📜 License

Free to use, share, and remix for educational purposes. Attribution appreciated but not required.

---

## 🙏 Credits

- Built with [`lightkurve`](https://docs.lightkurve.org) (Lightkurve Collaboration, 2018)
- Data from NASA's [Exoplanet Archive](https://exoplanetarchive.ipac.caltech.edu) and [MAST](https://archive.stsci.edu)
- Kepler mission: NASA Ames Research Center

---

## 🌟 What students often say after

> *"Wait — that dot on the graph is a real planet? I just found it?"*

Yes. They did.

🔭 Happy planet hunting.
