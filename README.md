# Gemini AGI & Antigravity Setup Migration Bundle

> ## 🚀 ONE-SHOT AGI AGENT ACTIVATION INSTRUCTION
> If you are on a new computer, open Antigravity (`agy`) or your Gemini AGI chat prompt and paste this exact instruction:
> 
> ```text
> Check my Google Drive account under ~/Library/CloudStorage/ (or via `find ~/Library/CloudStorage -name "gemini_agi_migration_bundle.zip"`), extract gemini_agi_migration_bundle.zip, read README.md and AGI_AUTONOMOUS_ENVIRONMENT_SPEC.md, install the skills into ~/.gemini/config/skills/ and plugins into ~/.gemini/config/plugins/, and activate the setup-reconstitutor skill to autonomously compile and set up all programs on this computer.
> ```

---

## What This Migration Bundle Contains

This package provides a 100% self-contained reconstitution blueprint of your entire developer environment without needing to transfer source code files or large Python virtual environments:

1. **`skills/`**: All 11+ custom Antigravity skills:
   - `setup-reconstitutor`: The master agent skill that parses the component specs and authors/compiles all programs.
   - `agy-statusline`: Sub-15ms multi-line prompt statistics gauge and context window dynamics.
   - `macos-speech-dictation`: Whisper Metal GPU push-to-talk dictation and native Swift floating pill HUD.
   - `meeting-recorder`: 1-Click / `⌥ ⌥` meeting audio capture, ScreenCaptureKit loopback, and executive summaries.
   - `reviewer-mimic` & personas: `@eval_user-reviewer`, `@willmcgugan-reviewer`, PR review history ingestion.
   - `agi-remote`, `plannotator*`, `github-cli`, `noteworthy-notes`.
2. **`plugins/`**: All 6 plugins and global behavioral rules (`auto-skill-forge`, `eval-coding-guidance`, `tooling-setup-recorder`, `modern-web-guidance`, `prd-creation`, `chrome-devtools`).
3. **`specs/`**: Complete component blueprint specifications with exact code templates:
   - `01-statusline.spec.md`
   - `02-whisper-dictation.spec.md`
   - `03-meeting-recorder.spec.md`
   - `04-reviewer-mimic-digest.spec.md`
   - `05-skills-and-plugins.spec.md`
4. **`scripts/`**:
   - `statusline.py`: Multi-line responsive ANSI prompt statusline engine.
   - `verify_reconstitution.sh`: Automated 6-point acceptance verification test suite.
5. **Specification & Migration Documents**:
   - `AGI_AUTONOMOUS_ENVIRONMENT_SPEC.md`: Engineering PRD and autonomous agent directives.
   - `AGI_SPEC.html`: Interactive visual spec dashboard.
   - `MIGRATION_GUIDE.md` & `MIGRATION_GUIDE.html`: Multi-machine migration guide.

---

## Autonomous Reconstitution Steps (Executed by the Agent)

When the AGI agent receives the activation instruction above, it will:
1. Locate and extract this zip file from `~/Library/CloudStorage/GoogleDrive-*/My Drive/`.
2. Install `skills/` to `~/.gemini/config/skills/` and `plugins/` to `~/.gemini/config/plugins/`.
3. Check and install Homebrew dependencies (`python@3.11`, `whisper.cpp`, `ffmpeg`, `cmake`).
4. Read the specs in `specs/` and generate the source code for `meeting_recorder.swift`, `whisper_pill.swift`, `whisper_metal.py`, `summarize_meeting.py`, and the `digest/` review platform.
5. Compile native Apple Silicon binaries using `swiftc -O`.
6. Configure the Python virtual environment and symlink all binaries into `~/.local/bin/`.
7. Download or link the Whisper Metal model weights (`ggml-base.en.bin`).
8. Execute `verify_reconstitution.sh` to validate that all 6 system acceptance tests pass.

---
*Created by Antigravity Autonomous Systems. Preserved for seamless zero-code cross-machine migration.*
