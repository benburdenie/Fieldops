# FieldOps — Crew & Equipment Manager

> Started as a coding project. Turned into something that might actually be useful.

---

## The Story

I built FieldOps to practice coding — the goal was to build something real instead of following tutorials.

I picked crew and equipment dispatching for landscaping companies because the problem is concrete. You have trucks, trailers, machines and crews. You need to know who has what, when and where. Spreadsheets fall apart fast. Existing software is either too lightweight or costs a fortune and takes months to get running.

The more I built, the more it felt like it was solving an actual problem. So now I'm putting it in front of people in the industry to find out if that's true.

Built with AI assistance — the feature direction, workflow decisions and product thinking were mine. I used AI as a coding tool to build and iterate faster.

---

## What It Does

FieldOps runs in a single HTML file, no install required. It's aimed at small landscaping operations — roughly 2 to 15 crews — that need a faster way to manage daily dispatching without paying for enterprise software.

**Scheduling and jobs** — create jobs with addresses, dates, client info and notes. Assign a crew and whatever equipment they need. If something is already booked on those dates, the app blocks the save and tells you exactly what's conflicting.

**Equipment tracking** — every truck, trailer and machine has a live status: Available, In Use, In Repair or permanently assigned to a crew. Permanently assigned gear auto-includes on every job that crew gets booked on.

**Crew management** — build out crews with foremen and workers. Block off dates when a crew is unavailable. If you try to schedule them during a blocked period, the conflict shows up before you save.

**Daily overview** — the home screen shows every active job today, which crew is on it and what equipment is out. Overdue jobs get flagged automatically.

**Dispatch sheet** — one click generates a printable daily dispatch layout with crews, jobs, addresses and equipment. Something to hand to your foreman in the morning.

---

## Try It

The demo is pre-loaded with sample data — just open it and click around. No signup, no install.

**Live demo:** [your GitHub Pages URL here]

---

## Honest Limitations

This version is fully browser-based. Data saves in `localStorage` on whatever device you're using — there's no backend, no cloud sync and no accounts. It works well as a single-user tool on one machine. Anything beyond that would need a proper backend, which is a future problem depending on whether this is worth building further.

---

## I'm Looking for Feedback

If you run a landscaping company — or know someone who does — I'd genuinely like to hear from you. A few things I'm trying to figure out:

- Does this solve a problem you actually have?
- What's missing that would make it usable for your operation?
- What would need to change for you to consider paying for something like this?

Hit the button on the demo page, open an issue here or email me at benburdenie@gmail.com.

---

## Roadmap

**Done**
- Job scheduling with real-time conflict detection
- Equipment and crew management
- Permanent equipment assignment per crew
- Crew availability blocking
- Job status tracking and overdue alerts
- Today's overview on the home screen
- Client contact info on jobs
- Printable daily dispatch sheet

**Coming (single-file version)**
- Calendar view for crew availability
- Heads-up when equipment is returning soon
- Maintenance and repair log
- Individual worker profiles

**Longer term (needs a backend)**
- Multi-user access for owners, dispatchers and foremen
- Cloud sync across devices
- Mobile view for crew leads
- Clock in / clock out

---

## Tech

Plain HTML, CSS and JavaScript. No frameworks, no build tools, no dependencies. One file. Data persists in `localStorage` under `fieldops_v4`.

---

## License

All rights reserved. Not open source — do not copy, distribute or use commercially without permission.
