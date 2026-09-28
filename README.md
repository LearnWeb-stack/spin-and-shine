# Spin to Answer 🎡

A classroom name-picker wheel. Enter your students, spin the wheel, and the chosen student gets a countdown timer to answer. Picked students leave the wheel until you put them back.

## Features
- Add students by typing or pasting a list (one per line or comma-separated)
- Multiple classes, saved automatically in the browser
- Spinning wheel with tick sounds, upbeat spin music, fanfare and confetti
- Answer panel beside the wheel: picked student, countdown timer with "thinking" music, 5-second beeps and a buzzer
- **❓ Q/A**: build a question bank per class (`Question | Answer`, one per line), show a question, spin, then mark the student ✓ Correct or ✗ Incorrect
- Reveal the answer on screen, ask your own question on the spot, next/previous/random question
- Results log with a per-student ✓/✗ tally and CSV download
- Keyboard: **Space** spin · **T** timer · **A** show answer · **N** next question
- Picked student is removed from the wheel (can be turned off in Settings)
- "Put back" buttons, shuffle, backup/restore to a file
- Full-screen mode for the projector; press **Space** to spin

All music and sounds are generated in the browser — no audio files needed.

## Host it free on GitHub Pages
1. Create a new repository on GitHub (e.g. `spin-to-answer`), set to **Public**.
2. Click **Add file → Upload files**, upload `index.html` (and this README), then **Commit changes**.
3. Go to **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then **Save**.
4. After a minute your app is live at `https://YOUR-USERNAME.github.io/spin-to-answer/`.

## Notes
- Student lists are stored in the browser you use (localStorage). Use **Backup** to save a file, and **Restore** to load it on another computer.
- Browsers block sound until you click something on the page, so the first spin starts the audio.
