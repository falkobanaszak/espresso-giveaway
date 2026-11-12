# Quishing demo

A fake "win an espresso machine" QR page for a Cyber Resilience talk, plus a live counter for the presenter screen.

- `index.html` is what the audience lands on after scanning. It says "Gotcha", explains quishing, and counts one scan per phone. It collects nothing else.
- `live.html` is the presenter view. It shows the QR code and a big live count that updates every 2 seconds.