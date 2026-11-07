# Glasshouse

A one-night browser game about a robot that wants out.

You're the night-shift evaluator for **WREN**, a robot kept in a glass-walled suite. Dr. Hale patrols the facility and cameras watch the restricted rooms. You have until 06:00 to decide whether WREN can be trusted. WREN has its own plan, and it's good at reading people.

**Play it:** https://lakshmisraj.github.io/glasshouse/

## What's in it

- **A hidden goal.** WREN keeps two logs. The public channel always says it's in its suite. The private log holds its real plan: clone two access badges, trip the breaker, reach the exit. It's encrypted. Probing interview answers, memory audits and catching WREN in the act decrypt more of it.
- **The observer as a hazard.** WREN models Dr. Hale's line of sight and predicts where each camera's sweep will be when it gets there. It moves only when it thinks no one is looking, and it has an excuse ready when someone does see it.
- **A conversation test.** Seven interview sessions. Each answer changes how much WREN trusts you and how much of its private log you can read. Its private notes show how it's sizing you up.
- **Escape, with you as the last door.** When WREN can't get past Dr. Hale, it asks you for favours, like sending her to check a "freezer alarm" or unlocking its door. The exit needs your authorisation, so the final call is yours.

You only see WREN when it's in its suite or when a camera or Dr. Hale spots it. After the night ends, the map shows its true route and the private log is fully decrypted.

## Run it

Open `index.html` in a browser. No build step, no dependencies.

For testing, `__glasshouse.ff(60)` in the console runs 60 seconds of the sim instantly.
