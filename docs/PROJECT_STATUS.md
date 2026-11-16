# Burnout Paradise Remastered VR — project status

[← Project page](../README.md) · [Flat2VR testing & discussion](https://discord.gg/P4q9zt7ek)

Reviewed **14 November 2026**. Documented branch: **P36 Exhaust Projection Preview**.

## What has been checked

- Actual-game XR Sim/Tape boost comparisons and hardware GPU controls checked the admitted particle passes, both-eye constants and restoration.

## Follow-up tests reviewed 16 November 2026

P38 exercised startup auto-confirm and manual takeover in XR Sim/Tape. In the P39 startup-to-driving test, a delayed render held the last complete stereo pair, and fresh stereo and input resumed. Physical headset behavior and all vehicle variants still need testing.

Verification records used for this section

- `P38_STARTUP_SKIP_QUALIFICATION.json`
- `P39_FRAME_RECOVERY_QUALIFICATION.json`

## Current limits

- Physical-headset visual acceptance, all vehicle/exhaust variants, weather and device recreation remain open.

## Build access

Ask for the current complete test package in the game’s Flat2VR thread. A local build record does not by itself mean a file has been uploaded to this repository’s Releases.

## Documentation basis

This overview was reconciled against the project’s recorded package notes and validation records. The following names identify the records reviewed; they are not download links:

- `BURNOUT_VR_P36_EXHAUST_20261112/README.txt`
- `P36_QUALIFICATION.json`

Game execution, simulator validation and physical-headset feedback are reported separately above. Features from a separate experimental branch are identified explicitly.
