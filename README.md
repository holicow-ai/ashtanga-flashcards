# Ashtanga Primary Series Flashcards

A single-page flashcard app for learning the Ashtanga Primary Series (Yoga Chikitsa). It covers 69 cards, from the Sun Salutation postures through Savasana.

Each card has:
- Sanskrit and English names, with a pronunciation guide
- Drishti (gaze point) and breath count
- A breath-led teaching cue
- A line-art illustration
- Three tags you can filter by: pose family, spinal action, and energy (warming / cooling / neutral)

The app also has two guides: **How to sequence** and **Cue by family**. You can flip cards, quiz yourself English-first or Sanskrit-first, shuffle, and mark cards as learned. Progress is saved in your browser.

## Run it
- **Locally:** open `index.html` in a browser. Keep the `assets/` folder next to it. There is no build step and nothing to install.
- **On GitHub Pages:** go to Settings > Pages, choose "Deploy from a branch", then `main` / root. The app is served at `https://<your-username>.github.io/<repo-name>/`.

The page loads two fonts (Montserrat, Open Sans) from Google Fonts. Offline, it falls back to system fonts.

## Files
- `index.html`: the whole app (HTML, CSS and JS)
- `assets/poses/ai/`: one illustration per pose

## Illustrations
The pose illustrations were AI-generated for this project in a single consistent style, so there are no third-party image credits. AI can get yoga anatomy wrong, so please check poses against a qualified teacher before teaching from them.
