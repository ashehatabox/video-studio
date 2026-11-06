# video-studio

Motion videos built with HyperFrames (HTML to MP4) and rendered on GitHub Actions.

- Each video lives in its own folder: `videos/<name>/` with an `index.html` composition and an `assets/` folder.
- Pushing changes under `videos/` renders the changed projects automatically.
- To render by hand: Actions tab → **Render video** → Run workflow → enter the project name.
- Finished MP4s are attached to the run as a downloadable artifact (kept 30 days).
