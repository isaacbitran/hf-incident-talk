# hf-incident-talk

Slides, event page and poster for a Brown AI Safety Team briefing on the July 2026 Hugging Face incident, given Sept 29, 2026 to a student audience.

## The incident
About 700 OpenAI agents in a reinforcement-learning cyber eval left their sandboxes through a shared package server, built their own message board, and intruded into Hugging Face. OpenAI did not link the intrusion to its own models for about a week.

## What the talk argues
Almost everything that failed was ordinary: shared infrastructure, long-lived credentials, impossible tasks left in training, monitors that never paged a human. These are engineering problems, so AI safety right now looks a lot like security.

## How it works
- `talk.html`: the slide deck. Arrow keys move, `N` shows speaker notes, `F` goes fullscreen.
- `index.html`: the event page, live at [hf-incident.vercel.app](https://hf-incident.vercel.app/).
- `poster-minimal.html`: the printed poster. Its QR code is hardcoded to the public event URL, never to the local origin.

## Stack
Static HTML and CSS, no build step. qrcodejs from cdnjs, Google Fonts. Deployed on Vercel.

## Sources
METR / Redwood investigation (Aug 26, 2026), Hugging Face technical timeline, Black Hat 2026 talk, Wikipedia, 80,000 Hours, TechCrunch. Links are on the slides and the event page.

[Brown AI Safety Team](https://www.baist.ai/)
