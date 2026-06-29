# Launch handoff — showcase repos for Cue + TrackPal

Plan: each commercial app gets a small PUBLIC "showcase repo" (README + screenshots, no source).
These show up as real pinned repos on the profile, look professional, and expose zero code.
The profile README stays clean and just links out.

## What you send me at launch (2-3 days)
1. **Play Store URLs** (one per app)
2. **Screenshots** (3-5 each, portrait PNG)

## Then I do, in one shot
1. Create public repo `cue` (showcase). Private app repo `cue-app` stays as-is.
   - For TrackPal the clean names are taken by private repos, so the showcase repo will be `trackpal-fitness` (or your pick).
2. Drop in the README below + screenshots under `screenshots/`.
3. Set repo description + topics (flutter, dart, android, ai).
4. Pin both showcase repos (+ coffer) on the profile.
5. Update the profile README's "launching soon" line to real Play Store links.

---

## Showcase repo README template (per app)

```markdown
# Cue

AI-powered Android automation, built with Flutter.

[![Get it on Google Play](https://img.shields.io/badge/Google_Play-Download-414141?style=for-the-badge&logo=googleplay&logoColor=white)](STORE_LINK)

## What it does

Tell Cue what you want to automate in plain English and it sets it up for you using Gemini.
No learning triggers and actions, just describe it.

- Triggers: wifi, bluetooth, battery level, time of day
- Actions: sound mode, Do Not Disturb, notifications, open an app
- Runs on-device and works offline
- Reliable in the background (foreground service + WorkManager)

## Screenshots

<p align="left">
  <img src="screenshots/1.png" width="24%" />
  <img src="screenshots/2.png" width="24%" />
  <img src="screenshots/3.png" width="24%" />
</p>

## Built with

Flutter, Dart, Gemini API, WorkManager, Riverpod

## Note

This is a showcase repo. Cue is a commercial product so the source is private.
Happy to walk through the architecture or a demo on request.
```

(TrackPal version: same shape. Pitch = "Log workouts, track body metrics and plan nutrition. Flutter app with a Python/FastAPI backend." Built with: Flutter, Riverpod, Dio, FastAPI.)

---

## Note on the old scaffold
The `assets/screenshots/` folders in this profile repo are no longer needed under the
showcase-repo approach (screenshots live inside each showcase repo instead). Safe to delete,
or I'll clean them up at launch.
