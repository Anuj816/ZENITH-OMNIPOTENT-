# Zenith Omnipotent 
Studio-grade lossless music player for Android

Built by ANUJ — Android / Media3 / NDK / Compose
Zenith Omnipotent
Studio-grade lossless music player for Android.
Zenith is built for people who care about how music actually sounds and feels on a phone: clean Media3 playback, a modern Jetpack Compose interface, proper metadata and artwork handling, optional DSP, and MilkDrop-style visualizers — including a real projectM path for .milk presets when the native engine is available.
What it does
Playback — Local and streaming-oriented Media3/ExoPlayer engine with queue, shuffle modes, scrubbing, notifications, and home-screen widget support
Library — Offline-first music library with folder/SAF-friendly access
Metadata — Artwork, lyrics, and tag embedding for downloads and local files
Sound — Optional EQ/DSP with session-aware audio effects
Visualizers — Zenith GPU demos plus optional projectM for authentic MilkDrop .milk presets (SAF import into app storage; no All Files required for presets)
UI — Dark, focused Compose UI aimed at full-player and immersive listening
Stack
Kotlin · Jetpack Compose · Media3 · Room · NDK/CMake · projectM · Coil · JAudioTagger
Design goals
Sound and control first — not clutter
Works offline as a real local player
Honest behavior (e.g. clear labels when using projectM vs Zenith’s own GPU demo)
No dependency on All Files access for MilkDrop preset import
License notes
App code: [your license, e.g. MIT / Apache-2.0]
projectM is LGPL-2.1 — see projectM’s license if you distribute the native library.
