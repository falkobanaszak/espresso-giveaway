# Quishing demo

A fake "win an espresso machine" QR page for the Cyber Resilience talk, plus a live counter for the presenter screen.

- `index.html` is what the audience lands on after scanning. It says "Gotcha", explains quishing, and counts one scan per phone. It collects nothing else.
- `live.html` is the presenter view. It shows the QR code and a big live count that updates every 2 seconds.

## Publish with GitHub Pages

1. Create a new **public** repository (for example `espresso-giveaway`) and upload `index.html` and `live.html`.
2. In the repo, go to Settings, then Pages. Under "Build and deployment" choose "Deploy from a branch", branch `main`, folder `/ (root)`, and save.
3. After a minute the site is live at `https://<your-username>.github.io/espresso-giveaway/`.

## On the day

- Open `https://<your-username>.github.io/espresso-giveaway/live.html?key=berlin-nov26` on your laptop. Use a new `key` for each talk so every audience starts at 0.
- The QR code on that page already points to the matching counter. Put the presenter view on screen, or use its QR on your slide.
- Test it once beforehand with your own phone. Each phone is counted once, so open the link in a private tab to test again.

The count is stored with the free Abacus counter service (abacus.jasoncameron.dev). It's public and has no uptime guarantee, so keep the "hands up" reveal as your backup.
