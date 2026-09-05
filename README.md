# Little Last Light

A tiny Godot prototype: turn up a lantern to earn energy faster, attract more creatures, and watch an automatic turret defend it.

## Play

https://pelletiermaxime.github.io/little-last-light-demo/

Click the game to focus it, then press **Space** to cycle Low, Medium, and High brightness. Refresh the page to restart.

This is an early experiment: enemies do not damage the lantern yet, and progress is not saved.

## About this repository

This repository contains the exported browser build, made with Godot 4.7.2 using the Compatibility renderer and single-threaded Web export. It does not contain the editable Godot project.

To update the demo, export Web in release mode as `index.html`, replace the generated web files in this repository, and push to `main`. Keep `.nojekyll` and this README. GitHub Pages publishes from the root of `main`.
