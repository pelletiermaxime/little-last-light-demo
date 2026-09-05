# Little Last Light

A tiny Godot prototype with short survival runs: dodge creatures near fixed turrets, earn energy, and improve your defenses between attempts.

## Play

https://pelletiermaxime.github.io/little-last-light-demo/

Click the game to focus it. During preparation, press **Enter** or click **Start run**. Use **WASD / arrow keys** to move and **Space** to cycle Low, Medium, and High brightness. Higher brightness earns more energy and attracts more creatures.

After a run, spend saved energy on turrets with **B**, then click inside the arena to place them. Click an existing turret to move it for free. **Escape** cancels placement. Turrets stay in place during runs; enemies get stronger and faster over time.

Energy and turret layouts are saved locally in your browser. Use the same browser profile and website to continue; clearing site data removes that progress. Saves do not sync between devices or with the native game.

Current release: **Milestone 5 — clarity and feel**, exported from source commit `4920a76` (`milestone-5`). The sidebar includes a health bar, run earnings, clickable Low / Medium / High brightness choices, and a survival/earnings recap with next-turret affordability. The top-left FPS counter updates once per second during preparation and runs. The UI and difficulty are still being refined.

## About this repository

This repository contains the exported browser build, made with Godot 4.7.2 using the Compatibility renderer and single-threaded Web export. It does not contain the editable Godot project.

To update the demo, export Web in release mode as `index.html`, replace the generated web files in this repository, and push to `main`. Keep `.nojekyll` and this README. GitHub Pages publishes from the root of `main`.
