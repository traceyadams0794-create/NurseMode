# NurseMode MVP

**Replace doom scrolling with nursing school content and NCLEX prep.**

A mobile-first Progressive Web App (PWA) built for nursing students. Swipe through bite-sized study cards instead of social media. Flashcard decks organized by course/system with spaced repetition tracking.

---

## What's Inside

### Feed (Doom-Scroll Replacement)
- 41 swipeable cards: tips, mnemonics, and NCLEX practice questions with rationales
- Covers pharmacology, med-surg, OB, peds, mental health, critical care, and more
- Tap to answer NCLEX questions and see full rationales

### Flashcard Decks (17 decks, 227+ cards)
| Deck | Cards | Topics |
|------|-------|--------|
| Fundamentals | 19 | Nursing process, safety, infection control, assessment |
| Cardiovascular | 17 | HF, MI, EKG, shock, DVT, PE, medications |
| Respiratory | 14 | COPD, asthma, pneumothorax, ARDS, ventilators, ABGs |
| Neurological | 13 | ICP, stroke, seizures, meningitis, spinal cord injury |
| Endocrine/Diabetes | 14 | DKA, HHS, thyroid, Addison's, Cushing's, SIADH/DI |
| Renal & Electrolytes | 13 | AKI, CKD, dialysis, all electrolyte imbalances |
| GI System | 12 | GERD, Crohn's/UC, liver cirrhosis, pancreatitis |
| Musculoskeletal | 9 | Compartment syndrome, fractures, hip replacement |
| Hematology/Oncology | 10 | Anemia, sickle cell, transfusions, DIC, chemo care |
| Pharmacology | 17 | Antidotes, drug classes, interactions, insulin types |
| OB/Maternity | 14 | Labor stages, FHR, preeclampsia, hemorrhage, mag sulfate |
| Pediatrics | 14 | Milestones, croup vs epiglottitis, Kawasaki, pyloric stenosis |
| Mental Health | 14 | Therapeutic comm, psych meds, NMS, substance abuse |
| Prioritization & Delegation | 10 | ABCs, RN/LPN/UAP scope, delegation rules |
| Infection Control | 10 | Precautions, sterile field, TB, MRSA, C. diff |
| Critical Care/Emergency | 12 | Shock types, vasopressors, ACLS, ventilators |
| NCLEX Practice Questions | 15 | Full questions with answer choices and rationales |

### Features
- Daily study streak tracking
- Progress tracking per deck
- Bookmark/save cards for review
- Shuffle mode
- Offline support (PWA/service worker)
- Works as a home screen app on iPhone and Android

---

## Tech Stack
- **Vanilla HTML/CSS/JS** — zero dependencies, zero build step
- **Progressive Web App** — installable, works offline
- **Mobile-first** — designed for phone screens

---

## Project Structure
```
nursing app/
  index.html      — App UI + all JavaScript logic
  data.js         — All content (feed cards, flashcard decks)
  manifest.json   — PWA manifest (app name, icon, theme)
  sw.js           — Service worker (offline caching)
  icon.svg        — App icon
  README.md       — This file
```

---

## Deploy (Get It On Your Phone)

### Option A: Netlify Drop (30 seconds, no account needed)
1. Go to https://app.netlify.com/drop
2. Drag and drop all 5 app files onto the page
3. Copy the URL it gives you
4. On your phone: open URL in Safari → Share → "Add to Home Screen"

### Option B: GitHub Pages (free, permanent)
1. Create a GitHub repo
2. Push these files to `main` branch
3. Go to Settings → Pages → Source: main branch
4. Your app is live at `https://yourusername.github.io/repo-name`
5. On your phone: open URL in Safari → Share → "Add to Home Screen"

### Option C: Local (testing only)
```bash
cd "/Users/traceyadams/nursing app"
python3 -m http.server 8080
```
Open `http://localhost:8080` in your browser.

---

## Content Sources
- Saunders NCLEX-RN Comprehensive Review
- Mosby's Comprehensive Review of Nursing for NCLEX-RN
- Quick Facts for NCLEX
- NCLEX-RN Exam Cram Practice Questions
- Prioritization, Delegation & Management of Care for NCLEX-RN

---

## MVP Roadmap

### v1.0 (Current)
- [x] Scrollable study feed (doom-scroll replacement)
- [x] NCLEX questions with tap-to-answer and rationales
- [x] 17 flashcard decks organized by course/system
- [x] Progress tracking and streak counter
- [x] Bookmark/save cards
- [x] Offline PWA support

### v1.1 (Next)
- [ ] Search across all cards
- [ ] Spaced repetition algorithm (SM-2)
- [ ] Quiz mode (timed practice tests)
- [ ] Dark/light theme toggle

### v2.0 (Future)
- [ ] AI tutor (chat with your nursing PDFs via AnythingLLM API)
- [ ] User-created flashcards
- [ ] Study groups / share decks
- [ ] Audio pronunciation for drug names
- [ ] Sync progress across devices

---

Built for Tracey
