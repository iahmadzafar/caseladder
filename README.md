# Clinical Case Ladder MCQ

Interactive high-yield clinical reasoning practice for NRE-style MCQs.

Created by **Ahmad Zafar**.

## What It Is

Clinical Case Ladder MCQ is a case-based learning tool built around one simple idea:

Instead of practicing isolated random MCQs, each topic begins with one anchored patient scenario. The learner then moves through multiple case segments where one meaningful clue changes at a time.

Each segment asks a single-best-answer MCQ and then reveals:

- the correct answer
- the key discriminator
- the common trap
- a future alert for exam recall

This makes the learner practice clinical pattern recognition, answer-changing variables, and trap avoidance.

## Current Coverage

- 100 high-yield topics
- 400 case ladder segments
- Multiple clinical domains
- NRE-style discriminators and traps
- Interactive answer reveal mode

## Features

- Search topics, stems, traps, and explanations
- Filter by segment type
- Expand or collapse reasoning segments
- Save progress locally
- Multiple learner profiles
- Light and dark mode
- Theme options
- Mobile-friendly PWA structure
- Offline-capable app shell after first hosted load

## How To Use

Open `index.html` in a browser or deploy the folder to a static hosting platform.

Recommended hosting options:

- Netlify
- Cloudflare Pages
- Vercel
- GitHub Pages

For best mobile experience, deploy it as a hosted site rather than sending the HTML file directly. iPhone and Android browsers handle hosted PWAs much better than loose local HTML files.

## Mobile Use

After deployment:

### iPhone

1. Open the hosted link in Safari.
2. Tap Share.
3. Tap Add to Home Screen.
4. Open Case Ladder from the Home Screen.

### Android

1. Open the hosted link in Chrome.
2. Tap the browser menu.
3. Tap Add to Home screen or Install app.
4. Open Case Ladder like an app.

## Files

- `index.html` - main interactive app
- `manifest.json` - PWA metadata
- `service worker.js` - offline cache support
- `icon 192.svg` - app icon
- `icon 512.svg` - app icon
- `mobile instructions.md` - quick deployment and mobile-use notes

## Important Boundary

This project is a separate add-on learning format.

It does not replace:

- the MedCORE MCQ framework
- NRE50 rotation logic
- standard standalone MCQ production

## Creator

**Ahmad Zafar**

