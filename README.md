Recomp Coach 🏋️
A minimal, offline-first gym tracker PWA built for one job: body recomposition — losing fat and building muscle at the same time.
No accounts. No servers. No ads. Your data never leaves your phone.
Why this exists
Most workout apps are bloated with social feeds, exercise encyclopedias, and subscriptions. This app does the opposite: it knows your program, tells you what's next, and gets out of the way. Logging a set is two taps.
Features
Rotating 4-session program — Push / Legs+Core / Pull / Lower+Back, rotated automatically (A→B→C→D). The app always knows which session is next; you just tap Start.
Tap-first set logging — steppers instead of typing: tap ±1 kg, hold for ±5 kg jumps. Works with any machine's weight stack.
Progressive overload built in — every exercise pre-fills what you lifted last time and tells you to beat it.
Automatic rest timer — tick a set and the countdown starts by itself (60–120 s depending on the lift), with vibration when it's time to go.
Weekly body check-in — log smart-scale data (weight, body fat %, waist, muscle mass…). Fat mass, lean mass, and BMI are calculated automatically.
Recomp verdict — the Progress screen compares fat mass and lean mass against your starting point and tells you in plain words whether the plan is working, plus estimated 1RM trends on the key lifts.
Full workout history — every session, every set, with total volume.
Backup & restore — one-tap export to a JSON file in your phone's Downloads, one-tap restore. Move phones without losing anything.
Offline-first — installs to your home screen as a PWA and works with no internet at all.
Tech
Single-file vanilla JS app — no framework, no build step, no dependencies
IndexedDB for on-device storage (with persistent-storage request so the OS won't evict it)
Service worker for full offline support
~30 KB total
Install
Open the deployed URL on your phone
Browser menu → Add to Home screen
That's it — it opens full-screen like a native app
Self-hosting
It's five static files. Host them anywhere (GitHub Pages, Netlify, Cloudflare Pages):
Code# Gym-set-logger
App to log gym progress
