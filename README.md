# RepTitan — v0.1 playable PWA

A GitHub Pages-ready prototype based on the original multisport tracker. The athlete can test football, baseball, basketball, soccer and running drills, timing, wellness entries, study tasks, and weekly rollover.

## Publish on GitHub Pages

1. Create a public GitHub repository, e.g. `reptitan-demo`.
2. Extract the ZIP. Upload **the contents** (not the containing folder) to the root of the repository, including the `icons` directory.
3. Open **Settings → Pages → Build and deployment → Deploy from a branch**. Select `main` and `/(root)` and save.
4. Open `https://YOUR-USERNAME.github.io/reptitan-demo/` after GitHub Pages finishes deploying.
5. On iPhone, open the published URL in Safari, tap Share → Add to Home Screen. On Android, use Chrome → Install app / Add to Home screen.

## Important limitations

- This is a **playable demo**, not a finished or commercially cleared app.
- Workout data is saved **only in the current browser/device** using localStorage. It does not synchronize with other devices. Clearing site data can erase it. Use **Export Backup** to preserve a copy. There is not yet a backup import tool.
- The 5:30 AM reminder is only a preference toggle, **not a working wake-up alarm**. Use the device Clock app.
- Weekly archives are retained in local storage but there is not yet a full archive-browsing screen.
- This build keeps much of the original generated workout and recovery logic; do not treat training volume, fatigue indices, or injury warnings as validated coaching or medical advice.
- The site is public when published with GitHub Pages. Do not enter a child's name, contact details, or sensitive health information.
- RepTitan is a working product name, **not a confirmed trademark or domain clearance**.

## Testing checklist

1. Open the site on phone and desktop. Switch through all seven day tabs.
2. Enter a few reps, sleep hours and hydration values. Refresh and confirm entries remain.
3. Try the stopwatch, academic timer and weekly summary.
4. Export a JSON backup; archive a week and confirm new entries start blank.
5. Add the site to the phone home screen. Test offline after one successful online visit.

If anything breaks, capture the day/tab, the action taken, and any error message so it can be reproduced.
