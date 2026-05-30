# MCAS Companion

A single-file, offline, phone-first companion for someone newly diagnosed with **Mast Cell Activation Syndrome (MCAS)** in the Oakland / Bay Area. It turns a dense survival playbook into a calm, step-by-step journey — with a built-in symptom log, a Bay Area specialist directory, an always-one-tap anaphylaxis screen, and a prominent "what *not* to do" section.

> ⚠️ **This is information, not medical advice.** Every drug, dose, supplement, and strategy in the app must be vetted by a treating physician before acting on it. The app says this too, on every screen.

---

## How to use it

1. **Open `mcas-companion.html`** in any web browser (double-click it, or drag it onto a browser window). No internet, no install, no account.
2. **Add it to your phone home screen** so it feels like an app:
   - **iPhone (Safari):** open the file → Share → *Add to Home Screen*.
   - **Android (Chrome):** open the file → ⋮ menu → *Add to Home screen*.
   - To get it onto the phone in the first place, email the file to yourself or put it in iCloud/Drive and open it there.
3. **Work the journey at your own pace.** Three "Acts":
   - **Act I — This Week:** the immediate, evidence-based moves.
   - **Act II — Building the System:** the 1–3 month project.
   - **Act III — If You Get Stuck:** refractory-case escalation (most people never need it).
   Check off tiny tasks as you do them. Progress saves automatically.
4. **Log one signal a day.** The *Log* tab takes ~10 seconds — symptoms, sleep, stress, food, anything new. Bring this to every appointment; it's the most useful thing you'll carry in.
5. **Red button, top of every screen = Anaphylaxis.** One tap shows recognition signs and the act-now steps in big type. Read it once now, while calm, so it's familiar if you ever need it.

## The tabs

| Tab | What's there |
|---|---|
| **Journey** | The three Acts, progress bars, badges, identity framing. |
| **Log** | Daily symptom entry, 7-day strip, gentle streak, backup/restore. |
| **Care** | Bay Area specialists + national experts — tap to call, tap for map, with honest notes on what each actually treats. |
| **Cautions** | The traps: the diet cage, predatory clinics, supplement spirals, and the signals it's time to change the plan. **Read this one.** |
| **Reference** | The treatment ladder, triggers, diet, supplements (honestly graded), lifestyle, trusted resources. Tap to expand. |

## Backing up your symptom log (important)

All data lives **only in this browser, on this device** — nothing is uploaded anywhere. That means:

- **Clearing browser data, switching browsers, or switching phones will erase it** unless you back up.
- In the **Log** tab, tap **⬇ Export backup** to download a `.json` file. Do this every week or two — email it to yourself or save it to cloud storage.
- To restore (new phone, new browser), tap **⬆ Import backup** and pick that file.

## What this app is — and isn't

- **Is:** an organizer, a habit scaffold, and a calm reference so a methodical few-months project doesn't feel like an emergency.
- **Isn't:** a diagnosis, a treatment, or a substitute for your care team. The core message of the source material is built in: *medication-first, not diet-first; one variable at a time; the proven core is cheap and safe; mute the noise; be most skeptical when most desperate.*

## Technical notes

- Single self-contained `mcas-companion.html` — vanilla HTML/CSS/JS, no frameworks, no build step, no network calls. Works fully offline.
- Persistence via the browser's `localStorage`. (Note: opening from a strict private/incognito window may not persist between sessions.)
- All content is drawn from the *MCAS Survival Playbook — Oakland / Bay Area Edition*, simplified for readability but not altered in substance.
