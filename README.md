# Netra
Privacy-first local prototype for reviewing digital safety: alerts, media authenticity, case tracking, and complaint drafts.
NETRA Guardian is a local, privacy-first prototype that helps people review their digital safety from inside their own browser. It runs on a small Node.js server (v18 or newer) with no dependencies, API keys, or accounts. 

**What it includes**
- **Dashboard and alerts:** Sample alerts such as a public post exposing an email address or phone number, a repeated routine that reveals a pattern, or a look-alike profile. They load from a CSV file and are sorted by priority.
- **Real or Rendered?:** A media-authenticity workflow with four prepared scenarios, an optional local image preview, an uncertainty indicator, open questions, and suggested next steps. Review notes can be copied.
- **Case Tracker:** Any review can be saved as a case, with progress tracking and a field to record your own next action.
- **URL checker:** Flags common warning signs in a link without ever opening it.
- **Profiles and keywords:** Local references to your social profiles and keywords you want to watch.
- **Complaint report:** Select evidence files, then copy or download a text draft to submit yourself through the official portal.

**Limitations**
- It is a simulated front-end demo, not a real detector. It doesn't scan social accounts, run an AI detector, read image metadata, do reverse-image search, or submit complaints anywhere.
- Alerts and authenticity results are illustrative only.

**Privacy**
- Everything stays on your device. Preferences and cases are saved in browser local storage, unencrypted and not synced.
- Evidence files and previewed images are never uploaded or stored. Only filenames are recorded.

**Files:** `index.html`, `style.css`, `script.js`, `server.js`, and `sample_alerts.csv`.
