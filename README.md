# vedicville-routines

This repository is the operational anchor for VedicVille's Claude Code Routines.

It does not contain code. It exists to provide a remote environment for scheduled
Claude routines that generate content, manage distribution, and support the
VedicVille content marketing flywheel.

---

## Active Routines

| Routine | Schedule | Purpose |
|---------|----------|---------|
| VEDICVILLE DAILY CONTENT ENGINE — Routine 1 | Weekdays, 10:00 AM Belgrade (UTC+2) | Generates daily content pack: TikTok script, Instagram caption, BlueSky post, Pinterest description, and secondary platform task. Output saved to Google Drive → VedicVille → Routines. |

---

## How It Works

Each routine reads a Brand Brain context file stored in Google Drive:
**VedicVille → Routines → VEDICVILLE_CONTEXT**

This file contains VedicVille's brand voice, content strategy, 2-week content
calendar, Vedic concept rotation, and product stack. It is updated every 2 weeks.

All content output is draft only. Ronnie Ganguly reviews and approves
before anything is published.

---

## Maintenance

- Context file reviewed and updated every 2 weeks (next: June 11, 2026)
- New routines added to the table above as they are created
- Repo is private — do not make public

---

*VedicVille — Better inputs for a better reality.*
