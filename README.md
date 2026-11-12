# Crash Scout

**Find out why a Windows PC crashes, blue screens or restarts while a program is running.**

Crash Scout is a single portable program from Dialsoft LLC. Nothing is installed.

## Download

**[Download CrashScout.exe (version 1.1.0)](https://github.com/Dialsoft/crashscout-releases/raw/main/v1.1.0/CrashScout.exe)**

1. Save the file anywhere (a USB stick is fine) and run it.
2. Answer **Yes** to the Windows administrator prompt (needed to read blue screen dump files).
3. Press **Run Diagnosis**.

Windows SmartScreen may warn about a new program: choose **More info > Run anyway**.

## What it does

- Reads every blue screen (bugcheck) stop code and explains it in plain English
- Tells blue screens apart from sudden power-loss restarts and freezes
- Ranks the likely causes - graphics, processor, memory, power, heat, storage, drivers - with steps to try
- Record Now: records the screen and the readings so you can see what was showing just before a crash
- Names the program behind restarts that were requested rather than crashes
- Network share crashes: crash stack, mup.sys and file-system filter drivers (fltmc)
- Flight recorder: saves the PC's vital signs every second so the moments before a crash survive
- Stress test: is it the program, or the PC?
- Updates itself from this page

A short explainer video is in this repository: `CrashScout-Explainer.mp4`.

## Release notes

### 1.1.0 - November 12, 2026
- **Record Now**: records the screen along with the readings, picture by picture, so it survives the crash.
- **Restarts that were asked for**: names the program that told Windows to restart.
- **Network share crashes**: drivers on the crash stack, mup.sys flagged, neighbors named; filter driver list (fltmc); share traffic reading.

### 1.0.0 - November 11, 2026
- First release.

---
SHA-256 of CrashScout.exe 1.1.0: `8335cda460e358e7352d2b59332822ef6f721f988983afe9eda7e7066603bf28`

Copyright (c) Dialsoft LLC. `version.json` is the update feed read by the program.
