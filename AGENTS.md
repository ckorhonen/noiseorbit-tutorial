# Repository guide

## Sources and preview

`README.md` is the p5.js tutorial, `sketches/` contains standalone stages, and `sketches/FINAL.js` is the complete animation. `images/` contains referenced screenshots, GIFs, and MP4s. Preserve the tutorial sequence and original attribution when updating explanations or examples.

There is no package manifest, HTML runner, build, lint, automated test, or CI configuration. Preview one sketch at a time in a p5.js browser environment; these scripts depend on globals such as `createCanvas`, `noise`, and `frameCount` and are not Node applications. Use a disposable local runner when needed rather than adding a framework to this tutorial. With Node available, `node --check sketches/FINAL.js` checks JavaScript syntax only; substitute the changed sketch path.

## Completion and boundaries

Begin with `git status --short` and preserve unrelated changes. Finish authorized edits through relevant verification and repair, making ordinary reversible choices directly. For prose-only changes, verify tutorial links/image paths and run `git diff --check`. For sketch changes, check syntax and render the affected stage in p5.js; inspect several animation frames against the corresponding reference media and check the browser console. Syntax success alone does not validate the visual result.

Keep screenshots/media unchanged unless the requested behavior requires updates. Publishing to an external editor/account or replacing source media needs authorization within the task. If a preview runtime is unavailable, report that exact gap and complete independent source checks. Close with changed paths, executed checks, and any missing visual evidence.
