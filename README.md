<p align="center">
  <img src="media/icon.png" width="112" alt="OiBuddy: a painted kitten peeking over a marigold ledge">
</p>

<h1 align="center">OiBuddy</h1>

<p align="center"><strong>A tiny friend lives in your editor.</strong><br>
Water, eye rest, stretches and walks, reminded by a buddy who waits for a natural pause.</p>

![The OiBuddy sidebar: Miso on the shelf with a water jar and the next reminder](docs/store/sidebar-panel.png)

> **Preview.** OiBuddy is new and still growing. Voice lines and character motion are being reviewed and polished in upcoming updates.

## Contents

- [What it does](#what-it-does)
- [Meet the crew](#meet-the-crew)
- [Getting started](#getting-started)
- [How it behaves](#how-it-behaves)
- [Make it yours](#make-it-yours)
- [Commands](#commands)
- [Privacy and data](#privacy-and-data)
- [Feedback](#feedback)

## What it does

- **Sidebar home.** Your buddy lives on a shelf in the sidebar. It reads while you type, nods when you save, naps when you step away and welcomes you back. A jar fills with today's water and a sprout grows with your water-goal streak.
- **Gentle visits.** When a reminder is due, your buddy walks in with a speech bubble. Choose **Do it with me** for a short guided break, **Done**, **Later** or **Skip**.
- **Status bar.** Your own buddy's face always says what is next, such as "Water in 12 min", "Miso is waiting" or "Focus · 18 min left". While a reminder waits, it plays peekaboo behind the shelf. Click it to open your buddy.
- **A peek in your code.** While a reminder waits, your buddy peeks out beside the line numbers and ducks away as soon as you type. Hover that line to bring the reminder in now.
- **A shelf in the bottom panel.** Next to the Terminal, your buddy strolls along a wide shelf, plays hide-and-seek (click it to find it) and comes in for reminders.
- **Focus sessions and focus sounds.** Start a focus session from anywhere. Play original lofi tracks with rain, fireplace, café, night or wave ambience, on their own or with every session.
- **Dashboard.** Your day on one timeline, the week's progress, your little wins, reminders, settings and the crew.

![Today on the dashboard](docs/store/dashboard.png)

## Meet the crew

Pick one in the setup, switch any time on the crew page and give them your own name.

| Buddy   | Who     | How they arrive                        |
| ------- | ------- | -------------------------------------- |
| Miso    | Cat     | Quiet padding, a peek and a stretch    |
| Biscuit | Dog     | An eager trot and a settling bounce    |
| Clover  | Rabbit  | Short hops and an ear twitch           |
| Pebble  | Penguin | A waddle and a little slide            |
| Rusty   | Fox     | Light steps and a curious head tilt    |
| Theo    | Boy     | A relaxed walk and a friendly wave     |
| Maya    | Girl    | Lively steps and a two-handed greeting |

Every buddy speaks English, Hindi and Bengali with its own voice.

## Getting started

1. Install the `.vsix` through **Extensions → … → Install from VSIX**.
2. Click the **OiBuddy** icon (a little face peeking over a ledge) in the Activity Bar.
3. A three-step setup asks for your buddy, your rhythm and your working hours. That's it.

## How it behaves

- **It waits for you.** Reminders hold while you type, debug or run a task. A waiting buddy peeks in from the edge and walks in at your next pause; after 10 minutes it comes in at the next short break in your typing.
- **Breaks count.** Time away from the keyboard counts as a break for your eyes, stretches and walks. Time in another app does not.
- **No pile-ups.** Visits are spaced out, and after quiet hours, sleep or time away you get one overdue reminder instead of a burst.
- **Honest progress.** Done records progress and Later snoozes (5 minutes, 15 minutes or your usual snooze). Skipping, expiry, pausing and editing never count as progress.
- **Kind suggestions.** If a reminder keeps getting skipped, OiBuddy suggests a gentler interval. When a focus session ends, your buddy offers a short break.
- **Easy pauses.** Pause for 30 minutes, an hour or until your next working day; reminders resume on their own.

## Make it yours

- **Name your buddy** on the crew page. The name appears in speech bubbles, notifications and the status bar.
- **Language:** English, हिन्दी or বাংলা for the interface and the buddy's lines.
- **Rhythm:** working days and hours to the minute, overnight shifts, per-reminder snooze, focus sessions from 1 to 240 minutes and eight ready-made reminder templates.
- **Water:** log a glass any time with **+1 glass**, in millilitres or ounces.
- **Sound:** voice, sound effects and focus sounds are optional and start off, each with its own volume.
- **Where it shows up:** switch the code peek, the status-bar peekaboo and the bottom-panel shelf on or off in Settings, or with `oibuddy.peekInCode`, `oibuddy.animateStatusBar` and `oibuddy.bottomPanel`. All three start on.
- **Comfort:** light, dark and high-contrast themes are supported, and OiBuddy draws on top of your theme. **Reduce animation** and your system's reduced-motion setting are respected everywhere.

## Commands

| Command                             | What it does                                                             |
| ----------------------------------- | ------------------------------------------------------------------------ |
| OiBuddy: Open Dashboard             | Opens the full dashboard                                                 |
| OiBuddy: Quick Actions              | Log water, start or end focus, pause or resume, play sounds, try a visit |
| OiBuddy: Log a Glass of Water       | Records one glass                                                        |
| OiBuddy: Play or Pause Focus Sounds | Starts or stops the focus music                                          |
| OiBuddy: Pause or Resume Reminders  | Pauses until you resume                                                  |
| OiBuddy: Try a Reminder             | A practice visit that leaves progress unchanged                          |
| OiBuddy: Open Data Folder           | Shows where your data is stored                                          |

## Privacy and data

- **Local only.** Preferences, schedules and progress stay in VS Code's local extension storage. No account, no tracking and no network requests; fonts, artwork and audio ship inside the extension.
- **Safe across windows.** Several VS Code windows share one buddy, and only one window shows each visit. Writes use an exclusive lease and atomic file replacement.
- **Recoverable.** A damaged file recovers from a valid backup and is preserved before the next change. Newer saved formats are kept rather than overwritten.

## Feedback

Found a bug or have an idea? [Open an issue](https://github.com/SoubhikBiswas-gitHub/oibuddy-vscode/issues).

## License

All rights reserved. See [LICENSE](LICENSE).
