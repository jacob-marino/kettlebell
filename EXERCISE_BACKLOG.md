# Exercise backlog

Exercises that have been taken out of a workout, or that might be added later. Nothing here is shown in the app.
Add a line when something is removed, and move it back into `index.html` (`WORKOUTS` and `ANIMS`) when it returns.

## March hold

- **Removed from:** Full-Body Complex (A, Mon/Thu), on 2026-10-04.
- **How it was programmed:** x6 each leg, 3-second hold, bell held at the chest, 8 kg or 12 kg.
- **Why it was removed:** simplifying the complex (swings, clean & squat, overhead press, rows, horn curls).
- **To bring it back:**
  - Workout entry: `{name:'March hold', reps:'×6 each leg, 3-sec hold, bell at chest', kg:[8,12]}`
  - Animation entry in `ANIMS` (the figure alternates lifting each knee while holding the bell at the chest):

    ```js
    'March hold': {move:350, frames:[frame(pose(RACK), 150), frame(pose(RACK, {foot:[60,78]}), 600), frame(pose(RACK), 150), frame(pose(RACK, {foot2:[58,78]}), 600)]},
    ```
  - The last version of the app that included it is commit `8daa431`.

## Ideas / possible add-ons

_(none yet)_
