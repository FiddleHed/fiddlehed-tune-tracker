# Tune Tracker

FiddleHed tune-memory tracker (Play Every Day / Tune Memory Month). Single page, no build step.
Same "Poster" skin as MetroDrone; fiddler drawing = `drawing_fiddler with glasses.jpeg`.

- Data lives in the student's browser (`localStorage`, key `fh-tune-tracker-v1`). No accounts, no server.
- Spacing rule: rating 1–4 → back tomorrow. Rating 5 → rests 2 days; each 5 in a row doubles it (2, 4, 8, 16 max).
- First visit seeds an "Oh Susannah (example)" tune with ratings 2, 3, 3, 4 (matches the PDF).
- Backup / restore = JSON file download / upload.

Embed on WordPress (same pattern as MetroDrone):
`<iframe src="https://jkleinberg.com/fiddlehed-tune-tracker/" width="100%" height="1100" style="border:0"></iframe>`
