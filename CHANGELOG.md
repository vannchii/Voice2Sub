# Changelog

This changelog mirrors the public Voice2Sub release history from the official release feed and website.

## v1.0.5 — Linux support and smoother performance

**Date:** 2026-05-20  
**Channel:** stable  
**Status:** current

Voice2Sub 1.0.5 adds Linux availability and optimizes overall performance and stability for a smoother, more reliable user experience.

### Changes

- Voice2Sub is now available for Linux.
- Optimized overall performance and stability for a smoother, more reliable user experience.

## v1.0.4 — Improved license management and safer updates

**Date:** 2026-05-18  
**Channel:** stable

Voice2Sub 1.0.4 improves license management reliability and the overall activation experience, while making updates more reliable, safer, and more stable on Windows and macOS.

### Changes

- Improved license management reliability and overall activation experience.
- Improved update reliability, safety, and stability on Windows and macOS.

## v1.0.3 — Runtime compatibility checks, clearer diagnostics and safer updates

**Date:** 2026-05-16  
**Channel:** stable

Voice2Sub 1.0.3 improves Windows runtime compatibility, adds clearer diagnostics for subtitle generation errors, and makes update paths safer for older app versions.

### Changes

- Windows: Voice2Sub checks for a supported Microsoft Visual C++ Runtime and guides users to install the latest Microsoft runtime when their system is outdated.
- Audio processing and subtitle generation errors now include detailed native process logs, exit codes, and clearer messages.
- Update compatibility is improved for users moving from older app versions.

## v1.0.2 — In-app CUDA setup, clearer download speed and free-duration limit

**Date:** 2026-05-13  
**Channel:** stable

Voice2Sub 1.0.2 updates how CUDA is enabled on Windows, improves download progress feedback, and adds a clear duration limit for the free version.

### Changes

- Windows: CUDA acceleration is managed inside the Windows app. The app detects compatible NVIDIA GPUs and lets users download required CUDA libraries from Settings.
- Download speed is now shown for app updates, CUDA libraries, and AI model downloads.

## v1.0.1 — Audio Quality Enhancement speed and stop/cancel stability

**Date:** 2026-05-04  
**Channel:** stable

Voice2Sub 1.0.1 matches the app update notes: faster Audio Quality Enhancement processing and more stable stop/cancel behavior during audio processing.

### Changes

- Optimized processing speed when using the "Audio Quality Enhancement" option.
- Improved stability when stopping or canceling audio processing.

## v1.0.0 — Initial public release

**Date:** 2025-03-20  
**Channel:** stable

The first public release introduced the desktop workflow for turning speech in video or audio into AI subtitles, transcripts and editable text.

### Changes

- Windows x64 and macOS Apple Silicon builds.
- Windows app later supports optional CUDA acceleration managed inside the app.
- Local speech recognition for offline transcription work.
- 99 recognition languages and support for common media formats.
- Subtitle and plain-text output for creator, learning and documentation workflows.
