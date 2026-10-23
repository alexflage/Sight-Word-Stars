# Sight Word Stars

A free, simple sight word practice app for early readers. It works like flash cards with a few game touches (stars, stickers, badges and streaks) and gives parents full control of the word bank.

- No ads, no accounts, no tracking
- Runs in any modern browser and can be installed to a phone or tablet home screen
- Works offline after the first visit
- Everything is saved on the child's own device

## For families

**App link:** `https://alexflage.github.io/Sight-Word-Stars/'

### Install on a phone or tablet

1. Open the link on the device the child will use (Chrome on Android, Safari on iPhone or iPad).
2. Let the page finish loading once while online.
3. Add it to the home screen:
   - **Android (Chrome):** menu (three dots) → **Add to Home screen** or **Install app**
   - **iPhone or iPad (Safari):** **Share** → **Add to Home Screen**
4. Open it from the home screen. It now works like an app, even without wifi.

### How a child plays

- Choose **Flash cards** (a grown-up or the child taps "Got it" or "Try again") or **Pick the word** (listen, then tap the right word).
- Tap the word or the speaker to hear it read aloud (uses the device's built-in voice).
- Each correct answer earns a star. Stars earn stickers, mastered words earn badges, and a flame counter tracks days practiced in a row.
- A calm timer bar runs for each card. An answer slower than the time limit (5 seconds by default) comes back later in the round.
- Words a child misses twice become "tricky" and show up more often. Words she has mastered show up less often. There is also a **Tricky words** round.

### Parent area

Open **Parent** and answer the short math question.

- **Word bank:** words are grouped by difficulty (about 500 starter words). Tap a group to open it, tap a word to turn it on or off, or use a group's **On** and **Off** buttons. Tap a word's ✕ twice to delete it.
- **Add words:** type or paste words (commas, spaces or new lines) or import a `.csv` or `.txt` file. Added words go into **My words** and are turned on right away. This is handy for lists a teacher sends home.
- **Auto-unlock:** when a word is mastered, 2 more words turn on, moving through the groups in order. It can be switched off.
- **Settings:** time limit per word, cards per round (5 or 10), and the child's name.
- **Prizes:** set real-life rewards at star milestones, like "movie night at 100 stars," and mark them as given.
- **Last 7 days:** answers, how many were right and missed, estimated minutes, and words mastered.
- **Backup:** copy a code to keep progress safe, and paste it back to restore (for example on a new device).

### Good to know

- Progress is saved in the browser on that one device. Clearing the browser's site data erases it, so copy a backup code now and then.
- Progress is tied to the app's web address. If you move the app to a new address, restore from a backup code.
- Sound uses the device's own text-to-speech voice, so voice quality varies by device. A sound button at the top turns sound off. "Pick the word" mode needs sound.

## Privacy

The app has no accounts, analytics or ads, and it does not send words, names, stars or any other progress anywhere. All of it stays in the browser's local storage on the child's device. The only outside request is the font (Andika), which loads from Google Fonts when the device is online.

## Host your own copy (GitHub Pages)

1. Create a **public** repository.
2. Upload the files from this project to the top level of the repository: `index.html`, `sw.js`, `manifest.webmanifest`, `icon-192.png` and `icon-512.png`.
3. Go to **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/(root)`, and save.
4. After a minute or two the address appears at the top of the Pages settings.

To update, upload the new `index.html` (same file name) to the repository and commit. Devices pick up the change the next time they open the app while online.

## Customizing

- The starter word groups are the `DEFAULT_GROUPS` list near the top of the script in `index.html`. Each group is a name followed by a space-separated list of words.
- The child's name, time limit, round length, prizes and word choices are all set inside the app, not in the code.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole app (page, styles and code) |
| `manifest.webmanifest` | Lets the app be installed to the home screen |
| `sw.js` | Lets the app work offline |
| `icon-192.png`, `icon-512.png` | Home screen icons |

## License and disclaimer

Free to use. Provided as is, with no warranty. Choose a license for your repository (for example MIT) and add a `LICENSE` file if you want others to reuse or modify it.

Made by a parent for a kindergartner, and shared in case it helps your family too.
