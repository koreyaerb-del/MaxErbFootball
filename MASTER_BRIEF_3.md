# Max Erb Football — Master Brief

> **Purpose:** This is the standing context file for the *Max Erb Football Updates* project.
> Send it to Claude (or say "here's the Master Brief") at the start of any session so Claude
> is instantly up to speed on the player, the team, the website, and how updates get published.
> Keep it in the repo and update the dated "Latest Known Status" section as the season moves.

---

## 0. Quick orientation for Claude

- **Owner:** Korey Erb (Max's dad). Email: korey.a.erb@gmail.com
- **What this is:** A private tracker website for family & friends following Max Erb's
  quarterback campaign at Bethel University (TN).
- **The ask, most weeks:** A concise, **honest** scouting/status update on Max, tied to the
  ongoing question of his realistic path to **starting QB vs. contributing at WR/returner**.
  Plainly say when it's a quiet news week rather than padding.
- **Tone:** Warm but straight. No hype, no doom. Dad wants the real picture.

---

## 1. The player — Max (Maxwell) Erb

- **Position:** Quarterback. **Jersey #18 on gamedays** (practice #13).
- **Class / eligibility:** Sophomore, 4 years of eligibility remaining.
- **Measurables:** ~6'1", ~185 lb. 10" hands, 35" vertical, dual-threat, deep ball ~60–65 yds,
  benches 225 for 6–7 reps. Birthday: Sept 29 (age 19).
- **Hometown / HS:** Bloomington, MN — Bloomington Jefferson HS.
  Senior year (2024): ~1,271 pass yds, 12 TD, 9 INT.
- **Path:** Transferred to **Bethel (2026)** from **UW–River Falls** (Wisconsin), where in 2025
  he was a true-freshman backup QB on the **NCAA D-III national championship** team
  (behind Gagliardi Trophy winner Kaleb Blaha); recorded no game stats.
- **Recruited by:** Bethel OC **Riley Reid** (@Coach_RReid1).
- **Online:** X **@MaxwellErb** · Hudl **hudl.com/profile/19604832/max-erb**

---

## 2. Bethel University 2026 context

- **School:** Bethel University, McKenzie, TN. **NAIA**, **Mid-South Conference**. Team: Wildcats.
- **Head coach:** Chris Springer.
- **Coordinators:** OC **Riley Reid** (promoted from OL/run-game coordinator; recruited Max) ·
  DC Kris Beauchamp · ST Deandre Riddick.
- **Notable departures:** Former OC **Drew Chance** left after 2025 (Memphis offensive analyst/QBs).
  2025 starting QB **Destin Chance** graduated.
- **QB room (2026):**
  - **Silas Teat** — Jr., ~6'0", 185. **Current QB1** in early 2026.
  - **Nathan Clemmer** — So., 6'3", 192.
  - **Max Erb** — see above. Depth: QB3 and trending up; on the travel roster.
- **2025 team result:** roughly .500 (program lists 4–5).

---

## 3. Latest known status  *(update this section each week; date it)*

**As of 2026-09-19:**
- **Depth chart:** Max is **QB3 (trending up ▲)**, **on the travel roster (Yes)**, dressing/traveling.
- **QB1:** Silas Teat is taking the meaningful snaps (e.g., 5/15, 168 yds, 1 TD in the Keiser loss).
- **Record:** Tracker shows **1–1**; some box-score sources read 1–2 after Keiser — worth reconciling.
- **Results so far:** W 16–3 vs Lane College (Aug 29) · L 7–48 at #2 Keiser (Sep 12–13).
- **Next up:** @ Webber International (Babson Park, FL), **Sat Sep 19, 1:30 PM ET / 12:30 CT**;
  stream on The Sun Digital Network.
- **Read:** Consistent with "grooming as QB of the future" — Teat has QB1 reps now; Max is
  developing, dressing, and rising. Watch even games for possible first live snaps.

---

## 4. The website & repository

- **Live site:** https://maxerbfootballupdates.com  (title: "Max Erb QB Tracker")
- **GitHub repo:** `koreyaerb-del/MaxErbFootball`  (branch: `main`) — **PUBLIC repo**
- **Structure:** One self-contained `index.html` (~1.7 MB; fonts, CSS, and images all inline).
  Also a `CNAME` file (custom domain) — leave it alone.
- **Password gate:** The page is **AES-GCM encrypted**. Visitors enter a password on a gate
  screen; the content is decrypted in the browser and injected into `#app`.
  - The gate/lock is a full-screen overlay; unlocking removes the `locked` class and shows `#app`.
  - **Editing the actual content** (record, depth, stats, game log, hero copy) requires the page
    password to decrypt → edit → **re-encrypt** and replace the ciphertext in `index.html`.
- **Things OUTSIDE the encrypted blob** (edit freely, no password needed): the sticky
  **"Watch Live" bar** (pasted right after `<body>`), the page `<title>`/meta, and top-level CSS.
- **Brand tokens (for on-brand additions):**
  band/purple `#3C2465`, brand `#5A3392`, gold `#B8830F`, gold-bright `#E8B23A`,
  good/green `#2E7D5B`; fonts: Barlow Condensed (display), IBM Plex Sans (body), IBM Plex Mono.
  Supports light & dark mode via CSS variables — keep any additions using those variables.

### The "Watch Live" bar pattern (reusable each game week)
A sticky top bar linking to that week's stream, shown on **both** the login screen and the
unlocked page, styled with the brand tokens. It lives just after `<body class="locked">` and is
independent of the encrypted content, so it's a safe, quick weekly edit. Remove it after the game.

---

## 5. How updates get published

There are two modes, and it matters which one a session is in:

- **Cloud session (e.g. the scheduled weekly run):** Claude has **no access to Korey's computer**
  and **cannot push to GitHub**. It can research and build an updated `index.html`, then hand it
  over as a file for Korey to upload (GitHub web "Add files via upload," or GitHub Desktop, or
  the ✏️ editor).
- **On-computer session (Claude desktop app → "Run this task on your computer"):** Claude can
  work directly in the local clone and **commit + push to GitHub itself** — no file passing.
  This is the hands-off flow Korey prefers.

**Local setup already done on Korey's Mac:** GitHub Desktop installed + signed in to GitHub,
with `MaxErbFootball` cloned locally on `main`.

**Hands-off workflow (goal):**
1. Korey opens the Claude desktop app and starts the tracker task **on his computer**.
2. Grants the task access to the local `MaxErbFootball` folder.
3. Tells Claude the update in plain English (+ the page password if content changes).
4. Claude edits `index.html`, commits, and pushes to `main`. Site updates in ~1–2 min.

---

## 6. Weekly research checklist

1. **Roster** — bethelathletics.com football roster: Max's number/position, QB count, skill players.
2. **Depth chart / camp / game reports** — Bethel Athletics releases, McKenzie Banner,
   Mid-South Conference site, and Bethel's X **@BU_FootballTN**. Where is Max repping (QB/WR/returner)?
   Any QB1 competition signal among Teat, Clemmer, Max?
3. **Box scores** — did Max take any snaps or record stats? (ESPN team id **2064**; opponent
   athletics sites often post recaps with Bethel QB stats.)
4. **Injury / availability** — Max or the QB room.
5. **Scheme / roster / coaching news** affecting the offense.
6. **Max's own updates** — X @MaxwellErb (note: X is often not directly fetchable; search around it).

**Handy sources:** bethelathletics.com · espn.com (id 2064) · thesiac.com / opponent athletics
sites for recaps · mckenziebanner.com · victorysportsnetwork.com (NAIA).
**Note:** Bethel's official site sometimes blocks automated fetches (403/404) and X blocks
scraping — flag when a source can't be accessed rather than guessing.

---

## 7. How to report

- Lead with the **single most important change** since last week (or "quiet week, no changes").
- Then briefly cover: roster/depth chart, camp/game notes, availability, QB-competition signal.
- Tie back to the throughline: **path to starting QB vs. WR/returner contribution in 2026.**
- Be concise and honest; end with **source links**.
- For the scheduled cloud run: also send a **push notification** with the headline.

---

## 8. Security & housekeeping

- **The repo is PUBLIC.** Never commit the page password, and never paste it into any file here.
  The placeholder below stays a placeholder — provide the real password to Claude **in chat**,
  per session, only when a content edit needs it.
  - `PAGE_PASSWORD = <given in chat each session — do NOT store in this public repo>`
- Don't commit secrets, tokens, or anything you wouldn't want public.
- `CNAME` controls the custom domain — don't edit or delete it.
- Keep a mental backup: before a big content re-encrypt, it's fine to keep the prior
  `index.html` version in GitHub history (that's automatic on each commit).

---

*Last reviewed: 2026-09-19.*
