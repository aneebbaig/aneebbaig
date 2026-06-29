# Apps showcase — handoff

Everything is pre-wired. In 2–3 days, when the apps are on the Play Store:

## What you send me
1. **Play Store URLs** — one per app (Cue, TrackPal)
2. **Screenshots** — drop into:
   - `assets/screenshots/cue/` → `1.png`, `2.png`, `3.png`
   - `assets/screenshots/trackpal/` → `1.png`, `2.png`, `3.png`

That's it. I then: replace the `STORE_LINK_*` tokens, paste the section below into `README.md` (after **Featured Projects**), and remove the standalone TrackPal row from the Featured Projects table (it moves into Apps).

---

## Ready-to-paste section (tokens get filled on handoff)

```markdown
## Apps

Flutter apps I've designed and shipped. Source is private (commercial products) — try them live on the Play Store.

### Cue — AI Android Automation
> Describe what you want to automate in plain English; Gemini sets it up. Triggers on WiFi/Bluetooth/battery/time, runs on-device, works offline.

**Flutter · Gemini AI · WorkManager** &nbsp;·&nbsp; [▶ Google Play](STORE_LINK_CUE)

<p align="center">
  <img src="assets/screenshots/cue/1.png" width="24%" />
  <img src="assets/screenshots/cue/2.png" width="24%" />
  <img src="assets/screenshots/cue/3.png" width="24%" />
</p>

### TrackPal — Fitness Tracker
> Log workouts, track body metrics, monitor progress, plan nutrition. Flutter client backed by a Python/FastAPI API with JWT auth.

**Flutter · Riverpod · FastAPI** &nbsp;·&nbsp; [▶ Google Play](STORE_LINK_TRACKPAL) &nbsp;·&nbsp; [API](https://trackpal-backend.vercel.app)

<p align="center">
  <img src="assets/screenshots/trackpal/1.png" width="24%" />
  <img src="assets/screenshots/trackpal/2.png" width="24%" />
  <img src="assets/screenshots/trackpal/3.png" width="24%" />
</p>
```

---

## Adding more apps later
Same pattern: make `assets/screenshots/<app>/`, drop `1.png`–`3.png`, copy a block above, swap the name/pitch/stack/store link.
