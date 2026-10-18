# Max Erb Football — Master Brief (v6)

> **Purpose:** Standing context file for the *Max Erb Football Updates* project and the
> **maxerbfootballupdates.com** website. Attach it to Claude at the start of any session so Claude
> is instantly up to speed on the player, the team, and — critically — **exactly how the encrypted
> site is edited and published**. v6 adds the hard lessons from the Oct 18, 2026 session.
>
> **Update Section 3 (Latest Known Status) and the game log every week.**
>
> *Brief last revised: 2026-10-18.*  ·  This file lives in a **PUBLIC** repo — see Section 9 before adding anything sensitive here.

---

## 0. Quick orientation for Claude — READ FIRST

- **Owner:** Korey Erb (Max's dad). Email: korey.a.erb@gmail.com
- **What this is:** A private, password-gated tracker website for family & friends following
  Max Erb's quarterback campaign at Bethel University (TN).
- **The ask, most weeks:** A concise, **honest** scouting/status update on Max, tied to the throughline
  of his realistic path to **starting QB vs. contributing at WR/returner**, then publishing that update
  to the site. Say plainly when it's a quiet week — don't pad.
- **Tone:** Warm but straight. No hype, no doom. Korey wants the real picture.

### 0a. The five failure modes — each one has actually happened
1. **Rebuilding the site instead of editing it.** The site is ONE encrypted `index.html` (Section 4).
   Claude must **never** generate a "new" page, a different design, or a non-encrypted replacement.
   If Claude does not have the real file, it must **stop and ask for it** — not improvise.
2. **Not having the real file.** In a cloud session Claude **cannot** fetch from GitHub (robots-blocked)
   and **cannot** push. Korey must **attach the current `index.html`** at the start of every update
   session (download it from the repo). No file = no update. See Section 5, step 0.
3. **Guessing status from web search.** Bethel's pages often render empty to automated fetches, and
   Max's roster page is under the `maxwell-erb` slug. Do **not** conclude "Max isn't on the roster"
   from an empty search. The **decrypted page** and **Korey** are the sources of truth for Max's status.
4. **Forgetting the timestamps.** Every publish refreshes **BOTH** "updated" stamps (top strip + footer),
   with time-of-day in Mountain time. (Section 4c.)
5. **Asking Korey to upload media files.** Videos/photos are embedded **inside** `index.html`. Never ask
   him to upload `.mp4`/`.jpg`/`.zip` files to the repo — it's public, and loose files are viewable by
   direct link, outside the password. The only thing he ever uploads is `index.html`.

### 0b. If `index.html` ever gets overwritten with a wrong version
GitHub keeps every prior version. Recovery (Korey, ~30 seconds):
`github.com/koreyaerb-del/MaxErbFootball/commits/main` → click the last **good** commit → **Browse files**
(or the `<>` icon) → `index.html` → **Download raw file** → attach to Claude. Claude edits that; Korey uploads
the result, which both restores the site and applies the update in one commit.

---

## 1. The player — Max (Maxwell) Erb

- **Position:** Quarterback. **Gameday jersey #18** (practice #13).
- **Class / eligibility:** Sophomore, 4 years of eligibility remaining. **Age 20** (birthday Sept 29; turned 20 on
  Sept 29, 2026 — site ticker updated Oct 18).
- **On Bethel's official roster:** Yes — **#18, QB, So., 6-1, 175 lb, Bloomington, MN, prev. UW–River Falls.**
  Roster page: `bethelathletics.com/sports/football/roster/maxwell-erb/4194` (plain "Max Erb" searches miss it).
  Site ticker shows 6'1" / 185 lb (family figure).
- **Measurables:** ~6'1", ~175–185 lb, 10" hands, 35" vertical, dual-threat, deep ball ~60–65 yds, benches 225 for 6–7 reps.
- **Hometown / HS:** Bloomington, MN — Bloomington Jefferson HS. Senior year (2024): ~1,271 pass yds, 12 TD, 9 INT.
- **Path:** Transferred to **Bethel (2026)** from **UW–River Falls** (Wisconsin), where in 2025 he was a true-freshman
  backup QB on the **NCAA D-III national championship** team (behind Gagliardi Trophy winner Kaleb Blaha); no game stats.
- **Recruited by:** Bethel OC **Riley Reid** (@Coach_RReid1). QB coach: **Joaquin Collazo** (former Bethel standout QB).
- **Online:** X **@MaxwellErb** · Hudl **hudl.com/profile/19604832/max-erb**
- **2026 stat line at Bethel through 6 games:** 1 game appearance, 1 assisted tackle (special teams). **Zero offensive snaps.**

---

## 2. Bethel University 2026 context

- **School:** Bethel University, McKenzie, TN. **NAIA**, **Mid-South Conference**. Wildcats ("Cats"). Home: Walter Butler Stadium.
- **Head coach:** Chris Springer (2nd year). **OC** Riley Reid (promoted from OL/run-game; recruited Max) ·
  DC Kris Beauchamp · ST Deandre Riddick.
- **Departures after 2025:** OC Drew Chance → Memphis; 2025 starting QB Destin Chance graduated. **2025 record:** 4–5.
- **QB room (2026) — as of Oct 18:**
  - **Silas Teat (#4)** — Jr. Started the season; snaps dipped late Sept when Brown took over; **went the distance Oct 17 vs
    Cumberlands and appeared to hurt his hand late.** Season: 51-90, 754 yds, 4 TD, 4 INT.
  - **Jaylan Brown (#10)** — new (via Georgia Military). Took the bulk of the QB work late Sept–Oct 10; **injured, DNP Oct 17;
    status uncertain.** Season: 28-64, 417 yds, 3 TD, 1 INT.
  - **Max Erb (#18)** — with Brown out he was the **QB2 on Oct 17**, one snap from the field — **still did not play**, even with
    Teat's late hand injury. Dresses/travels every week. Performing well in practice per Max.
  - *Nathan Clemmer* (returning So.) has not appeared in any passing stats; not in the rotation.
- **Coaches' feedback to Max (summary; full detail lives in the encrypted journal, not here):** they want him to read the
  defense better and play as a "system QB" — work through all reads before breaking the pocket — while acknowledging
  improvement in a new system. The WR/athlete reps and RPO "Max package" discussed in recruiting have **not** been used in a
  game through 6 weeks. Max is frustrated by the lack of snaps; happy with school, teammates, and the community otherwise.

---

## 3. Latest known status  *(update every week; date it)*

**As of 2026-10-18 (record 2–4, 0–1 MSC):**
- **Depth chart:** Teat → **Erb (QB2 on Oct 17 with Brown out)** → Brown (injured). If Brown returns, expect him back ahead of Max.
- **Max's game usage:** Dressed · DNP in all six games. Zero offensive snaps/stats at Bethel.
- **Results / game log:**
  - **W 16–3** vs Lane — Aug 29 (H). Teat went the distance. Max DNP.
  - **L 7–48** vs #2 Keiser — Sep 12 (H). Teat 5-15, 168, 1 TD; Brown 1-2, 25. Max DNP.
  - **L 27–28 (OT)** at Webber Int'l — Sep 19 (A). Teat hurt (3-6, 36); Brown 5-16, 107, 2 TD. Max DNP.
  - **L 7–31** at Pikeville — Sep 26 (A). Brown started/most of game; Teat 1 drive, INT. Max DNP.
  - **W 21–10** vs Faulkner — Oct 10 (H, MSC opener). Brown 8-18, 108; Teat 5-9, 87, 1 TD (55-yd to Dowdell); T. Smith 76 rush
    yds + TD; Dowdell 130 rec yds. Max dressed, DNP.
  - **L 21–38** vs Univ. of the Cumberlands — Oct 17 (H, **Bethel Homecoming**). Brown out injured; Teat went the distance
    (14-27, 241, 1 TD, 2 INT per cumulative stats), hurt hand late. **Max was QB2, DNP.**
- **Next up:** **at Georgetown College (Ky.)** — Sat **Oct 24**, **12:30 PM CT / 1:30 PM ET**, Toyota Stadium, Georgetown, KY.
  **It is Georgetown's Homecoming.** Away games stream via the host; Georgetown's video link posts on the Oct 24 row of
  `georgetowncollegeathletics.com/sports/fball/2026-27/schedule` on gameday (their site blocks automated fetch — Claude could
  not capture a direct player URL). Backup: Mid-South Network `team1sports.com/midsouth/`. Live stats: Bethel hub.
- **Read:** Six games, zero snaps. With Brown hurt, Max is one injury from the field — but the staff didn't use him even when the
  window opened Oct 17. His realistic 2026 path remains relief/injury duty plus the still-unused WR/"Max package" role; 2027 is the
  real competition window (Teat is a junior).
- **Site state (after Oct 18 publish):** stamps = Oct 18, 2026 · 2:50 AM MDT · record 2–4 · next-up chip & Watch Live bar =
  Georgetown · gallery = `w7gtown, w6cumb, coach, rival, team, heroB, heroA` · Practice Film card = **7 clips** · age 20 ·
  file size **16.6 MB**.

**Full 2026 schedule (all times Central):**
Aug 29 Lane (H) ✅W · Sep 5 BYE · Sep 12 Keiser (H) ❌L · Sep 19 @ Webber Intl. ❌L(OT) · Sep 26 @ Pikeville ❌L ·
Oct 3 BYE · Oct 10 Faulkner (H) ✅W · Oct 17 Cumberlands KY (H, Homecoming) ❌L · **Oct 24 @ Georgetown College (their HC)** ·
Oct 31 Campbellsville (H, Senior Day) · Nov 7 @ Lindsey Wilson · Nov 14 @ Cumberland Univ. (TN)

---

## 4. The website & repository — technical internals (read before editing)

- **Live site:** https://maxerbfootballupdates.com  (page title: "Max Erb QB Tracker")
- **GitHub repo:** `koreyaerb-del/MaxErbFootball` (branch `main`) — **PUBLIC repo**. GitHub Pages deploys from `main`.
- **Structure:** One self-contained **`index.html`** (fonts, CSS, JS, images, and now videos all inline). Plus **`CNAME`**
  (custom domain — **never touch**) and this brief. **Nothing else belongs in the repo.**
- **Brand tokens (CSS variables; light & dark):** band/purple `#3C2465`, brand `#5A3392`, gold `#B8830F`, gold-bright
  `#E8B23A`, good/green `#2E7D5B`. Fonts: Barlow Condensed (display), IBM Plex Sans (body), IBM Plex Mono.

### 4a. Encryption — why Claude can't "see" the site without the file + password
- The page content is **AES-GCM encrypted** and injected into `#app` after the visitor enters the password.
- Near **line ~370** is one constant line: `var SALT = "…", IV = "…", CT = "…";` (find it with a regex, don't trust the line number).
- Scheme: **PBKDF2, 150,000 iterations, SHA-256** → **AES-GCM-256**; SALT/IV/CT are base64.
- The **decrypted plaintext IS the site's real content**: masthead stamp, hero pills, ticker, gallery image JSON, "Max's Role ·
  Latest" banner, Film Room, **Practice Film card**, Season Results, Gameday card, QB Depth Chart, package status, "Feedback
  Directly from Max" journal, Summer Camp, coach-investment card, NAIA explainer, Forecast, Off the Field, Career Path, Game
  Log table, footer stamp.

### 4b. Password vs. no password
- **Inside the encrypted blob (needs password):** everything listed in 4a, including **both timestamps** and `#galdata`.
- **Cleartext (no password):** the sticky **Watch Live bar**, the gallery **slide list** `var defs = [...]`, `<title>`/meta, CSS.

### 4c. ⚠️ The TWO "updated" stamps — refresh BOTH, every single time
1. **Top strip:** `<div class="mh-meta">Private &middot; Family &amp; Friends &middot; Updated <DATE &middot; TIME TZ></div>`
2. **Footer:** `<div>Last updated <DATE &middot; TIME TZ> &middot; Weeks … </div>`
- **Format:** Mountain time with time-of-day, e.g. `Oct 18, 2026 &middot; 2:50 AM MDT`. Generate it from the clock at build time
  (`America/Denver`), never hand-type it.

### 4d. Gallery / photos
- Images: `<script type="application/json" id="galdata">{ "key": "data:image/jpeg;base64,…", … }</script>` — **encrypted**.
  Current keys: `heroA, heroB, coach, rival, team, w6cumb, w7gtown`. (Removed Oct 18: `w2keiser`, `w4pike`.)
- Slide list: `var defs = [ {k:'key', c:'caption'}, … ]` — **cleartext**, filtered by `IM[k]`. New slides go at the **top**.
- Captions use `—` / `–` escapes and `&amp;` (they're injected via innerHTML).
- To add a photo: convert to JPEG (~q85), add its data URL to `#galdata` (encrypted) **and** a `{k,c}` entry to `defs` (cleartext).
  Landscape ~900–1150 px wide matches the existing set. **The site's caption bar overlays the bottom ~60 px of each slide** —
  keep graphics' bottom edge free of text.
- **Made-up matchup graphics are fine** (Korey OK'd it Oct 18) — typographic, in brand colors, **no team logos/mascots**.

### 4e. Practice Film card (added Oct 18)
- A `<section class="card">` titled **"Practice Film — Max's Big Plays"** with a gold `CONFIDENTIAL · DO NOT SHARE` tag, placed
  right after the Film Room (YouTube) card. **Inside the encrypted blob.**
- Each clip is a `<figure>` with `<video controls playsinline preload="metadata" poster="data:image/jpeg;base64,…">` and
  `<source src="data:video/mp4;base64,…" type="video/mp4">` plus a `<figcaption>` ("Practice · Oct 13, 2026 · clip 2").
- **The card's lead sentence states the clip count** ("Seven of Max's big-time plays … (Sep 29, Oct 6 and Oct 13 sessions)") —
  update it whenever clips are added/removed. Current: **7 clips** (3× Sep 29, 2× Oct 6, 2× Oct 13).
- Clips are confidential at Max's request (practice film) — they exist **only** here, never on YouTube or as loose repo files.

### 4f. Video encoding recipe & the size budget (important)
- Source clips are iPhone screen recordings of Hudl, `.mov`/HEVC, **444×960 with 90° rotation metadata → native display is
  960×444 landscape.** ffmpeg auto-rotates; encode at native size, don't upscale.
- Recipe that works: `ffmpeg -i in.mov -vf "scale=960:-2" -c:v libx264 -crf 27 -preset slow -pix_fmt yuv420p -c:a aac -ac 1
  -b:a 40k -movflags +faststart out.mp4` → ~1–1.6 MB per 15–30 s clip. Poster: one frame at ~640 px wide, JPEG q6.
- **Cost:** a video inside the page costs about **1.78× its MP4 size** (base64 as a data URL, then base64 again in the
  ciphertext). The page was 1.95 MB before video; **16.6 MB with 7 clips.**
- **Hard limit: GitHub's web uploader rejects files over 25 MB.** Keep `index.html` **≤ ~22 MB**. Above that, trim clips, encode
  tighter (CRF 29–30), or Korey uploads with GitHub Desktop (100 MB limit). Always report the final size.
- Headless Chromium in Claude's sandbox has **no H.264 decoder** — videos show no duration there. That is expected, not a bug;
  real Chrome/Safari/Edge/iOS/Android play them. Verify the embed by byte-comparing the base64 to the MP4 instead.

### 4g. The "Watch Live" bar (reusable each game week — cleartext)
- Sticky top bar between `WATCH LIVE BAR (added)` / `END WATCH LIVE BAR (added)` comment markers, just after `<body class="locked">`.
- Pieces to edit: `aria-label`, the game text `<span>`, two buttons (`href` + label), and the small backup line.
- **Home games:** Hudl `fan.hudl.com/usa/tn/mckenzie/organization/6212/bethel-university` + Bethel Sports Network YouTube
  `youtube.com/channel/UC_d5gbqHpuveZZcL7vGOX1A/live`; backup = Bethel hub `bethelathletics.com/sports/fball/index`.
- **Away games:** host school's stream/schedule page + Mid-South Network `team1sports.com/midsouth/`; live stats = Bethel hub.
- The **Gameday card** (encrypted) carries the same links in long form — update both. Remove/reset the bar after each game.

---

## 5. How to edit the encrypted content (cloud session, step-by-step)

0. **Korey attaches the CURRENT `index.html`** (downloaded from the repo). Claude never fetches it and never starts from anything else.
1. **Get the page password from Korey in chat.** Keep it **only in an environment variable** (`PW=… node …`) — never in a file,
   never in this brief.
2. **Decrypt** `CT` with PBKDF2(pw, SALT, 150000, SHA-256) → AES-GCM key; decrypt with `IV`. Node's `crypto.webcrypto.subtle` works.
   Write plaintext to a scratch file.
3. **Edit the plaintext with exact single-match string replaces** (assert exactly one match per edit). Lines are long — read
   with a truncating `awk` so base64 doesn't flood the context.
4. **Update BOTH timestamps** from the clock (Section 4c).
5. **Re-encrypt** with the **same SALT** and a **fresh random 12-byte IV**. Replace only the `IV` and `CT` values.
6. **Cleartext edits** (Watch Live bar, `defs`) go in the outer HTML.
7. **Verify:** re-decrypt the new file and `cmp` against the edited plaintext (byte-identical); grep for each edit; unlock it in a
   headless browser (Playwright at `/opt/pw-browsers/chromium`) and screenshot the changed sections. Check file size vs. 4f.
8. **Hand `index.html` back**; delete every scratch file that held the password or plaintext; confirm with a grep.

---

## 6. How updates get published

- **Cloud session (scheduled weekly run / chat):** Claude returns the finished **`index.html`**; Korey uploads it to `main`
  (GitHub web **Add file → Upload files → Commit**). One file. ⚠️ Upload the **newest** file Claude sent.
- **On-computer session (Claude desktop app → "Run this task on your computer"):** Claude edits the local clone and commits +
  pushes `main` itself (content edits still need the page password). GitHub Desktop is installed; `MaxErbFootball` cloned on `main`.
- **Repo hygiene:** only `index.html`, `CNAME`, and the brief belong there. Any loose `.mp4`/`.jpg`/`.zip` in the repo is
  **publicly viewable** — delete them. (Four such files were uploaded by mistake on Oct 18 — confirm they're gone.)

---

## 7. Weekly research checklist + sources

1. **Roster** — direct player URL `bethelathletics.com/sports/football/roster/maxwell-erb/4194` (list pages fetch empty).
2. **Results / box scores** — **The official cumulative stats PDF is the best single source**:
   `https://s3.us-east-2.amazonaws.com/sidearm.nextgen.sites/bethelathletics.com/stats/football/2026/pdf/cume.pdf`
   (passing/rushing/receiving/defense for every player, record, results list). A player's week-over-week delta gives the
   per-game line when a box score is unreachable.
   Box scores: `bethelathletics.com/boxscore.aspx?id=NNN&path=football` — ids are **not** sequential by game (Faulkner 2026 = 663;
   664 was a 2025 game). Find the id via the opponent-history page, e.g. `bethelathletics.com/sports/football/opponent-history/faulkner/17`.
   Schedule/results: `bethelathletics.com/sports/football/schedule/2026` ("HC" = Homecoming).
3. **Depth chart / QB1 signal** — box-score usage + Korey. Bethel releases, McKenzie Banner (paywalled), MSC site, X **@BU_FootballTN**.
4. **Injury / availability** — usually from Korey, not public sources.
5. **Opponent info** — opponent athletics sites (PrestoSports) often **block automated fetch** (Georgetown did). Use their
   schedule-announcement releases when the schedule page fails. Google search result links are not fetchable — ask Korey to paste the actual URL.
6. **Max's own updates** — X **@MaxwellErb** (X blocks scraping).
- **Gotchas:** `athletics.bethel.edu` is **Bethel University in Minnesota** (D-III Royals) — wrong school; MaxPreps "Bethel Wildcats"
  is a Connecticut high school. Always use **bethelathletics.com** (Tennessee). Flag "couldn't verify" rather than stating a
  negative. When Korey provides a fact, that's authoritative for the family page — note it's his info.

---

## 8. How to report (the weekly write-up)

- Lead with the **single most important change** since last week (or "quiet week").
- Then: roster/depth, game notes, availability, QB-competition signal.
- Tie back to the throughline: **path to starting QB vs. WR/returner contribution in 2026** (and the 2027 window).
- Concise and honest; end with **source links**. Scheduled cloud run: send a **push notification** with the headline.

---

## 9. Security & housekeeping

- **The repo — and this brief — are PUBLIC.** Never commit the page password or write it in any file. Placeholder only:
  `PAGE_PASSWORD = <given in chat each session — never stored>`.
- **Keep sensitive specifics on the encrypted page, not in this brief.** Coaches' verbatim feedback, locker-room morale,
  recruiting-promise details, and family opinions belong in the encrypted journal. This brief summarizes at a neutral level.
  (GitHub Pages on a free account requires a public repo, so assume anything in the repo can be read.)
- Practice film is confidential at Max's request — only inside the encrypted page.
- After a content edit, delete sandbox scratch files that contained the password or decrypted plaintext.
- `CNAME` controls the custom domain — don't edit or delete it.
- GitHub history is the backup (Section 0b).

---

## 10. ✅ Update protocol — run this checklist EVERY publish

1. [ ] Korey attaches the **current `index.html`**; get the page password in chat (env var only).
2. [ ] Decrypt; treat the decrypted content as the true current status.
3. [ ] Update content: **record**, **game-log row(s)**, **Season Results**, **next-up chip**, **"Max's Role · Latest"**,
       **QB Depth Chart** + note, **package status**, add a **journal entry**, **Gameday card** links/text.
4. [ ] **Refresh BOTH timestamps** (top strip + footer) — current date **and** time, Mountain, from the clock.
5. [ ] **Watch Live bar** (cleartext) → next game, correct home/away links; remove after a game.
6. [ ] **Gallery**: add the week's graphic(s) (data URL in `#galdata` + `defs` entry at top); retire stale ones if asked.
7. [ ] **Practice Film**: add/remove clips per Korey; encode per 4f; update the count in the lead sentence.
8. [ ] Re-encrypt (same SALT, fresh IV); **verify** round-trip + browser unlock; **check size ≤ ~22 MB**.
9. [ ] Deliver `index.html` **only**; delete scratch; remind Korey to upload the newest file and keep the repo free of loose media.
10. [ ] Update this brief's **Section 3** + game log; bump the "last revised" date; deliver as `MASTER_BRIEF_<n>.md`.
