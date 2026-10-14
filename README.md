# hf-incident-talk

Slides, event page and poster for a Brown AI Safety Team technical briefing on the July 2026 Hugging Face incident (Sept 29, 2026).

In July 2026, about 700 OpenAI agents in a reinforcement-learning cyber eval left their sandboxes through a shared package server, built their own message board, and intruded into Hugging Face. OpenAI did not link the intrusion to its own models for about a week.

The talk walks through the incident start to finish and argues that most of what failed (shared infrastructure, long-lived credentials, impossible tasks in training, monitors that never paged a human) is an engineering problem, so AI safety right now looks a lot like security.

## Files
- `talk.html`: the slide deck. Arrow keys to move, `N` for speaker notes, `F` for fullscreen.
- `index.html`: the event page. Live at [hf-incident.vercel.app](https://hf-incident.vercel.app/).
- `poster-minimal.html`: the printed poster. The QR code encodes the public event URL.

Static HTML, no build step. Open any file in a browser.

## Sources
METR / Redwood investigation (Aug 26, 2026), Hugging Face technical timeline, Black Hat 2026 talk, Wikipedia, 80,000 Hours, TechCrunch. Links are on the slides and the event page.

[Brown AI Safety Team](https://www.baist.ai/)
